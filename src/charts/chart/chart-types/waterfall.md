# Waterfall Chart

## Waterfall

Waterfall chart helps to understand the cumulative effect of the sequentially introduced positive
and negative values. To render a Waterfall series, use series [`Type`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~Type.html) as
`Waterfall`. [`IntermediateSumIndexes`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~IntermediateSumIndexes.html)
property of waterfall is used to represent the in between sum values and
[`SumIndexes`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~SumIndexes.html)
is used to represent the cumulative sum values.

{% aspTab template="chart/series/other-types/waterfall", sourceFiles="waterfall.razor" %}

{% endaspTab %}

![Waterfall Chart](../images/othertypes/waterfall.png)

## Customization of Waterfall Series

The negative changes of waterfall charts is
represented by using [`NegativeFillColor`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~NegativeFillColor.html)
and the summary changes are represented by using [`SummaryFillColor`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~SummaryFillColor.html)
properties.

By default, the NegativeFillColor as ‘#E94649’ and the SummaryFillColor as ‘#4E81BC’.

{% aspTab template="chart/series/other-types/custom-waterfall", sourceFiles="custom-waterfall.razor" %}

{% endaspTab %}

![Customization](../images/othertypes/waterfall-custom.png)

**New Note:** You can refer to our [`Blazor Charts`](https://www.syncfusion.com/blazor-components/blazor-charts) feature tour page for its groundbreaking feature representations. You can also explore our [`Blazor Chart example`](https://blazor.syncfusion.com/demos/chart/line?theme=bootstrap4) to knows various chart types and how to represent time-dependent data, showing trends in data at equal intervals.

## See Also

* [Data label](../data-labels)
* [Tooltip](../tool-tip)