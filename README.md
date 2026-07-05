# DayTradingBot with Live Signals

1️⃣ Order Flow Footprint Proxy: Because standardized trading models rely heavily on true institutional volume distribution I developed a model to effectively track buying versus selling pressure. It calculates a volume based delta level relative to the candle's absolute range and requires a 130% imbalance ratio to alert a signal.  

2️⃣ Delta Divergences: Now to prevent chasing false momentum pressure with the imbalance ratio, the bot cross references price action with delta divergence. A long signal is only printed if there is strong bullish divergence with the next candle printing a lower low despite the order flow imbalances present indicating seller exhaustion and a turn to the upside.

3️⃣ ICT Mapping: To add on support to the delta divergence indicators present an assessment of ICT concepts also further proves pivotal to the creation of this algorithm marking the highs of the candles before and after a respective candle checking for the presence of a Fair Value Gap, and a respective Inverse of this gap on both a higher 5 minute time frame and a lower 1 minute time frame.

4️⃣  Dynamic Risk Space: Stop losses are never static; they are algorithmically anchored to local pivot highs and lows to provide technical breathing room. Profit targets are mapped to unfilled Asia High and Low Targets with stop losses marked to major extremities in the chart.
