# sparkline
A prototype to make sparklines using SVG

This prototype will generate some random data points and then graph them as a sparkline.
Use the URL parameters to generate the points as follows:
 - `numPoints`: the number of data values
 - `maxValue': the largest possible data value (min value is always 0)

Given the two required URL parameters, a sparkline will be generated that normalizes the range of the values to the height of the svg area. The svg is currently a fixed size.
