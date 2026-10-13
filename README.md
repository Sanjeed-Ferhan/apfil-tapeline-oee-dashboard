# APFIL Tapeline — Production Performance / OEE Loss Diagnostic

Single-file HTML dashboard for **APFIL — Tape Line**, covering **Unit-1 Tapeline** and **Unit-2 Tapeline**, shifts A–C.

## Features
- **Toggle:** Last day (12-Oct-2026) and Month-to-date (Oct 2026)
- OEE KPIs (Availability / Performance / Quality / Overall OEE) vs targets **A90 / P86 / Q97 / OEE75**
- Where time is going (Planned Production Time split Run vs unplanned NPT)
- OEE by unit (Unit-1, Unit-2 Tapeline) + Find-the-bottleneck (OEE factor constraint)
- Top downtime + downtime by category (min)
- **Opportunity Loss = NPT min ÷ cycle time (min/KG)** → lost output (KG)
- Production & OEE trend (last 16 days)
- Shift Action Board — downtime reasons with **responsible team** tagging
- Shift OEE and Gemba walk

## Data source
`Production Report` and `Tapeline Breakdown` tabs of the APFIL Tapeline sheet.

## Notes
- OEE = Availability × Performance × Quality.
- Availability = Actual Run Time ÷ Planned Production Time (planned downtime excluded).
- Data through 12-Oct-2026. The Tapeline Breakdown tab only recorded 12-Oct within October, so MTD breakdown is taken from the Production Report NPT categories.
