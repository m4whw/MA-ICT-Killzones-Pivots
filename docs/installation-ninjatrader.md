# Installation — NinjaTrader 8

**Package:** `MA-ICT-Killzones-Pivots-NinjaTrader-v1.0.0.zip` (from [GitHub Releases](https://github.com/m4whw/MA-ICT-Killzones-Pivots/releases))
**Tested with:** NinjaTrader 8.1.8.3

The package is a NinjaTrader add-on archive containing a compiled assembly. Do not unzip it.

1. In NinjaTrader 8 open **Tools → Import → NinjaScript Add-On…**
2. Select `MA-ICT-Killzones-Pivots-NinjaTrader-v1.0.0.zip` and confirm the import.
3. Restart NinjaTrader if prompted.
4. Open a chart, right-click → **Indicators…**, add **MA ICT Killzones & Pivots** and configure it.

## Session Volume Profile data
- **Tick data (default):** requires historical tick data from your data provider for the loaded days. Tick Replay is not required.
- **Volumetric:** use a Volumetric chart (NinjaTrader Order Flow+).
- Sessions without sufficient data show *Insufficient Data* instead of levels.

## Recommended chart setup
- Use an ETH trading-hours template (for example *CME US Index Futures ETH*) so that day / week / month levels follow the full futures trading day.
- Drawings appear on charts whose bar period is less than or equal to the **Timeframe Limit** setting (default 30 minutes).
