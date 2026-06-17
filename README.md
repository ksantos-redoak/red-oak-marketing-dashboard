# Red Oak — Marketing Attribution Dashboard

Interactive GTM performance dashboard. Point-in-time snapshot of YTD 2026 new-business
pipeline, sourced from HubSpot (MQLs, sources, demos) and Salesforce via the Snowflake
mirror (pipeline, revenue, campaign influence).

**Live page:** https://ksantos-redoak.github.io/red-oak-marketing-dashboard/

## Notes
- New-business opportunities only; renewals excluded.
- Period tabs (YTD / Q1 / Q2 / monthly) recompute KPIs, metric tables, the demand trend,
  and revenue-by-source live.
- MQL-by-source and campaign-influence panels are YTD-only (badged in the UI) — see the
  in-page caveats for attribution-coverage limitations.
- Figures are a snapshot as of June 16, 2026 and do not auto-refresh; regenerate to update.
