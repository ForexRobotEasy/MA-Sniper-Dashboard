# MA Sniper Dashboard

This code represents the MA Sniper Dashboard indicator for MetaTrader 4. It provides a visual representation of the moving average (MA) crossover signals on the chart.

## Indicator Settings

- `MA_Period` (default: 14) - The period used for calculating the moving average.

## Indicator Buffers

- `ExtMapBuffer1[]` - Buffer for bullish signals.
- `ExtMapBuffer2[]` - Buffer for bearish signals.

## Global Variables

- `hideDashboard` - Flag to hide or show the dashboard.

## Custom Indicator Functions

### OnInit()

This function is called when the indicator is initialized. It sets up the indicator buffers and short name.

### OnCalculate()

This function is called for each new tick. It calculates the moving average and determines the bullish or bearish signal based on the current close price relative to the MA. The signals are stored in the indicator buffers.

### IndicatorProperties()

This function is called to retrieve the properties of the indicator. It returns the value of `hideDashboard` as a string to indicate whether the dashboard is hidden or not.

### IndicatorInputs()

This function is called to retrieve the input parameters of the indicator. It sets the limits and tooltips for the `hideDashboard` input.

### IndicatorOutputs()

This function is called to retrieve the output parameters of the indicator. It sets the values and tooltips for the bullish and bearish signals.

### IndicatorChartEvent()

This function is called when a chart event occurs. It checks if the arrow button on the dashboard is clicked and toggles the `hideDashboard` flag accordingly. The indicator is then redrawn.

---

## Product Description

[MA Sniper Dashboard](https://forexroboteasy.com/forex-robot-review/ma-sniper-dashboard-review-ultimate-entry-system-at-199/) is an ultimate entry system indicator developed by Forex Robot Easy Team. This indicator provides a comprehensive view of the moving average crossover signals on the chart, helping traders make informed trading decisions.

Features:
- Easy to use and understand.
- Customizable moving average period.
- Bullish and bearish signals displayed on the chart.
- Dashboard can be hidden or shown with a click of a button.

Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5. For detailed reviews and trading results, visit the [official product page](https://forexroboteasy.com/forex-robot-review/ma-sniper-dashboard-review-ultimate-entry-system-at-199/).
