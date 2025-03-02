# 100% Stacked Bar

## 100% Stacked

Shows the relative percentage of multiple data series in stacked bars. The cumulative proportion of each stacked bar always totals 100%. To render a [`100% stacked bar`](https://www.syncfusion.com/blazor-components/blazor-charts/chart-types/100-stacked-bar-chart) series, use series [`Type`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~Type.html) as `StackingBar100`.

{% aspTab template="chart/series/bar-charts/100%stackedbar", sourceFiles="stackedbar100.razor" %}

{% endaspTab %}

**New Note:** You can also explore our [`Blazor 100% Stacked Bar Chart`](https://blazor.syncfusion.com/demos/chart/percent-stacked-bar?theme=bootstrap4) Example to knows how to render and configure the 100% stacking bar type chart.

## Stacking Group

You can use the [`StackingGroup`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~StackingGroup.html) property to group the stacked
bar and 100% stacked bar. Bars with same group name are stacked on top of each other.

{% aspTab template="chart/series/bar-charts/group", sourceFiles="group.razor" %}

{% endaspTab %}

![Stacking Group](../images/chart-types-images/groupbar.png)

## Customization

You can use the following properties to customize the 100% stacked bar series.

* [`Fill`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~Fill.html) – used to change the color of the 100% stacked bar.
* [`Opacity`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.Charts.ChartSeries.html#Syncfusion_Blazor_Charts_ChartSeries_Opacity) – used to control the transparency of the chart series.
* [``DashArray``](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ChartSeries~DashArray.html) – used to render 100% stacked bar series with dashes.
* [`Border`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor.Charts.ChartSeries.html#Syncfusion_Blazor_Charts_ChartSeries_Border) – used to render 100% stacked bar with border.

{% aspTab template="chart/series/bar-charts/custom-bar", sourceFiles="custom-bar.razor" %}

{% endaspTab %}

![Custom 100% Stacked Bar](../images/chart-types-images/custom-stacked-bar-100.png)

**New Note:** You can refer to our [`Blazor Charts`](https://www.syncfusion.com/blazor-components/blazor-charts) feature tour page for its groundbreaking feature representations. You can also explore our [`Blazor Chart example`](https://blazor.syncfusion.com/demos/chart/line?theme=bootstrap4) to knows various chart types and how to represent time-dependent data, showing trends in data at equal intervals.

## See Also

* [Data label](../data-labels)
* [Tooltip](../tool-tip)