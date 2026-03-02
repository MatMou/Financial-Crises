---
title: "1.4 A Taxonomy: The Reinhart-Rogoff Framework and the Laeven-Valencia Database"
subtitle: The two most important crisis databases
---

The study of financial crises is, at its core, an empirical enterprise. Theoretical models can describe the mechanisms that produce crises, but testing those models, measuring the costs of crises, and identifying recurring patterns requires data. And not just data on individual episodes, but data that is **comparable across countries and time periods**, so that we can distinguish what is specific to a particular crisis from what is general to crises as a class.

Two databases have become the standard references in the crisis literature. The first is the Reinhart-Rogoff dataset, which covers 66 countries over up to eight centuries and provides the broadest historical perspective available. The second is the Laeven-Valencia Systemic Banking Crises Database, maintained at the IMF, which covers the period since 1970 with more systematic identification criteria and detailed information on policy responses and costs. This subsection presents each database in detail, discusses the methodological choices that shape their content, and considers their strengths and limitations.

## The Reinhart-Rogoff dataset

### Scope and coverage

The dataset assembled by {cite:t}`Reinhart2009` in *This Time Is Different* is the most ambitious attempt to catalogue financial crises across time and space. It covers 66 countries in Africa, Asia, Europe, Latin America, North America, and Oceania, with time series extending as far back as the 1300s for some variables and some countries (England's sovereign defaults, for instance, go back to Edward III's default in 1340). For most countries, systematic coverage begins around 1800.

The dataset tracks six types of crisis events:

**External sovereign defaults.** Failure to meet payment obligations on debt incurred under foreign legal jurisdiction, including outright default, repudiation, and restructurings on terms less favorable to creditors than the original contract. Coverage for some countries extends back several centuries.

**Domestic sovereign defaults.** Failure to meet payment obligations on debt incurred under domestic legal jurisdiction. This category also includes the forced conversion of foreign-currency deposits into local currency at below-market rates, and the freezing of bank deposits. Domestic defaults have been studied much less than external defaults, and Reinhart and Rogoff's inclusion of domestic debt in their analysis was one of the major contributions of their work.

**Banking crises.** Episodes of widespread bank failures, bank runs, or large-scale government assistance to the banking sector. Given the paucity of quantitative data for earlier historical periods, the identification of banking crises relies heavily on qualitative judgment and narrative evidence from country-specific historical studies.

**Currency crashes.** Annual depreciations of at least 15% against the relevant anchor currency (or, in metallic eras, debasements of at least 5% of the metallic content of the currency).

