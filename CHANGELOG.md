# Changelog

All notable changes to MA ICT Killzones & Pivots are documented here.

## [1.0.0-mt5] — 2026-10-22

First MetaTrader 5 release (free).

### Added
- MetaTrader 5 version with the full feature set: killzones, session pivots and alerts, range levels, previous day / week / month levels, opening prices, timestamps, statistics table and the Session Volume Profile (per killzone plus Overnight and US Full).
- Broker server time detection from the weekly forex close, with conversion to New York time using US daylight-saving rules (verified 2000–2036 against Windows time zone data); manual override.
- Session Volume Profile sources for MetaTrader 5: real volume on exchange symbols, otherwise tick activity at price, with M1 tick volume as a fallback. The source is shown on the chart.
- Popup alerts and optional push notifications.
- Session pivots are off by default on MetaTrader 5 (enable them under 02. Pivots).

### Release status
- MetaTrader 5 package: released — [v1.0.0-mt5](https://github.com/m4whw/MA-ICT-Killzones-Pivots/releases/tag/v1.0.0-mt5).

## [1.0.0] — 2026-10-06

Initial release for NinjaTrader 8 and ATAS.

### Added
- Six configurable killzones with session boxes, session limit, New York (DST-aware) or fixed GMT timezone.
- Session high / low / midpoint pivots with labels, extension modes, hit-rate statistics and break alerts.
- Range-projection levels from average, median or standard-deviation session ranges.
- Previous day / week / month high, low and midline, D/W/M opens and dividers, hit rates and alerts; day-of-week labels.
- Opening-price lines, vertical timestamps, drawing cutoff time and timeframe limit.
- In-chart statistics table.
- Session Volume Profile per killzone plus Overnight (18:00–09:29 NY) and US Full (09:30–16:00 NY) sessions: POC, VAH, VAL, configurable Value Area %, histogram and level extension, built from real volume-at-price data only.
- ATAS: configurable ticks per row for the Session Volume Profile.

### Release status
- NinjaTrader 8 package: released — [v1.0.0-ninjatrader](https://github.com/m4whw/MA-ICT-Killzones-Pivots/releases/tag/v1.0.0-ninjatrader).
- ATAS package: released — [v1.0.0](https://github.com/m4whw/MA-ICT-Killzones-Pivots/releases/tag/v1.0.0).
