# Hive Source Edge Router Brief - Week of Midweek Fresh Brief 2026-06-03

This document tells NotebookLM which source facts are safe to use as broad media evidence. It is not the full paid research packet and it should not be read as a ticker ranking.

## Router Health

- Router status: usable.
- Source count: 186.
- Routed fact count: 361.
- Source statuses: usable: 143; thin: 9; stale: 33; quarantined: 1.
- Quarantined source count: 1.

## Source Quality

Hive routed **112 publish-safe facts** from **37 usable source lanes** before this issue. The evidence grade is **BLOCKED**.

| Evidence lane | What it adds | Quality |
| --- | --- | --- |
| NVDA / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| AAPL / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| GOOGL / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| TSLA / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| AMZN / ta_signal | technical composite: Core daily signal strength for market board rank, stock reports, and confirmation chains. | usable |
| labor / bls_cpi | average hourly earnings private: Wage pressure links labor strength to margin and inflation risk. | usable |
| inflation / bls_cpi | cpi all items: Headline CPI keeps inflation-sensitive claims tied to the official BLS release. | usable |
| inflation / bls_cpi | cpi core less food energy: Core CPI helps separate persistent inflation pressure from energy and food noise. | usable |

Hive uses this layer to keep the public story anchored to fresh, routed evidence rather than one-off headlines.

## How Hosts Should Use This

- Treat routed facts as evidence snippets, not trading instructions.
- Use them to explain confirmation, contradiction, crowding, fragility, and risk pressure.
- If a source is quarantined, do not cite it as proof.
- If maritime or supply-chain data is missing, say Hive is watching the lane but does not have current confirmation.
- Send listeners to the blog for the full source table, market board, and receipts.

## Media-Safe Evidence Hooks

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
- inflation: latest_ppi = period: April; year: 2026; value: 154.301 (bls_ppi; PPI can lead consumer inflation pressure and margin pressure before it shows up in CPI.)
- credit: credit_spread_baa_10y = date: 2026-05-26; value: 1.56; series: BAA10Y (fred_macro; FRED macro levels frame inflation, liquidity, credit, and rate pressure across every signal.)
- rates: fed_funds_effective = date: 2026-04-01; value: 3.64; series: FEDFUNDS (fred_macro; FRED macro levels frame inflation, liquidity, credit, and rate pressure across every signal.)
- inflation: inflation_cpi_level = date: 2026-04-01; value: 332.407; series: CPIAUCSL (fred_macro; FRED macro levels frame inflation, liquidity, credit, and rate pressure across every signal.)
- liquidity: money_supply_m2 = date: 2026-04-01; value: 22804.5; series: M2SL (fred_macro; FRED macro levels frame inflation, liquidity, credit, and rate pressure across every signal.)
- growth: real_gdp_level = date: 2026-01-01; value: 24152.656; series: GDPC1 (fred_macro; FRED macro levels frame inflation, liquidity, credit, and rate pressure across every signal.)

## Social / Graphic Hooks

- energy: crude_inventory_latest from eia_crude.
- credit: credit_spread_baa_10y from fred_macro.
- rates: fed_funds_effective from fred_macro.
- inflation: inflation_cpi_level from fred_macro.
- liquidity: money_supply_m2 from fred_macro.
- growth: real_gdp_level from fred_macro.
- valuation: market_cape from shiller_cape.
- macro: signal from shiller_cape.
- macro: macro_weather_signal from noaa_weather.
- macro: signal from tradegov_signals.

## Sources Not Safe To Use As Proof

- tradier_options_paper: tradier_credentials_missing.

## Router Notes For Hive

- Refresh stale routed sources before publishing source-specific claims: maritime, ta_signal, ta_signal, ta_signal, ta_signal.