**Inflation crises.** Years in which the annual inflation rate exceeds 20%. This is a deliberately low threshold by modern standards (Cagan's classic definition of hyperinflation uses a monthly rate of 50%, which corresponds to an annual rate of roughly 13,000%), but it is calibrated to capture significant inflationary episodes in the earlier metallic eras as well as in the modern fiat money era.

**Stock market crashes.** Large, rapid declines in equity prices. These are tracked alongside the other crisis types but receive less systematic attention in the main analysis.

In addition to the crisis dates themselves, the dataset includes long-run time series on a range of macrofinancial variables: public debt (both external and domestic), trade, GNP, inflation, exchange rates, interest rates, and commodity prices. These series are assembled from a wide variety of primary and secondary sources, including national statistical offices, central banks, the League of Nations, the IMF, the World Bank, and a large number of country-specific historical studies.

### The BCDI composite index

To summarize the overall incidence of crises across countries and time, Reinhart and Rogoff construct a composite crisis index called the **BCDI index** (Banking, Currency, Default, Inflation). For each country in each year, the index can take values from zero (no crisis) to five or six (simultaneous banking crisis, currency crash, external default, domestic default, and inflation crisis, plus possibly a stock market crash). The aggregate world BCDI index, weighted by each country's share of world income, provides a summary measure of global financial instability over time.

This composite index reveals several striking patterns. First, the period from roughly 1945 to 1970 stands out as an era of unusual financial calm, at least in comparison with the preceding and following periods. Second, the frequency of crises increases markedly after the breakdown of the Bretton Woods system in the early 1970s and the wave of financial liberalization that followed. Third, even the most severe modern crises (the 1980s debt crisis, the 1990s emerging market crises, the 2007-2009 global financial crisis) do not match the intensity of the crisis waves of the 1930s or the pre-World War I era in terms of the share of countries simultaneously in crisis.

### Identification methodology

The Reinhart-Rogoff identification methodology varies by crisis type. For currency crashes and inflation crises, the identification is purely quantitative: a crisis is declared when the relevant variable crosses a predefined threshold. For banking crises and sovereign defaults, identification relies more heavily on narrative evidence and qualitative judgment.

For banking crises, Reinhart and Rogoff define an episode as beginning with one of two types of events: bank runs that lead to the closure, merging, or government takeover of financial institutions, or the closure, merging, takeover, or government assistance of an important financial institution that marks the start of a string of similar outcomes. This event-based approach is necessitated by the lack of consistent quantitative indicators (such as bank stock prices or non-performing loan ratios) across the full time span of the dataset. The approach is effective for identifying major episodes but involves inevitable judgment calls, particularly for the earlier historical periods where the documentary record is sparse.

For sovereign defaults, the identification draws on a large body of prior work by Lindert and Morton (1989), Suter (1992), Purcell and Kaufman (1993), Standard and Poor's, and many others. The key innovation of Reinhart and Rogoff is the inclusion of domestic defaults, which had been systematically neglected in the prior literature. As they argue, the common assumption that countries will always honor their domestic debt (because the government can simply inflate it away) is contradicted by the historical record. Numerous countries, including advanced economies, have defaulted on or forcibly restructured their domestic debt obligations.

### Key findings

The long-run perspective of the Reinhart-Rogoff dataset yields several findings that would be invisible in a shorter time series:

**Serial default is the norm.** Most countries that have defaulted once have defaulted multiple times. France defaulted eight times between 1558 and 1788. Spain defaulted thirteen times between 1557 and 1882. These are not marginal economies; they are countries that went on to become major economic powers. The pattern of serial default reflects what Reinhart, Rogoff, and Savastano (2003) call "debt intolerance": countries with a history of default tend to get into trouble at lower debt levels than countries without such a history.

**Advanced economies are not immune.** Before the global financial crisis, there was a widespread belief that banking crises were primarily a developing-country problem. The Reinhart-Rogoff data show that this belief was itself an instance of the "this time is different" syndrome. The United Kingdom, the United States, and France, the historical centers of global finance, are among the countries with the most banking crisis episodes. Between 1800 and 2008, Reinhart and Rogoff document 13 banking crises in the United States, 12 in the United Kingdom, and 15 in France. The period of relative calm after World War II was the exception, not the rule.

**Financial crises cluster across types.** Banking crises, currency crashes, sovereign defaults, and inflation crises tend to occur together, especially in severe episodes. The Russian crisis of 1998, for instance, involved a banking crisis, a currency crash, an external default, a domestic default, and an inflation crisis simultaneously, producing a BCDI index value of 5. This clustering reflects the feedback mechanisms between different crisis types that we discussed in subsection 1.2.

**Debt surges precede crises.** {cite:t}`ReinhartRogoff2011` show that the connection between financial crises and debt is robust and bidirectional. Banking crises are typically preceded by surges in private credit, and they are typically followed by surges in public debt (as the government absorbs the losses of the banking sector and runs fiscal deficits during the recession). The banking crisis then increases the probability of a sovereign debt crisis.

## The Laeven-Valencia Systemic Banking Crises Database

### Scope and coverage

The database compiled by {cite:t}`LaevenValencia2020`, published in the *IMF Economic Review*, covers a shorter period than the Reinhart-Rogoff dataset (1970 to 2017) but provides more systematic and detailed information for the episodes it covers. The database identifies 151 systemic banking crises across the globe during this period. It also records currency crises and sovereign debt crises that occurred during the same time frame, making it possible to study the sequencing and interaction between different crisis types.

For each banking crisis episode, the database records:

**Crisis dates.** The year the crisis began and the year it ended. The end date is particularly valuable because it allows researchers to measure crisis duration, which varies considerably across episodes (from one year to more than a decade).

**Policy responses.** The database tracks six categories of policy intervention: extensive liquidity support from the central bank, blanket guarantees on deposits and other liabilities, significant bank recapitalizations using government funds, significant asset purchases or transfers (including the creation of asset management companies), bank nationalizations, and deposit freezes. For each category, the database records whether the intervention was used and, where possible, its scale.

**Fiscal costs.** The gross fiscal cost of the crisis, measured as the direct outlays by the government on financial sector rescue operations, expressed as a percentage of GDP. The database also records the net fiscal cost (gross cost minus any recoveries from asset sales) and the increase in public debt over the crisis period.

**Output losses.** The cumulative loss in real GDP relative to trend during the crisis period, expressed as a percentage of trend GDP. This measure captures the total output foregone as a result of the crisis, relative to what would have been produced in the absence of the crisis.

### Identification methodology

The Laeven-Valencia identification methodology, as discussed in subsection 1.2, requires the simultaneous presence of two conditions: significant signs of financial distress in the banking system and significant policy interventions in response. This dual requirement produces a relatively conservative list of episodes. It excludes mild banking stress that was resolved without significant government intervention, and it also excludes cases where the government intervened preemptively before distress became visible.

For currency crises, Laeven and Valencia use a depreciation threshold of at least 30% that is also at least 10 percentage points greater than the rate in the preceding year. For sovereign debt crises, they use default events as identified by Standard and Poor's or the presence of an IMF program with access above 100% of the country's quota.

### Key findings

The Laeven-Valencia database has generated several important findings, particularly regarding the relationship between crisis characteristics and country income levels.

**Crises in high-income countries last longer.** This finding may seem counterintuitive, since high-income countries generally have stronger institutions and greater fiscal capacity to respond to crises. The explanation appears to be that high-income countries tend to rely more heavily on bank guarantees and expansionary macroeconomic policies, which can stabilize the immediate crisis but slow the process of balance sheet repair and structural adjustment. Lower-income countries, by contrast, tend to experience sharper but shorter crises, in part because they have less fiscal capacity to sustain prolonged interventions.

**Crises in high-income countries have higher output losses but lower fiscal costs.** High-income countries lose more output (relative to trend) during banking crises than lower-income countries, but spend less in direct fiscal outlays on bank rescue operations. This pattern reflects the greater reliance of high-income countries on implicit guarantees and expansionary monetary and fiscal policy, as opposed to explicit bank bailouts.

**Sovereign debt and currency crises tend to follow banking crises.** Consistent with the findings of {cite:t}`ReinhartRogoff2011`, the Laeven-Valencia data show that sovereign debt crises and currency crises typically coincide with or follow banking crises, rather than preceding them. This sequencing supports the view that banking crises are often the initial shock, and that sovereign and currency crises emerge as secondary consequences through the fiscal cost of bank bailouts and the loss of confidence in the government's solvency.

**Policy responses matter.** The database provides evidence that the design of the policy response affects crisis outcomes. Early and decisive intervention (particularly the use of blanket guarantees to halt bank runs, combined with recapitalization to restore bank solvency) is associated with shorter crisis duration and lower output losses than delayed or partial intervention. We will examine this evidence in detail in later sessions on crisis management and resolution.

## Complementary databases

The Reinhart-Rogoff and Laeven-Valencia databases are the two most widely used, but they are not the only sources of crisis data. Several other databases are useful for specific purposes.

**BIS credit-to-GDP gap.** The Bank for International Settlements maintains quarterly data on the credit-to-GDP gap for 44 countries. The credit-to-GDP gap is defined as the deviation of the credit-to-GDP ratio from its long-run trend, estimated using a one-sided Hodrick-Prescott filter with a very high smoothing parameter (lambda = 400,000). The BIS credit gap has been adopted by the Basel Committee on Banking Supervision as the key indicator for guiding the activation of the countercyclical capital buffer, a macroprudential policy tool introduced under Basel III ({cite:t}`Drehmann2014`). We use this data in the accompanying visualizations notebook.

**The Jorda-Schularick-Taylor Macrohistory Database.** This database, maintained by economists at the Federal Reserve Bank of San Francisco and the University of Bonn, provides long-run annual macrofinancial data for 18 advanced economies from 1870 to the present. It includes data on bank loans, total credit, house prices, stock prices, interest rates, exchange rates, and a range of macroeconomic variables. The database is particularly valuable for studying the role of credit growth in driving financial crises over the long run.

**The Harvard Business School Behavioral Finance and Financial Stability (BFFS) Project.** This project, initiated by Carmen Reinhart and maintained at Harvard, keeps the Reinhart-Rogoff dataset updated and extends it with additional variables and country coverage. Banking crisis dates for more than 70 countries from 1800 to the present are available through this project, along with data on exchange rate arrangements, stock market crises, and sovereign debt growth.

**FRED (Federal Reserve Economic Data).** The Federal Reserve Bank of St. Louis maintains a large and freely accessible database of economic time series, including many that are useful for crisis analysis: financial stress indices, credit spreads, interest rates, and measures of economic activity. We use FRED data throughout the course as a supplement to the specialized crisis databases.

:::{table} Summary of Key Crisis Databases
:label: table-databases-summary

| Database | Authors | Period | Countries | Crisis types | Policy data | Cost data |
|---|---|---|---|---|---|---|
| This Time Is Different | Reinhart & Rogoff (2009) | 1300s-2008 | 66 | Banking, currency, sovereign (ext. & dom.), inflation | No | Limited |
| Systemic Banking Crises II | Laeven & Valencia (2020) | 1970-2017 | Global (151 episodes) | Banking, currency, sovereign | Yes (6 categories) | Yes (fiscal & output) |
| BIS Credit Gap | BIS | ~1960-present | 44 | Early warning indicator | N/A | N/A |
| Macrohistory Database | Jorda, Schularick, Taylor | 1870-present | 18 (advanced) | Banking | No | Limited |
| BFFS Global Crises Data | Reinhart et al. (HBS) | 1800-present | 70+ | Banking, currency, sovereign, inflation | No | Limited |

:::

## Strengths and limitations

No database is perfect, and understanding the strengths and limitations of each is essential for using them correctly.

### The trade-off between breadth and precision

The Reinhart-Rogoff dataset sacrifices precision for breadth. Its coverage of eight centuries across 66 countries is unmatched, but the identification of banking crises in the earlier periods relies heavily on narrative evidence and qualitative judgment. Two researchers looking at the same historical sources might reasonably disagree about whether a particular episode constitutes a "crisis." The Laeven-Valencia database achieves greater precision through its dual-condition identification methodology and its systematic recording of policy responses and costs, but at the cost of a much shorter time span (1970-2017) and a focus exclusively on systemic banking crises.

For the purposes of this course, we draw on both databases according to the analytical question being asked. When we study long-run patterns (such as the frequency of crises over time, or the relationship between crises and debt), we rely primarily on Reinhart and Rogoff. When we study the details of crisis management and resolution (such as the effectiveness of different policy interventions, or the fiscal costs of bank bailouts), we rely primarily on Laeven and Valencia.

### The problem of crisis dating

Determining when a crisis begins and ends is less straightforward than it might seem. Banking crises, in particular, often build gradually over months or years before they are recognized as crises. The "start date" of a crisis is often a judgment call: is it the first bank failure, the first government intervention, or the point at which the problems become systemic? Different choices can shift the start date by a year or more, which matters for studies that examine the conditions prevailing before the crisis.

The end date is even more ambiguous. When is a crisis "over"? When the last bank is recapitalized? When output returns to its pre-crisis level? When output returns to its pre-crisis trend? When extraordinary policy support is withdrawn? Different definitions produce different crisis durations, which in turn affect estimates of output losses and other costs.

### Survivorship and selection bias

All crisis databases are subject to selection bias. The Reinhart-Rogoff dataset, despite its ambition, is limited to countries for which adequate historical records exist. This means that the very poorest countries, and countries whose state institutions were too weak to maintain records, are underrepresented. It also means that crises that occurred in countries that no longer exist (the Ottoman Empire, the Austro-Hungarian Empire, various pre-colonial states) may be missed or misattributed. The Laeven-Valencia database avoids some of these problems by focusing on the modern period, but it is limited to crises that were severe enough to trigger significant policy interventions, which means that milder episodes of banking stress are excluded.

### The boundary problem

The taxonomy of crisis types (banking, currency, sovereign debt) is analytically useful, but the boundaries are often artificial. As we discussed in subsection 1.2, the most severe crises involve the interaction of multiple crisis types, and the classification of an episode into one category or another can obscure important dynamics. The European sovereign debt crisis, for instance, involved banking crises, sovereign debt crises, and currency-crisis-like dynamics within a monetary union, and any single-category classification fails to capture its complexity.

Despite these limitations, the Reinhart-Rogoff and Laeven-Valencia databases remain indispensable tools for the study of financial crises. Together, they provide the empirical foundation for the stylized facts, theoretical models, and policy lessons that constitute the core of this course. In the next subsection, we use these databases to establish the key stylized facts about financial crises.

---

## Data access

The datasets discussed in this subsection are publicly available:

Reinhart-Rogoff Dataset and BFFS Global Crises Data: [https://www.hbs.edu/behavioral-finance-and-financial-stability/data/Pages/global.aspx](https://www.hbs.edu/behavioral-finance-and-financial-stability/data/Pages/global.aspx)

Laeven-Valencia Systemic Banking Crises Database: [https://www.imf.org/en/publications/wp/issues/2018/09/14/systemic-banking-crises-revisited-46232](https://www.imf.org/en/publications/wp/issues/2018/09/14/systemic-banking-crises-revisited-46232)

BIS Credit-to-GDP Gap: [https://www.bis.org/statistics/c_gaps.htm](https://www.bis.org/statistics/c_gaps.htm)

Jorda-Schularick-Taylor Macrohistory Database: [https://www.macrohistory.net/database/](https://www.macrohistory.net/database/)

FRED (Federal Reserve Economic Data): [https://fred.stlouisfed.org/](https://fred.stlouisfed.org/)

---

## Readings for this subsection

**Required:**

Reinhart, C. M. and Rogoff, K. S. (2009). *This Time Is Different: Eight Centuries of Financial Folly*. Princeton University Press. Chapter 1 (introduction to the dataset) and Appendix (data sources and definitions).

Laeven, L. and Valencia, F. (2020). Systemic Banking Crises Database II. *IMF Economic Review*, 68(2), 307-361.

**Recommended:**

Reinhart, C. M. and Rogoff, K. S. (2011). From Financial Crash to Debt Crisis. *American Economic Review*, 101(5), 1676-1706.

Reinhart, C. M. and Rogoff, K. S. (2010). On Graduation from Default, Inflation, and Banking Crises: Elusive or Illusion? *NBER Macroeconomics Annual*, 25, 1-36.

Jorda, O., Schularick, M. and Taylor, A. M. (2017). Macrofinancial History and the New Business Cycle Facts. *NBER Macroeconomics Annual*, 31, 213-263.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
