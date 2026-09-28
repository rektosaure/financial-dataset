# Data Catalog

This file is generated automatically from the public dataset definitions.

Machine-readable catalog: [`CATALOG.json`](CATALOG.json).

## Companies

| Dataset | Description | Coverage | Refresh | Format | Files |
| --- | --- | --- | --- | --- | --- |
| Company Fundamentals | Company profiles, identifiers, fundamentals, dividends, valuation and financial statistics, analyst estimates, and annual, quarterly and trailing financial statements. | Mixed | Weekly | JSON | `stockanalysis/{TICKER}.json` |
| Earnings-call Transcripts | Earnings-call transcripts with fiscal metadata and ordered transcript chunks. | Event history | — | JSON | `transcripts/{TICKER}.json` |

## Crypto

| Dataset | Description | Coverage | Refresh | Format | Files |
| --- | --- | --- | --- | --- | --- |
| Crypto Network Value Distributed | Distributed real-world asset value by blockchain network, excluding stablecoins. | Daily | Every 4 hours | CSV / JSON | [`macro-crypto/crypto_network_tvd.csv`](macro-crypto/crypto_network_tvd.csv)<br>[`macro-crypto/crypto_network_tvd.json`](macro-crypto/crypto_network_tvd.json) |
| Crypto Network Value Represented | Represented real-world asset value by blockchain network, excluding stablecoins. | Daily | Every 4 hours | CSV / JSON | [`macro-crypto/crypto_network_tvr.csv`](macro-crypto/crypto_network_tvr.csv)<br>[`macro-crypto/crypto_network_tvr.json`](macro-crypto/crypto_network_tvr.json) |

## Equities & Reference Data

| Dataset | Description | Coverage | Refresh | Format | Files |
| --- | --- | --- | --- | --- | --- |
| Company Classifications | Company classifications with ticker, industry, sector, SIC, country and grouping fields. | Snapshot | Weekly | CSV / JSON | [`screener/damodaran_stocks.csv`](screener/damodaran_stocks.csv)<br>[`screener/damodaran_stocks.json`](screener/damodaran_stocks.json) |
| GICS Taxonomy | Global Industry Classification Standard sector, industry-group, industry and sub-industry hierarchy. | Snapshot | Daily | CSV / JSON | [`screener/taxonomy_gics.csv`](screener/taxonomy_gics.csv)<br>[`screener/taxonomy_gics.json`](screener/taxonomy_gics.json) |
| Industry Ranking History | Historical changes in industry rankings. | Change history | — | CSV / JSON | [`screener/rankings_industries_history.csv`](screener/rankings_industries_history.csv)<br>[`screener/rankings_industries_history.json`](screener/rankings_industries_history.json) |
| Industry Rankings | Current industry rank bucket, percentile, position and universe size. | Snapshot | — | CSV / JSON | [`screener/rankings_industries.csv`](screener/rankings_industries.csv)<br>[`screener/rankings_industries.json`](screener/rankings_industries.json) |
| Industry Valuation Multiples | Industry valuation multiples including current, trailing and forward P/E measures and growth metrics. | Snapshot | Weekly | CSV / JSON | [`screener/damodaran_pe.csv`](screener/damodaran_pe.csv)<br>[`screener/damodaran_pe.json`](screener/damodaran_pe.json) |
| S&P 400 Constituents | S&P MidCap 400 constituents with sector, industry and headquarters information. | Snapshot | Daily | CSV / JSON | [`screener/sp400.csv`](screener/sp400.csv)<br>[`screener/sp400.json`](screener/sp400.json) |
| S&P 500 Constituents | S&P 500 constituents with sector, industry, headquarters, CIK and reference information. | Snapshot | Daily | CSV / JSON | [`screener/sp500.csv`](screener/sp500.csv)<br>[`screener/sp500.json`](screener/sp500.json) |
| S&P 600 Constituents | S&P SmallCap 600 constituents with sector, industry, headquarters and CIK information. | Snapshot | Daily | CSV / JSON | [`screener/sp600.csv`](screener/sp600.csv)<br>[`screener/sp600.json`](screener/sp600.json) |
| SEC Company Identifiers | SEC CIK, ticker and company-name reference data. | Snapshot | Daily | CSV / JSON | [`screener/sec_cik.csv`](screener/sec_cik.csv)<br>[`screener/sec_cik.json`](screener/sec_cik.json) |
| SIC Taxonomy | Standard Industrial Classification codes and industry names. | Snapshot | Daily | CSV / JSON | [`screener/taxonomy_sic.csv`](screener/taxonomy_sic.csv)<br>[`screener/taxonomy_sic.json`](screener/taxonomy_sic.json) |
| Ticker Ranking History | Historical changes in ticker rankings and style scores. | Change history | — | CSV / JSON | [`screener/rankings_tickers_history.csv`](screener/rankings_tickers_history.csv)<br>[`screener/rankings_tickers_history.json`](screener/rankings_tickers_history.json) |
| Ticker Rankings | Current ticker rankings and value, growth, momentum and VGM scores. | Snapshot | — | CSV / JSON | [`screener/rankings_tickers.csv`](screener/rankings_tickers.csv)<br>[`screener/rankings_tickers.json`](screener/rankings_tickers.json) |
| US Industry Metrics | U.S. equity-industry performance, earnings and financial-ratio metrics. | Snapshot | Weekly | CSV / JSON | [`screener/usa_industries.csv`](screener/usa_industries.csv)<br>[`screener/usa_industries.json`](screener/usa_industries.json) |
| US Sector Metrics | U.S. equity-sector performance, earnings and financial-ratio metrics. | Snapshot | Weekly | CSV / JSON | [`screener/usa_sectors.csv`](screener/usa_sectors.csv)<br>[`screener/usa_sectors.json`](screener/usa_sectors.json) |
| US Stock Universe | U.S. stock universe and company screening fields. | Snapshot | Weekly | CSV / JSON | [`screener/usa_stocks.csv`](screener/usa_stocks.csv)<br>[`screener/usa_stocks.json`](screener/usa_stocks.json) |

