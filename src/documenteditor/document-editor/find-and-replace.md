---
title: "Find and Replace"
component: "Word processor"
description: "Learn how to find a text in Blazor Word processor and replace it with another text."
---

# Find and Replace

Documents can be long, and you might need to search through the text to find and select specific words, text sequences, sentences, or paragraphs and then replace them with the desired content. This Word processor (DocumentEditor) provides a built-in navigation pane like Microsoft Word on the left of the editor.

You can use the search box at the top of this navigation pane to find all the instances of a specific word or phrase in the document. When you enter a word in the search box and perform search, it highlights all the occurrences of those words in the document and displays them below the search options in the pane. When you click to a search result, the cursor or selection move directly to that location in the document.

You can open the navigation pane using the `Ctrl+F` shortcut key and close using the `ESC` key.

## Show or hide navigation pane

You can programmatically toggle the visibility of navigation pane using the `ShowOptionsPane()` method.

```csharp
@using Syncfusion.Blazor.DocumentEditor

<button @onclick="OpenOptionsPane">OpenOptionsPane</button>
<SfDocumentEditorContainer @ref="container" EnableToolbar=true></SfDocumentEditorContainer>

@code {
    SfDocumentEditorContainer container;
    protected void OpenOptionsPane(object args)
    {
        container.DocumentEditor.ShowOptionsPane();
    }
}
```

## Search

You can invoke the search or find text functionality programmatically using the `FindAll()` method. Also, you can customize the search operation with options such as “**match case**” and “**whole words only**”. The following code example explains how to perform text search without any search options.

```csharp
@using Syncfusion.Blazor.DocumentEditor

<button @onclick="FindAll">Find All</button>
<SfDocumentEditorContainer @ref="container" EnableToolbar=true></SfDocumentEditorContainer>

@code {
    SfDocumentEditorContainer container;
    protected void FindAll(object args)
    {
        container.DocumentEditor.Search.FindAll("Some text", FindOption.None);
    }
}
```
