# JCSPatterns_MT4_Bot
Experimental and simple robot for Metatrader 4

This is intended to be used as a base for the development of a Metatrader 4 bot (even if it works as is).

This is a Metatrader 4 experimental bot that I coded while freestyling around detection of Bullish Engulfing Patterns (in french : Avalements Haussiers).

This robot only detects bulling engulfing patterns.

It trades without Stop Loss so use it at your own risk if you test it on a real account (You should not, IMHO).

I suggest that you do a lot of backtests before trying it on a real account (You should not, IMHA). I also suggest that you use small lots.

You will have to change the Take Profit levels in the OrderSend() functions to set it properly for a specific instrument.

The default Take Profit levels are for GBPJPY in H1 timeframe.

This bot logs into a text file in the following folder :
C:\Users\[USERNAME]\AppData\Roaming\MetaQuotes\Terminal\Common\Files

https://tradingbot.wixsite.com/robots-de-trading

https://ichimoku-expert.blogspot.com

https://ntic974.blogspot.com

