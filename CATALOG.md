# Data Catalog

This file is generated automatically from the public dataset definitions.

## Crypto

| Dataset | Description | Granularity | Format | Files |
| --- | --- | --- | --- | --- |
| Crypto Network Value Distributed | Distributed real-world asset value by blockchain network, excluding stablecoins. | Daily | CSV | [`macro-crypto/crypto_network_tvd.csv`](macro-crypto/crypto_network_tvd.csv) |
| Crypto Network Value Represented | Represented real-world asset value by blockchain network, excluding stablecoins. | Daily | CSV | [`macro-crypto/crypto_network_tvr.csv`](macro-crypto/crypto_network_tvr.csv) |

## Equities & Reference Data

| Dataset | Description | Granularity | Format | Files |
| --- | --- | --- | --- | --- |
| Company Classifications | Company classifications with ticker, industry, sector, SIC, country and grouping fields. | Snapshot | CSV | [`screener/damodaran_stocks.csv`](screener/damodaran_stocks.csv) |
| GICS Taxonomy | Global Industry Classification Standard sector, industry-group, industry and sub-industry hierarchy. | Snapshot | CSV | [`screener/taxonomy_gics.csv`](screener/taxonomy_gics.csv) |
| Industry Valuation Multiples | Industry valuation multiples including current, trailing and forward P/E measures and growth metrics. | Snapshot | CSV | [`screener/damodaran_pe.csv`](screener/damodaran_pe.csv) |
| S&P 400 Constituents | S&P MidCap 400 constituents with sector, industry and headquarters information. | Snapshot | CSV | [`screener/sp400.csv`](screener/sp400.csv) |
| S&P 500 Constituents | S&P 500 constituents with sector, industry, headquarters, CIK and reference information. | Snapshot | CSV | [`screener/sp500.csv`](screener/sp500.csv) |
| S&P 600 Constituents | S&P SmallCap 600 constituents with sector, industry, headquarters and CIK information. | Snapshot | CSV | [`screener/sp600.csv`](screener/sp600.csv) |
| SEC Company Identifiers | SEC CIK, ticker and company-name reference data. | Snapshot | CSV | [`screener/sec_cik.csv`](screener/sec_cik.csv) |
| SIC Taxonomy | Standard Industrial Classification codes and industry names. | Snapshot | CSV | [`screener/taxonomy_sic.csv`](screener/taxonomy_sic.csv) |
| US Industry Metrics | U.S. equity-industry performance, earnings and financial-ratio metrics. | Snapshot | CSV | [`screener/usa_industries.csv`](screener/usa_industries.csv) |
| US Sector Metrics | U.S. equity-sector performance, earnings and financial-ratio metrics. | Snapshot | CSV | [`screener/usa_sectors.csv`](screener/usa_sectors.csv) |
| US Stock Universe | U.S. stock universe and company screening fields. | Snapshot | CSV | [`screener/usa_stocks.csv`](screener/usa_stocks.csv) |

## Global Economy

| Dataset | Description | Granularity | Format | Files |
| --- | --- | --- | --- | --- |
| European Economic Sentiment | Economic sentiment indicators for the euro area, European Union and member countries. | Monthly | CSV | [`macro-world/europe_esi.csv`](macro-world/europe_esi.csv) |
| Global Construction | Residential building-permit indicators across available OECD economies. | Monthly | CSV | [`macro-world/world_construction.csv`](macro-world/world_construction.csv) |
| Global Consumer Confidence | Consumer-confidence indicators across available OECD economies. | Monthly | CSV | [`macro-world/world_csi.csv`](macro-world/world_csi.csv) |
| Global Employment Rate | Employment-rate indicators across available OECD economies. | Monthly | CSV | [`macro-world/world_esr.csv`](macro-world/world_esr.csv) |
| Global Manufacturing PMI | Manufacturing purchasing managers indexes across major economies. | Monthly | CSV | [`macro-world/world_pmi.csv`](macro-world/world_pmi.csv) |
| Global Nominal GDP | Nominal GDP in U.S. dollars across available OECD economies and aggregates. | Quarterly | CSV | [`macro-world/world_gdp_nominal_usd.csv`](macro-world/world_gdp_nominal_usd.csv) |
| Global Real GDP | Real GDP in U.S. dollars across available OECD economies and aggregates. | Quarterly | CSV | [`macro-world/world_gdp_real_usd.csv`](macro-world/world_gdp_real_usd.csv) |
| Global Services PMI | Services purchasing managers indexes across major economies. | Monthly | CSV | [`macro-world/world_nmi.csv`](macro-world/world_nmi.csv) |