## Global Economy

| Dataset | Description | Coverage | Refresh | Format | Files |
| --- | --- | --- | --- | --- | --- |
| European Economic Sentiment | Economic sentiment indicators for the euro area, European Union and member countries. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/europe_esi.csv`](macro-world/europe_esi.csv)<br>[`macro-world/europe_esi.json`](macro-world/europe_esi.json) |
| Global Construction | Residential building-permit indicators across available OECD economies. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/world_construction.csv`](macro-world/world_construction.csv)<br>[`macro-world/world_construction.json`](macro-world/world_construction.json) |
| Global Consumer Confidence | Consumer-confidence indicators across available OECD economies. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/world_csi.csv`](macro-world/world_csi.csv)<br>[`macro-world/world_csi.json`](macro-world/world_csi.json) |
| Global Employment Rate | Employment-rate indicators across available OECD economies. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/world_esr.csv`](macro-world/world_esr.csv)<br>[`macro-world/world_esr.json`](macro-world/world_esr.json) |
| Global Manufacturing PMI | Manufacturing purchasing managers indexes across major economies. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/world_pmi.csv`](macro-world/world_pmi.csv)<br>[`macro-world/world_pmi.json`](macro-world/world_pmi.json) |
| Global Nominal GDP | Nominal GDP in U.S. dollars across available OECD economies and aggregates. | Quarterly | Every 12 hours | CSV / JSON | [`macro-world/world_gdp_nominal_usd.csv`](macro-world/world_gdp_nominal_usd.csv)<br>[`macro-world/world_gdp_nominal_usd.json`](macro-world/world_gdp_nominal_usd.json) |
| Global Real GDP | Real GDP in U.S. dollars across available OECD economies and aggregates. | Quarterly | Every 12 hours | CSV / JSON | [`macro-world/world_gdp_real_usd.csv`](macro-world/world_gdp_real_usd.csv)<br>[`macro-world/world_gdp_real_usd.json`](macro-world/world_gdp_real_usd.json) |
| Global Services PMI | Services purchasing managers indexes across major economies. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/world_nmi.csv`](macro-world/world_nmi.csv)<br>[`macro-world/world_nmi.json`](macro-world/world_nmi.json) |

## Markets

