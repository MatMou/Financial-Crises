---
title: "16.3 Market-Based Systemic Risk Measures: CoVaR, SRISK, and MES"
subtitle: Measuring the contribution of individual institutions to systemic risk
---

While credit-based indicators measure the buildup of aggregate vulnerabilities, market-based systemic risk measures attempt to quantify the contribution of individual financial institutions to overall systemic risk. These measures, developed primarily after the GFC, use information from financial market prices (stock prices, CDS spreads, option prices) to estimate how much distress at a particular institution would contribute to distress in the financial system as a whole.

## CoVaR

**CoVaR** (Conditional Value at Risk), developed by Adrian and Brunnermeier (2016), measures the value at risk of the entire financial system conditional on a specific institution being in distress. The institution's contribution to systemic risk is defined as the difference between the CoVaR when the institution is in distress and the CoVaR when the institution is at its median state: this difference, called **Delta-CoVaR**, captures the marginal increase in system-wide risk attributable to the institution's distress.

CoVaR is estimated using quantile regressions that relate the returns of the financial system (proxied by an index of financial sector returns) to the returns of the individual institution. The estimation uses publicly available market data (stock returns, balance sheet variables, macroeconomic variables), which makes it relatively easy to compute and update in real time.

The strengths of CoVaR include its simplicity, its use of publicly available data, and its ability to capture the systemic importance of individual institutions (which depends not only on their size but also on their leverage, their interconnection with other institutions, and their exposure to common risk factors). Its limitations include its dependence on market prices (which may not accurately reflect underlying risk during calm periods, when markets tend to underestimate risk), and its backward-looking nature (the estimation uses historical data, which may not capture the risk of events that have not occurred in the sample).

## SRISK

**SRISK** (Systemic Risk), developed by Acharya, Engle, and Richardson (2012) and Brownlees and Engle (2017), measures the capital shortfall that a financial institution would experience in a systemic crisis. SRISK is defined as the expected capital shortfall of the institution conditional on a severe market decline (typically a 40% decline in global equity markets over six months).

The computation of SRISK requires three inputs: the institution's market capitalization (equity value), its total liabilities (from balance sheet data), and the institution's sensitivity to a systemic event (estimated from the correlation between the institution's stock returns and the market). SRISK is higher for institutions that are larger (more liabilities), more leveraged (lower equity relative to liabilities), and more correlated with the market (more sensitive to systemic events).

SRISK provides a dollar-denominated measure of systemic risk, which makes it interpretable and comparable across institutions: the SRISK of a $100 billion institution can be directly compared to the SRISK of a $10 billion institution, and the total SRISK of the financial system (the sum of individual institutions' SRISK values) provides a measure of the aggregate capital shortfall that would occur in a systemic crisis.

The V-Lab at NYU Stern publishes real-time SRISK estimates for major global financial institutions, providing a continuously updated measure of systemic risk. The SRISK estimates correctly identified many of the most systemically important institutions before the GFC (including Citigroup, AIG, and the major investment banks) and have been used by regulators as a complement to the Basel framework's SIFI designation.

## Marginal Expected Shortfall

**Marginal Expected Shortfall** (MES), developed by Acharya, Pedersen, Philippon, and Richardson (2017), measures the expected loss on an institution's equity when the market experiences a tail event (typically defined as the worst 5% of market days). MES captures the institution's exposure to systemic risk: institutions with high MES are those whose equity loses the most value when the financial system is under stress.

MES is related to SRISK (SRISK can be decomposed into components that include MES), but it focuses on the market-risk dimension of systemic importance rather than the capital-shortfall dimension. MES is useful for identifying institutions whose stock prices are most sensitive to system-wide stress, which provides information about the institutions that are most likely to become distressed during a crisis and that would therefore contribute most to contagion.

## The Absorption Ratio and network measures

Beyond the institution-level measures, researchers have developed measures of systemic risk that capture the structure and connectivity of the financial system as a whole. The **Absorption Ratio**, developed by Kritzman, Li, Page, and Rigobon (2011), measures the fraction of the total variance of a set of asset returns that is explained by a fixed number of principal components. A high absorption ratio indicates that asset returns are tightly coupled (moving together), which implies that a shock to any one asset is likely to spread rapidly through the system.

Network-based measures map the interconnections among financial institutions (through lending, derivatives, and payment relationships) and identify the institutions that are most central to the network (and whose failure would therefore have the largest systemic impact). These measures draw on the mathematics of graph theory and have been applied to interbank lending networks, CDS counterparty networks, and payment system flows.

## Assessment

The market-based systemic risk measures represent a significant advance over the pre-GFC toolkit, which relied primarily on institution-level balance sheet data and did not capture the system-wide dimension of risk. The measures are useful for identifying the institutions that are most systemically important, for monitoring how systemic risk evolves over time, and for stress-testing the financial system under hypothetical adverse scenarios.

Their limitations are equally important. Market-based measures are inherently backward-looking and tend to underestimate risk during calm periods (when the market data on which they are based reflect benign conditions). They are subject to the "paradox of volatility" identified by the BIS: systemic risk often builds up during periods of low measured volatility, precisely when the market-based measures indicate that risk is low. And they do not capture risks that are not reflected in market prices, such as operational risk, cyber risk, or the risks embedded in opaque off-balance-sheet structures.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