## Markets

| Dataset | Description | Granularity | Format | Files |
| --- | --- | --- | --- | --- |
| CFTC Disaggregated Futures | CFTC disaggregated futures positioning by contract and trader category. | Weekly | CSV | [`macro-us/usa_cftc_disagg.csv`](macro-us/usa_cftc_disagg.csv) |
| CFTC Financial Futures | CFTC Traders in Financial Futures positioning by contract and trader category. | Weekly | CSV | [`macro-us/usa_cftc_tff.csv`](macro-us/usa_cftc_tff.csv) |
| Commodities | Energy, metals, agricultural commodities and livestock market prices. | Daily, Weekly, Monthly, Quarterly | CSV | [`macro-world/commodities_d.csv`](macro-world/commodities_d.csv)<br>[`macro-world/commodities_m.csv`](macro-world/commodities_m.csv)<br>[`macro-world/commodities_q.csv`](macro-world/commodities_q.csv)<br>[`macro-world/commodities_w.csv`](macro-world/commodities_w.csv) |
| Equity Indices | Major equity-market indices across the United States, Europe and Asia-Pacific. | Daily, Weekly, Monthly, Quarterly | CSV | [`macro-world/indices_d.csv`](macro-world/indices_d.csv)<br>[`macro-world/indices_m.csv`](macro-world/indices_m.csv)<br>[`macro-world/indices_q.csv`](macro-world/indices_q.csv)<br>[`macro-world/indices_w.csv`](macro-world/indices_w.csv) |
| Foreign Exchange | Major foreign-exchange rates including EUR/USD, GBP/USD, USD/JPY and other pairs. | Daily, Weekly, Monthly, Quarterly | CSV | [`macro-world/fx_d.csv`](macro-world/fx_d.csv)<br>[`macro-world/fx_m.csv`](macro-world/fx_m.csv)<br>[`macro-world/fx_q.csv`](macro-world/fx_q.csv)<br>[`macro-world/fx_w.csv`](macro-world/fx_w.csv) |
| US Market Volatility | S&P 500, VIX, VVIX, VIX futures and related volatility market series. | Daily, Weekly, Monthly, Quarterly | CSV | [`macro-us/usa_volatility_d.csv`](macro-us/usa_volatility_d.csv)<br>[`macro-us/usa_volatility_m.csv`](macro-us/usa_volatility_m.csv)<br>[`macro-us/usa_volatility_q.csv`](macro-us/usa_volatility_q.csv)<br>[`macro-us/usa_volatility_w.csv`](macro-us/usa_volatility_w.csv) |
| US Sector ETFs | Market price series for the major U.S. equity sector ETFs. | Daily, Weekly, Monthly, Quarterly | CSV | [`macro-us/usa_supersectors_d.csv`](macro-us/usa_supersectors_d.csv)<br>[`macro-us/usa_supersectors_m.csv`](macro-us/usa_supersectors_m.csv)<br>[`macro-us/usa_supersectors_q.csv`](macro-us/usa_supersectors_q.csv)<br>[`macro-us/usa_supersectors_w.csv`](macro-us/usa_supersectors_w.csv) |
| US Trade-Weighted Dollar | Broad, advanced-economy and emerging-market trade-weighted U.S. dollar indexes. | Daily | CSV | [`macro-us/usa_twi.csv`](macro-us/usa_twi.csv) |

## Rates & Credit

