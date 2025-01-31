# Error Bar Chart

## Error Bar

Error bars are graphical representations of the variability of data and used on graphs to indicate the error or uncertainty in a reported
measurement. To render the error bar for the series, set [`Visible`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ErrorBarSettingsModel~Visible.html)
as `True` in error bar object.

{% aspTab template="chart/series/other-types/errorbar", sourceFiles="errorbar.razor" %}

{% endaspTab %}

![Error Bar](../images/othertypes/errorbar.png)

## Error Bar Type

To change the error bar rendering type using [`Type`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ErrorBarSettingsModel~Type.html)
option of error bar. To change the error bar line length you can use [`VerticalError`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ErrorBarSettingsModel~VerticalError.html)
property.

{% aspTab template="chart/series/other-types/error-type", sourceFiles="error-type.razor" %}

{% endaspTab %}

## Customizing Error Bar Type

To customize the error bar type, set error bar [`Type`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ErrorBarSettingsModel~Type.htmll) as `Custom` and
then change the horizontal/vertical positive and negative error of error bar.

{% aspTab template="chart/series/other-types/custom-error", sourceFiles="custom-error.razor" %}

{% endaspTab %}

![Customizing Error Bar](../images/chart-types-images/custom-error-bar.png)

## Error Bar Mode

Error bar mode is used to define whether the error bar line has to be drawn horizontally, vertically or in both side.
To change the error bar mode use [`Mode`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ErrorBarSettingsModel~Mode.html) option.

{% aspTab template="chart/series/other-types/error-mode", sourceFiles="error-mode.razor" %}

{% endaspTab %}

## Error Bar Direction

To change the error bar direction to plus, minus or both side using [`Direction`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ErrorBarSettingsModel~Direction.html) option.

{% aspTab template="chart/series/other-types/error-direction", sourceFiles="error-direction.razor" %}

{% endaspTab %}

## Customizing Error Bar Cap

To customize the error bar cap length, width and fill color, you can use [`ErrorBarCap`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Charts.ErrorBarSettingsModel~ErrorBarCap.html) option.

{% aspTab template="chart/series/other-types/error-cap", sourceFiles="error-cap.razor" %}

{% endaspTab %}

![Customizing Error Bar](../images/othertypes/errorbarcap-custom.png)

**New Note:** You can refer to our [`Blazor Charts`](https://www.syncfusion.com/blazor-components/blazor-charts) feature tour page for its groundbreaking feature representations. You can also explore our [`Blazor Chart example`](https://blazor.syncfusion.com/demos/chart/line?theme=bootstrap4) to knows various chart types and how to represent time-dependent data, showing trends in data at equal intervals.

## See Also

* [Data label](../data-labels)
* [Tooltip](../tool-tip)