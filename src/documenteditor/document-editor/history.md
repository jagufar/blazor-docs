---
title: "Undo and redo"
component: "Word processor"
description: "Learn how undo and redo can be done in Blazor Word processor and how to customize its limit."
---

# History

Document editor tracks the history of all editing actions done in the document, which allows undo and redo functionality.

## Enable or disable history

Inject the `EditorHistory` module in your application to provide history preservation functionality for `DocumentEditor`. Refer to the following code example.

```csharp
@using Syncfusion.Blazor.DocumentEditor

<SfDocumentEditor @ref="documentEditor" IsReadOnly=false EnableEditor=true EnableSelection=true>
    <DocumentEditorContainerEvents Created="OnLoad"></DocumentEditorContainerEvents>
</SfDocumentEditor>

@code {
    SfDocumentEditor documentEditor;
    protected void OnLoad(object args)
    {
        documentEditor.EnableEditorHistory = true;
    }
}
```

You can enable or disable history preservation for a document editor instance any time using the `EnableEditorHistory` property. Refer to the following sample code.

```javascript
documentEditor.EnableEditorHistory = true;
```

## Undo and redo

You can perform undo and redo by `CTRL+Z` and `CTRL+Y` keyboard shortcuts. Document editor exposes API to do it programmatically.
To undo the last editing operation in document editor, refer to the following sample code.

```javascript
documentEditor.EditorHistory.Undo();
```

To redo the last undone action, refer to the following code example.

```javascript
documentEditor.EditorHistory.Redo();
```

## Stack size

History of editing actions will be maintained in stack, so that the last item will be reverted first. By default, document editor limits the size of undo and redo stacks to 500 each respectively. However, you can customize this limit. Refer to the following sample code.

```javascript
documentEditor.EditorHistory.SetRedoLimit(400);
documentEditor.EditorHistory.SetUndoLimit(400);
```