| Dataset | Description | Granularity | Format | Files |
| --- | --- | --- | --- | --- |
| Euro Area Rates and Yield Curve | ECB policy rates, €STR and euro-area yield-curve rates across 3M to 30Y maturities. | Daily | CSV | [`macro-world/europe_yield_curve.csv`](macro-world/europe_yield_curve.csv) |
| Federal Reserve | Federal funds rates, FOMC growth projections and Federal Reserve total assets. | Daily, Weekly, Annual | CSV | [`macro-us/usa_fed.csv`](macro-us/usa_fed.csv) |
| Global Long-Term Interest Rates | Long-term interest-rate indicators across available OECD economies. | Monthly | CSV | [`macro-world/world_ir_lt.csv`](macro-world/world_ir_lt.csv) |
| Global Short-Term Interest Rates | Short-term interest-rate indicators across available OECD economies. | Monthly | CSV | [`macro-world/world_ir_st.csv`](macro-world/world_ir_st.csv) |
| US Bond ETFs | U.S. Treasury and corporate bond ETF market prices. | Daily, Weekly, Monthly, Quarterly | CSV | [`macro-us/usa_bonds_d.csv`](macro-us/usa_bonds_d.csv)<br>[`macro-us/usa_bonds_m.csv`](macro-us/usa_bonds_m.csv)<br>[`macro-us/usa_bonds_q.csv`](macro-us/usa_bonds_q.csv)<br>[`macro-us/usa_bonds_w.csv`](macro-us/usa_bonds_w.csv) |
| US Corporate Credit | U.S. corporate bond yields and option-adjusted spreads by credit quality. | Daily | CSV | [`macro-us/usa_corporate_bonds.csv`](macro-us/usa_corporate_bonds.csv) |
| US Money and Liquidity | Nominal and real M2, Federal Reserve total assets and overnight reverse repos. | Daily, Weekly, Monthly | CSV | [`macro-us/usa_money_supply.csv`](macro-us/usa_money_supply.csv) |
| US Treasury Yield Curve | U.S. Treasury yields across short- and long-term maturities. | Daily, Weekly | CSV | [`macro-us/usa_yield_curve_d.csv`](macro-us/usa_yield_curve_d.csv)<br>[`macro-us/usa_yield_curve_w.csv`](macro-us/usa_yield_curve_w.csv) |

## US Economy

| Dataset | Description | Granularity | Format | Files |
| --- | --- | --- | --- | --- |
| US Consumer Sentiment | University of Michigan sentiment, expectations, current conditions and inflation expectations. | Monthly | CSV | [`macro-us/usa_umcsi.csv`](macro-us/usa_umcsi.csv) |
| US Durable Goods | U.S. durable-goods orders including major manufacturing categories. | Monthly | CSV | [`macro-us/usa_durable_goods.csv`](macro-us/usa_durable_goods.csv) |
| US Household Debt | U.S. household debt-to-GDP, debt-service and mortgage-debt indicators. | Quarterly | CSV | [`macro-us/usa_household_debt.csv`](macro-us/usa_household_debt.csv) |
| US Housing Construction | U.S. building permits, housing starts and housing completions. | Monthly | CSV | [`macro-us/usa_construction.csv`](macro-us/usa_construction.csv) |
| US Industrial Production | U.S. industrial and manufacturing production, including major manufacturing industries. | Monthly | CSV | [`macro-us/usa_industrial_production.csv`](macro-us/usa_industrial_production.csv) |
| US Inflation | CPI, core CPI, PCE, core PCE, PPI and 5Y/10Y breakeven inflation. | Daily, Monthly | CSV | [`macro-us/usa_inflation.csv`](macro-us/usa_inflation.csv) |
| US ISM Manufacturing | ISM manufacturing PMI and components including orders, production, employment, inventories and prices. | Monthly | CSV | [`macro-us/usa_pmi.csv`](macro-us/usa_pmi.csv) |
| US ISM Manufacturing Reports | Monthly ISM manufacturing reports with structured report sections and text. | Monthly | JSON | [`macro-us/usa_pmi_reports.json`](macro-us/usa_pmi_reports.json) |
| US ISM Services | ISM services index and components including activity, employment, orders, inventories and prices. | Monthly | CSV | [`macro-us/usa_nmi.csv`](macro-us/usa_nmi.csv) |
| US ISM Services Reports | Monthly ISM services reports with structured report sections and text. | Monthly | JSON | [`macro-us/usa_nmi_reports.json`](macro-us/usa_nmi_reports.json) |
| US Labor Market | Jobless claims, unemployment rates, payrolls and employment by major sector. | Weekly, Monthly | CSV | [`macro-us/usa_labor_market.csv`](macro-us/usa_labor_market.csv) |
| US Small Business | NFIB small-business optimism and survey indicators for expectations, hiring, investment and credit. | Monthly | CSV | [`macro-us/usa_sbo.csv`](macro-us/usa_sbo.csv) |
