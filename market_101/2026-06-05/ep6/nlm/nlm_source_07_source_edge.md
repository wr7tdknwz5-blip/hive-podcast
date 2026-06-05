# Hive Source Edge Router Brief - Week of Market 101 | Ep 6 | What Is Diversification?

This document tells NotebookLM which source facts are safe to use as broad media evidence. It is not the full paid research packet and it should not be read as a ticker ranking.

## Router Health

- Router status: usable.
- Source count: 193.
- Routed fact count: 363.
- Source statuses: usable: 171; stale: 6; thin: 11; quarantined: 5.
- Quarantined source count: 5.

## Source Quality

Hive routed **150 publish-safe facts** from **66 usable source lanes** before this issue. The evidence grade is **EXCELLENT**.

| Evidence lane | What it adds | Quality |
| --- | --- | --- |
| CAT / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| AMD / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| TSM / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| AAPL / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| PLD / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| QCOM / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| UNH / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| GOOGL / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |

Hive uses this layer to keep the public story anchored to fresh, routed evidence rather than one-off headlines.

## How Hosts Should Use This

- Treat routed facts as evidence snippets, not trading instructions.
- Use them to explain confirmation, contradiction, crowding, fragility, and risk pressure.
- If a source is quarantined, do not cite it as proof.
- If maritime or supply-chain data is missing, say Hive is watching the lane but does not have current confirmation.
- Send listeners to the blog for the full source table, market board, and receipts.

## Media-Safe Evidence Hooks

- supply_chain: global_maritime_signal = normal (maritime; Maritime facts prevent media content from turning current shipping risk into unsupported hypotheticals.)
- supply_chain: lane_panama_canal = low_traffic (maritime; Lane sample: 0 vessels; 0 tankers.)
- supply_chain: lane_persian_gulf = baseline_building (maritime; Lane sample: 0 vessels; 0 tankers.)
- supply_chain: lane_singapore_strait = baseline_building (maritime; Lane sample: 0 vessels; 0 tankers.)
- supply_chain: lane_strait_of_malacca = normal (maritime; Lane sample: 67 vessels; 0 tankers.)
- supply_chain: lane_suez_canal = high_traffic (maritime; Lane sample: 21 vessels; 0 tankers.)
- energy: crude_inventory_latest = period: 2026-05-22; value: 441686.0; units: MBBL; series: WCESTUS1 (eia_crude; Crude inventory data links energy stress, inflation risk, sector rotation, and maritime pressure.)
- labor: average_hourly_earnings_private = series: CES0500000003; label: Average hourly earnings, private employees; period: April; year: 2026; value: 37.41 (bls_cpi; Wage pressure links labor strength to margin and inflation risk.)
- inflation: cpi_all_items = series: CUUR0000SA0; label: CPI-U all items; period: April; year: 2026; value: 333.02 (bls_cpi; Headline CPI keeps inflation-sensitive claims tied to the official BLS release.)
- inflation: cpi_core_less_food_energy = series: CUUR0000SA0L1E; label: CPI-U all items less food and energy; period: April; year: 2026; value: 335.803 (bls_cpi; Core CPI helps separate persistent inflation pressure from energy and food noise.)
- labor: job_openings = series: JTS000000000000000JOL; label: Job openings, total nonfarm; period: March; year: 2026; value: 6866.0 (bls_cpi; Job openings show labor demand cooling or tightening ahead of payroll revisions.)
- labor: nonfarm_payrolls = series: CES0000000001; label: Total nonfarm payrolls; period: April; year: 2026; value: 158736.0 (bls_cpi; Payroll levels ground labor momentum before it is translated into risk appetite.)
- labor: unemployment_rate = series: LNS14000000; label: Unemployment rate; period: April; year: 2026; value: 4.3 (bls_cpi; The unemployment rate anchors labor-market risk and recession framing.)
- inflation: latest_cpi = period: April; year: 2026; value: 333.02 (bls_cpi; Primary CPI data prevents Hive content from using stale or rounded inflation claims without context.)
- inflation: ppi_final_demand = series: WPUFD4; label: PPI final demand; period: April; year: 2026; value: 156.878 (bls_ppi; Final-demand PPI is an official upstream inflation pressure gauge.)
- inflation: ppi_final_demand_goods = series: WPUFD49104; label: PPI final demand goods; period: April; year: 2026; value: 154.301 (bls_ppi; Goods PPI helps catch margin and inventory pressure before it reaches CPI.)
- inflation: ppi_final_demand_services = series: WPUFD49207; label: PPI final demand services; period: April; year: 2026; value: 277.36 (bls_ppi; Services PPI helps identify sticky inflation pressure outside goods.)
- supply_chain: ppi_general_freight_trucking = series: PCU484121484121; label: PPI general freight trucking; period: April; year: 2026; value: 210.086 (bls_ppi; Freight PPI connects shipping stress to goods inflation and transport margins.)

## Social / Graphic Hooks

- supply_chain: global_maritime_signal from maritime.
- supply_chain: lane_panama_canal from maritime.
- supply_chain: lane_persian_gulf from maritime.
- supply_chain: lane_singapore_strait from maritime.
- supply_chain: lane_strait_of_malacca from maritime.
- supply_chain: lane_suez_canal from maritime.
- energy: crude_inventory_latest from eia_crude.
- credit: credit_spread_baa_10y from fred_macro.
- rates: fed_funds_effective from fred_macro.
- inflation: inflation_cpi_level from fred_macro.

## Sources Not Safe To Use As Proof

- go_live_gate: insufficient_history: need 20+ trading days (have 7).
- ta_signal: Insufficient history: 0 rows.
- ta_signal: Insufficient history: 0 rows.
- tradier_options_paper: tradier_credentials_missing.
- weekly_investment_committee: meta-llama/llama-3.3-70b-instruct:free: HTTP Error 429: Too Many Requests; qwen/qwen3-coder:free: HTTP Error 429: Too Many Requests; google/gemma-4-26b-a4b-it:free: HTTP Error 429: Too Many Requests; nvidia/nemotron-nano-9b-v2:free: HTTP Error 429: Too Many Requests.

## Router Notes For Hive

- Refresh stale routed sources before publishing source-specific claims: backtest_harness_latest.