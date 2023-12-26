# XG Gold Robot MT4

**Developer's Site:** forexroboteasy.com

**Development:** Forex Robot Easy Team

---

## Weekly Gold Level Display

The XG Gold Robot MT4 is a custom indicator designed to display the minimum and maximum gold levels on a panel and chart. It provides a visual reference to aid in manual trading.

### Indicator Properties

- **Chart Window:** The indicator will be displayed on the chart window.
- **Buffers:** The indicator uses two buffers to store the minimum and maximum gold levels.
- **Color:** The minimum gold level will be displayed in blue, and the maximum gold level will be displayed in red.

### Initialization

The indicator's buffers are set in the `OnInit()` function. The `SetIndexBuffer()` function is used to assign the buffers to the indicator's plot lines. 

The indicator labels are created using the `ObjectCreate()` function. The labels are used to display the minimum and maximum gold levels on the chart.

### Calculation

The minimum and maximum gold levels are calculated in the `OnTick()` function. The `Low[]` and `High[]` arrays are used to retrieve the low and high prices for each bar. The `for` loop iterates through the bars to find the minimum and maximum values.

The calculated values are then assigned to the indicator buffers and updated on the chart using the `ObjectSetText()` function.

---

## Product Description

The XG Gold Robot MT4 is a powerful tool that provides traders with a visual reference for gold trading. By displaying the minimum and maximum gold levels on a panel and chart, it helps traders make informed trading decisions.

This custom indicator is designed to work in conjunction with manual trading strategies. It allows traders to easily identify key levels in the gold market, providing a valuable visual reference for entry and exit points.

The XG Gold Robot MT4 is versatile and can be used in various trading styles. Whether you are a short-term scalper or a long-term trend follower, this indicator can enhance your trading experience by providing you with important information about the gold market.

Please note that Forex Robot Easy is not the official developer of this product. We are showcasing this sample code as an example of how the indicator can work. To find the official developer and access more detailed reviews and trading results of this product, please visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/xg-gold-robot-mt4-unbiased-review-and-real-results/).

For more information about the XG Gold Robot MT4 and to explore its full potential, we recommend visiting the official developer's site or using MQL5, a platform for finding and purchasing trading tools and indicators.
