# Sleur-o-Buy

A Pine Script for TradingView to analyse Buy/Sell signals. Based on multiple indicators, 
the script shows possible buying opportunities and selling moments. This is a work in 
progress and should not be used as a financial advice. Always do your own research. 

![Example chart](https://github.com/iotricity/Sleur-o-Buy/blob/main/Sleur-o-Buy_sample.jpg)

## How to use the script?
Copy the source code, open the Pine Script Editor in TradingView and past the code in
the editor. Save the script as Sleur-o-Buy. Add the indicator by clicking on Indicators 
in the top toolbar. Select My Scripts and click Sleur-oBuy to add theindicator to
your chart.

## What is shown?
The script shows a collection of indicators so users with a Basic Subscription to
TradingView can still see multiple indicators. The script uses a fixed time frame of 
20 minutes per candle/bar. Time frames below 20 minutes will result in erratic 
behaviour. Best results are achieved by using 20 or 30 minute time frames.

1. Bollinger Bands
In white/gray the Bollinger Bands are shown, these are set for a 20 candles period. 
The upper and lower band, and the infill color will change to orange when the asset 
is oversold, and will turn to aqua when overbought.

2. EMA's
There are three EMA's visible, for short medium and long term, resp. red for 12, yellow 
for 72 and purple for 216 candles/bars.

3. Triple EMA
The green line is the Triple EMA for a period of 12 candles/bars.

4. Colored vertical background
When a possible buy or sell signal is calculated, the background of the bar will
change to green for buying or red for selling. Also a fainted graphic is shown at 
the bottom line of the graph area.

5. Pivot point indicators
Above and below the candles/bars there might be small triangles showing up. An
aqua colored triangle below the candle/bar indicates a possible pivot point from 
selling to buying, an orange triangle above the candle/bar indicates a possible 
pivot from buying to selling.

6. Special Buy/Sell indicator
When there are optimum circumstances to buy or sell, a green with a 'B' of red 
block with a 'S' are shown on the bottom line of the graph area.

7. Possible reversal signal
When a yellow dot or bar appears on the bottom area of the graph, there's a possible
reversal signal. This indicator is still in a very early stage of development.


Indicators may not appear on the last candle/bar since some of them depend on 
historical OHLC values, others need to look ahead from the point analysed. So there 
might be a delay of one to three candles/bars before showing the indicator. 
Therefor the indicator should be used for backtesting your own analysis.
