# Installation — MetaTrader 5

**Requirements:** MetaTrader 5 for Windows, any broker. Drawings appear on charts up to 30 minutes (configurable).

1. Download [`MA-ICT-Killzones-Pivots-MT5-v1.0.0.zip`](https://github.com/m4whw/MA-ICT-Killzones-Pivots/releases/download/v1.0.0-mt5/MA-ICT-Killzones-Pivots-MT5-v1.0.0.zip) and unzip it.
2. In MetaTrader 5 open **File → Open Data Folder**, then **MQL5 → Indicators**, and copy `MAICTKillzonesPivots.ex5` there (a sub-folder such as `MA` is fine).
3. In the **Navigator** right-click **Indicators → Refresh**.
4. Drag **MAICTKillzonesPivots** onto a chart, for example XAUUSD or EURUSD on M5 or M15.

## Settings worth knowing

- **07. Global → Broker Server Time:** *Auto* detects the broker clock from the weekly forex close. If sessions look shifted, choose *New York + 7h*, *GMT+2/+3 with EU DST* or *Fixed GMT offset*.
- **08. Session Volume Profile:** enable the profile per killzone, plus Overnight (18:00–09:30 NY) and US Full (09:30–16:00 NY). The note at the bottom of the chart shows the data source in use.
- **02. Pivots:** session pivots are off by default; turn on *Show Pivots* to draw session highs and lows and to receive break alerts.
- **09. Alerts:** popup alerts with sound, and optional push notifications (set your MetaQuotes ID in **Tools → Options → Notifications**).
- **Charts → Auto Scroll:** turn it off to browse history; when it is on, MetaTrader returns the chart to the last bar.

## Volume data

Most MetaTrader 5 brokers provide tick volume only. The profile then counts price changes (ticks) at each price — an approximation of where activity happened, not traded contracts. If the tick history does not cover a session, M1 bar tick volume is used instead. Exchange symbols with real volume are used automatically.

## Remove

Press **Ctrl+I** on the chart, select the indicator and click **Delete**.

Product page: [English](https://mohamed-abdelaziz.com/en/learning/tools/ma-ict-killzones-pivots) · [العربية](https://mohamed-abdelaziz.com/ar/learning/tools/ma-ict-killzones-pivots)
