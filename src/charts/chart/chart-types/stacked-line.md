# Stacked Line

## Stacked

[`Blazor Stacked Line Chart`](https://www.syncfusion.com/blazor-components/blazor-charts/chart-types/stacked-line-chart)  is like a line chart where lines of the data don’t get overlapped because they will be cumulative at each point. To render a stacked line series, use series [`Type`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~Type.html) as `StackingLine`.

{% aspTab template="chart/series/line-charts/stacked-line", sourceFiles="stacked-line.razor" %}

{% endaspTab %}

![Stacked Line](../images/chart-types-images/stacked-line.png)

## Customization

You can use the following properties to customize the stacked line series.

* [`Fill`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~Fill.html) – used to change the color of the stacked line.
* [`Width`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~Width.html) – used to change the width of the stacked line.
* [`Opacity`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.Charts.ChartSeries.html#Syncfusion_Blazor_Charts_ChartSeries_Opacity) – used to control the transparency of the chart series.
* [``DashArray``](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~DashArray.html) – used to render stacked line series with dashes.

> Note: You can refer to our [`Blazor Charts`](https://www.syncfusion.com/blazor-components/blazor-charts) feature tour page for its groundbreaking feature representations. You can also explore our [`Blazor Chart example`](https://blazor.syncfusion.com/demos/chart/line?theme=bootstrap4) to knows various chart types and how to represent time-dependent data, showing trends in data at equal intervals.

## See Also

* [Data label](../data-labels)
* [Tooltip](../tool-tip)