| Dataset | Description | Coverage | Refresh | Format | Files |
| --- | --- | --- | --- | --- | --- |
| CFTC Disaggregated Futures | CFTC disaggregated futures positioning by contract and trader category. | Weekly | Every 8 hours | CSV / JSON | [`macro-us/usa_cftc_disagg.csv`](macro-us/usa_cftc_disagg.csv)<br>[`macro-us/usa_cftc_disagg.json`](macro-us/usa_cftc_disagg.json) |
| CFTC Financial Futures | CFTC Traders in Financial Futures positioning by contract and trader category. | Weekly | Every 8 hours | CSV / JSON | [`macro-us/usa_cftc_tff.csv`](macro-us/usa_cftc_tff.csv)<br>[`macro-us/usa_cftc_tff.json`](macro-us/usa_cftc_tff.json) |
| Commodities | Energy, metals, agricultural commodities and livestock market prices. | Daily, Weekly, Monthly, Quarterly | Every 4 hours | CSV / JSON | [`macro-world/commodities_d.csv`](macro-world/commodities_d.csv)<br>[`macro-world/commodities_d.json`](macro-world/commodities_d.json)<br>[`macro-world/commodities_m.csv`](macro-world/commodities_m.csv)<br>[`macro-world/commodities_m.json`](macro-world/commodities_m.json)<br>[`macro-world/commodities_q.csv`](macro-world/commodities_q.csv)<br>[`macro-world/commodities_q.json`](macro-world/commodities_q.json)<br>[`macro-world/commodities_w.csv`](macro-world/commodities_w.csv)<br>[`macro-world/commodities_w.json`](macro-world/commodities_w.json) |
| Equity Indices | Major equity-market indices across the United States, Europe and Asia-Pacific. | Daily, Weekly, Monthly, Quarterly | Every 4 hours | CSV / JSON | [`macro-world/indices_d.csv`](macro-world/indices_d.csv)<br>[`macro-world/indices_d.json`](macro-world/indices_d.json)<br>[`macro-world/indices_m.csv`](macro-world/indices_m.csv)<br>[`macro-world/indices_m.json`](macro-world/indices_m.json)<br>[`macro-world/indices_q.csv`](macro-world/indices_q.csv)<br>[`macro-world/indices_q.json`](macro-world/indices_q.json)<br>[`macro-world/indices_w.csv`](macro-world/indices_w.csv)<br>[`macro-world/indices_w.json`](macro-world/indices_w.json) |
| Foreign Exchange | Major foreign-exchange rates including EUR/USD, GBP/USD, USD/JPY and other pairs. | Daily, Weekly, Monthly, Quarterly | Every 4 hours | CSV / JSON | [`macro-world/fx_d.csv`](macro-world/fx_d.csv)<br>[`macro-world/fx_d.json`](macro-world/fx_d.json)<br>[`macro-world/fx_m.csv`](macro-world/fx_m.csv)<br>[`macro-world/fx_m.json`](macro-world/fx_m.json)<br>[`macro-world/fx_q.csv`](macro-world/fx_q.csv)<br>[`macro-world/fx_q.json`](macro-world/fx_q.json)<br>[`macro-world/fx_w.csv`](macro-world/fx_w.csv)<br>[`macro-world/fx_w.json`](macro-world/fx_w.json) |
| US Market Volatility | S&P 500, VIX, VVIX, VIX futures and related volatility market series. | Daily, Weekly, Monthly, Quarterly | Every 4 hours | CSV / JSON | [`macro-us/usa_volatility_d.csv`](macro-us/usa_volatility_d.csv)<br>[`macro-us/usa_volatility_d.json`](macro-us/usa_volatility_d.json)<br>[`macro-us/usa_volatility_m.csv`](macro-us/usa_volatility_m.csv)<br>[`macro-us/usa_volatility_m.json`](macro-us/usa_volatility_m.json)<br>[`macro-us/usa_volatility_q.csv`](macro-us/usa_volatility_q.csv)<br>[`macro-us/usa_volatility_q.json`](macro-us/usa_volatility_q.json)<br>[`macro-us/usa_volatility_w.csv`](macro-us/usa_volatility_w.csv)<br>[`macro-us/usa_volatility_w.json`](macro-us/usa_volatility_w.json) |
| US Sector ETFs | Market price series for the major U.S. equity sector ETFs. | Daily, Weekly, Monthly, Quarterly | Every 4 hours | CSV / JSON | [`macro-us/usa_supersectors_d.csv`](macro-us/usa_supersectors_d.csv)<br>[`macro-us/usa_supersectors_d.json`](macro-us/usa_supersectors_d.json)<br>[`macro-us/usa_supersectors_m.csv`](macro-us/usa_supersectors_m.csv)<br>[`macro-us/usa_supersectors_m.json`](macro-us/usa_supersectors_m.json)<br>[`macro-us/usa_supersectors_q.csv`](macro-us/usa_supersectors_q.csv)<br>[`macro-us/usa_supersectors_q.json`](macro-us/usa_supersectors_q.json)<br>[`macro-us/usa_supersectors_w.csv`](macro-us/usa_supersectors_w.csv)<br>[`macro-us/usa_supersectors_w.json`](macro-us/usa_supersectors_w.json) |
| US Trade-Weighted Dollar | Broad, advanced-economy and emerging-market trade-weighted U.S. dollar indexes. | Daily | Every 4 hours | CSV / JSON | [`macro-us/usa_twi.csv`](macro-us/usa_twi.csv)<br>[`macro-us/usa_twi.json`](macro-us/usa_twi.json) |

