<!-- markdownlint-disable MD036 -->

# Hide axis line when clicking the legend

By using the `OnLegendClick` event, you can hide the axis line through legend.

To hide the axis line through legend click, follow the given steps:

**Step 1**:

Create a chart with multiple axes.

By using the `OnLegendClick`event, you can get the Series Name. Using this event, based on which you can hide the axis line when clicking the legend.

```razor
<ChartEvents OnLegendClick="LegendClick"></ChartEvents>
 void LegendClick(LegendClickEventArgs args)
    {
        if (args.Series.Name == "England")
        {
            this.AxisVisible1 = this.SeriesVisible1 = !this.SeriesVisible1;
        }
        else if(args.Series.Name == "US")
        {
            this.AxisVisible2 = this.SeriesVisible2 = !this.SeriesVisible2;
        }
        else if(args.Series.Name == "West Indies")
        {
            this.AxisVisible3 = this.SeriesVisible3 = !this.SeriesVisible3;
        }
    }

  ```

{% aspTab template="chart/how-to/axis-hide", sourceFiles="axis-hide.razor" %}

{% endaspTab %}

**New Note:** You can refer to our [`Blazor Charts`](https://www.syncfusion.com/blazor-components/blazor-charts) feature tour page for its groundbreaking feature representations. You can also explore our [`Blazor Chart example`](https://blazor.syncfusion.com/demos/chart/line?theme=bootstrap4) to knows various chart types and how to represent time-dependent data, showing trends in data at equal intervals.