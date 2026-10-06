# Installation — ATAS

**Package:** `MA-ICT-Killzones-Pivots-ATAS-v1.0.0.zip` (from [GitHub Releases](https://github.com/m4whw/MA-ICT-Killzones-Pivots/releases))
**Tested with:** ATAS 8.0.15.302 (.NET 10)

1. Close ATAS.
2. Unzip the package.
3. Copy `MAICTKillzonesPivots.dll` into `%APPDATA%\ATAS\Indicators`
   (paste that path into the Windows Explorer address bar to open the folder).
4. Start ATAS, open a chart, open **Indicators** and add **MA ICT Killzones & Pivots** (category **MA**).

No other files are required.

## Session Volume Profile data
- Uses ATAS cluster (volume-at-price) data. The chart must have cluster history for the loaded days.
- **Ticks per Row** sets the profile row size (default 1 tick).
- Sessions without sufficient data show *Insufficient Data* instead of levels.

## Notes
- Day / week / month changes follow the chart's ATAS session settings.
- Drawings appear on charts whose bar period is less than or equal to the **Timeframe Limit** setting (default 30 minutes).
- Alerts use the ATAS alert system; the sound is set in **Alert Sound File**.