## Rates & Credit

| Dataset | Description | Coverage | Refresh | Format | Files |
| --- | --- | --- | --- | --- | --- |
| Euro Area Rates and Yield Curve | ECB policy rates, €STR and euro-area yield-curve rates across 3M to 30Y maturities. | Daily | Every 4 hours | CSV / JSON | [`macro-world/europe_yield_curve.csv`](macro-world/europe_yield_curve.csv)<br>[`macro-world/europe_yield_curve.json`](macro-world/europe_yield_curve.json) |
| Federal Reserve | Federal funds rates, FOMC growth projections and Federal Reserve total assets. | Daily, Weekly, Annual | Every 4 hours, Every 8 hours, Every 12 hours | CSV / JSON | [`macro-us/usa_fed.csv`](macro-us/usa_fed.csv)<br>[`macro-us/usa_fed.json`](macro-us/usa_fed.json) |
| Global Long-Term Interest Rates | Long-term interest-rate indicators across available OECD economies. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/world_ir_lt.csv`](macro-world/world_ir_lt.csv)<br>[`macro-world/world_ir_lt.json`](macro-world/world_ir_lt.json) |
| Global Short-Term Interest Rates | Short-term interest-rate indicators across available OECD economies. | Monthly | Every 12 hours | CSV / JSON | [`macro-world/world_ir_st.csv`](macro-world/world_ir_st.csv)<br>[`macro-world/world_ir_st.json`](macro-world/world_ir_st.json) |
| US Bond ETFs | U.S. Treasury and corporate bond ETF market prices. | Daily, Weekly, Monthly, Quarterly | Every 4 hours | CSV / JSON | [`macro-us/usa_bonds_d.csv`](macro-us/usa_bonds_d.csv)<br>[`macro-us/usa_bonds_d.json`](macro-us/usa_bonds_d.json)<br>[`macro-us/usa_bonds_m.csv`](macro-us/usa_bonds_m.csv)<br>[`macro-us/usa_bonds_m.json`](macro-us/usa_bonds_m.json)<br>[`macro-us/usa_bonds_q.csv`](macro-us/usa_bonds_q.csv)<br>[`macro-us/usa_bonds_q.json`](macro-us/usa_bonds_q.json)<br>[`macro-us/usa_bonds_w.csv`](macro-us/usa_bonds_w.csv)<br>[`macro-us/usa_bonds_w.json`](macro-us/usa_bonds_w.json) |
| US Corporate Credit | U.S. corporate bond yields and option-adjusted spreads by credit quality. | Daily | Every 4 hours | CSV / JSON | [`macro-us/usa_corporate_bonds.csv`](macro-us/usa_corporate_bonds.csv)<br>[`macro-us/usa_corporate_bonds.json`](macro-us/usa_corporate_bonds.json) |
| US Money and Liquidity | Nominal and real M2, Federal Reserve total assets and overnight reverse repos. | Daily, Weekly, Monthly | Every 4 hours, Every 8 hours, Every 12 hours | CSV / JSON | [`macro-us/usa_money_supply.csv`](macro-us/usa_money_supply.csv)<br>[`macro-us/usa_money_supply.json`](macro-us/usa_money_supply.json) |
| US Treasury Yield Curve | U.S. Treasury yields across short- and long-term maturities. | Daily, Weekly | Every 4 hours | CSV / JSON | [`macro-us/usa_yield_curve_d.csv`](macro-us/usa_yield_curve_d.csv)<br>[`macro-us/usa_yield_curve_d.json`](macro-us/usa_yield_curve_d.json)<br>[`macro-us/usa_yield_curve_w.csv`](macro-us/usa_yield_curve_w.csv)<br>[`macro-us/usa_yield_curve_w.json`](macro-us/usa_yield_curve_w.json) |

## US Economy

| Dataset | Description | Coverage | Refresh | Format | Files |
| --- | --- | --- | --- | --- | --- |
| US Consumer Sentiment | University of Michigan sentiment, expectations, current conditions and inflation expectations. | Monthly | Every 12 hours | CSV / JSON | [`macro-us/usa_umcsi.csv`](macro-us/usa_umcsi.csv)<br>[`macro-us/usa_umcsi.json`](macro-us/usa_umcsi.json) |
| US Durable Goods | U.S. durable-goods orders including major manufacturing categories. | Monthly | Every 12 hours | CSV / JSON | [`macro-us/usa_durable_goods.csv`](macro-us/usa_durable_goods.csv)<br>[`macro-us/usa_durable_goods.json`](macro-us/usa_durable_goods.json) |
| US Household Debt | U.S. household debt-to-GDP, debt-service and mortgage-debt indicators. | Quarterly | Every 12 hours | CSV / JSON | [`macro-us/usa_household_debt.csv`](macro-us/usa_household_debt.csv)<br>[`macro-us/usa_household_debt.json`](macro-us/usa_household_debt.json) |
| US Housing Construction | U.S. building permits, housing starts and housing completions. | Monthly | Every 12 hours | CSV / JSON | [`macro-us/usa_construction.csv`](macro-us/usa_construction.csv)<br>[`macro-us/usa_construction.json`](macro-us/usa_construction.json) |
| US Industrial Production | U.S. industrial and manufacturing production, including major manufacturing industries. | Monthly | Every 12 hours | CSV / JSON | [`macro-us/usa_industrial_production.csv`](macro-us/usa_industrial_production.csv)<br>[`macro-us/usa_industrial_production.json`](macro-us/usa_industrial_production.json) |
| US Inflation | CPI, core CPI, PCE, core PCE, PPI and 5Y/10Y breakeven inflation. | Daily, Monthly | Every 4 hours, Every 12 hours | CSV / JSON | [`macro-us/usa_inflation.csv`](macro-us/usa_inflation.csv)<br>[`macro-us/usa_inflation.json`](macro-us/usa_inflation.json) |
| US ISM Manufacturing | ISM manufacturing PMI and components including orders, production, employment, inventories and prices. | Monthly | Every 12 hours | CSV / JSON | [`macro-us/usa_pmi.csv`](macro-us/usa_pmi.csv)<br>[`macro-us/usa_pmi.json`](macro-us/usa_pmi.json) |
| US ISM Manufacturing Reports | Monthly ISM manufacturing reports with structured report sections and text. | Monthly | Every 12 hours | JSON | [`macro-us/usa_pmi_reports.json`](macro-us/usa_pmi_reports.json) |
| US ISM Services | ISM services index and components including activity, employment, orders, inventories and prices. | Monthly | Every 12 hours | CSV / JSON | [`macro-us/usa_nmi.csv`](macro-us/usa_nmi.csv)<br>[`macro-us/usa_nmi.json`](macro-us/usa_nmi.json) |
| US ISM Services Reports | Monthly ISM services reports with structured report sections and text. | Monthly | Every 12 hours | JSON | [`macro-us/usa_nmi_reports.json`](macro-us/usa_nmi_reports.json) |
| US Labor Market | Jobless claims, unemployment rates, payrolls and employment by major sector. | Weekly, Monthly | Every 8 hours, Every 12 hours | CSV / JSON | [`macro-us/usa_labor_market.csv`](macro-us/usa_labor_market.csv)<br>[`macro-us/usa_labor_market.json`](macro-us/usa_labor_market.json) |
| US Small Business | NFIB small-business optimism and survey indicators for expectations, hiring, investment and credit. | Monthly | Every 12 hours | CSV / JSON | [`macro-us/usa_sbo.csv`](macro-us/usa_sbo.csv)<br>[`macro-us/usa_sbo.json`](macro-us/usa_sbo.json) |
