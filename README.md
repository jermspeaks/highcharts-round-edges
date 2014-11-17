Highcharts Custom Plugin
========================
Rounded edges for bar charts
----------------------------

This plugin is adapted from [Torstein Honsi](https://github.com/highslide-software/rounded-corners), which allows you to specify which corners to round on a column chart, to customize corners for bar charts. Requires Highcharts.

### Issues (adapted from original plugin):
- Animation isn't working. To overcome that, create a method on the Renderer which points to a symbol definition, like it is currently done with "arc" in PieSeries.
- Dom exception on showing/hiding the series
