# Text placing center of the doughnut

The annotations are used to mark the specific area of interest in the chart area with texts, shapes or images.

By using the content option of annotation property, you can specify the Id of the element that needs to be displayed in the chart area.

To display the text placing center of the doughnut, `ContentTemplate` should be provided within the `AccumulationChartAnnotation` directive and create the div element inside `ContentTemplate`. we can access the div element attribute to text placing the center of the doughnut.

```razor
        <AccumulationChartAnnotation X="40%" Y="48%" CoordinateUnits="Units.Pixel" Region="Regions.Chart">
                <ContentTemplate>
                   <div class="donut-text">Chart Annotation</div>
                </ContentTemplate>
            </AccumulationChartAnnotation>
        </AccumulationChartAnnotations>
```

{% aspTab template="chart/accumulation-charts/how-to/do-nut", sourceFiles="do-nut.razor" %}

{% endaspTab %}

**New Note:** You can refer to our [`Blazor Charts`](https://www.syncfusion.com/blazor-components/blazor-charts) feature tour page for its groundbreaking feature representations. You can also explore our [`Blazor Chart example`](https://blazor.syncfusion.com/demos/chart/line?theme=bootstrap4) to knows various chart types and how to represent time-dependent data, showing trends in data at equal intervals.