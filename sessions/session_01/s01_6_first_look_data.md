---
title: "1.6 A First Look at the Data"
subtitle: Visualizations and data exploration
---

The stylized facts presented in subsection 1.5 are more compelling when they can be seen in the data. This subsection provides two visualizations that bring the patterns to life, each drawn from one of the major databases discussed in subsection 1.4. A companion Jupyter notebook (`session_01_visualizations.ipynb`) allows you to reproduce and customize these figures.

## Figure 1: Timeline of systemic banking crises

The first figure uses the Laeven-Valencia Systemic Banking Crises Database ({cite:t}`LaevenValencia2020`) to display a timeline of systemic banking crises across a selection of countries from 1970 to 2017. Each horizontal bar indicates a period during which the country was experiencing a systemic banking crisis according to the Laeven-Valencia identification criteria (significant financial distress plus significant policy interventions).

The figure illustrates several of the stylized facts simultaneously. The clustering of crises is immediately visible: notice the concentration of episodes in the early 1980s (Latin America), the early 1990s (Nordic countries, Japan), the late 1990s (Asia), and 2007-2009 (global). The universality of crises is also apparent: the sample includes both advanced economies (the United States, the United Kingdom, Spain, Iceland) and emerging markets (Argentina, Thailand, Indonesia, Nigeria), all of which have experienced at least one systemic banking crisis during the sample period.

The crisis dates used in the figure are drawn directly from Table A1 of the original Laeven-Valencia IMF Working Paper (WP/18/206). The notebook allows you to modify the country selection, the time window, and the visual style.

:::{figure} #crisis-timeline
:label: fig-crisis-timeline

Timeline of systemic banking crises across selected countries (1970-2017). Each shaded bar indicates a crisis episode. Data source: {cite:t}`LaevenValencia2020`, Systemic Banking Crises Database II, IMF Economic Review.
:::

## Figure 2: The BIS credit-to-GDP gap for the United States

The second figure uses data from the Bank for International Settlements to plot the credit-to-GDP gap for the United States over the period from the late 1960s to the present. The credit-to-GDP gap is the deviation of the private non-financial sector credit-to-GDP ratio from its long-run trend, estimated using a one-sided Hodrick-Prescott filter with a smoothing parameter of 400,000 ({cite:t}`Drehmann2014`).

The figure provides a vivid illustration of Stylized Fact 4 (credit booms precede crises). Two major credit booms are clearly visible. The first occurred in the 1980s, preceding the Savings and Loan crisis. The second, much larger boom occurred in the early to mid-2000s, driven by the expansion of mortgage credit, and peaked just before the global financial crisis of 2007-2009. In both cases, the credit-to-GDP gap turned sharply positive well before the crisis, reaching levels above the 10 percentage point threshold that the Basel Committee uses as a guide for activating the countercyclical capital buffer.

Grey shaded areas in the figure indicate NBER-dated recessions. Notice that the credit-to-GDP gap tends to be negative during and after recessions (as credit contracts faster than GDP) and positive during the late stages of expansions (as credit grows faster than GDP). This procyclicality of credit is one of the key mechanisms that generates financial fragility during booms.

The data are downloaded in real time from the BIS Statistics Warehouse. The notebook allows you to change the country, the time window, and the recession shading.

:::{figure} #credit-gap-us
:label: fig-credit-gap

BIS credit-to-GDP gap for the United States. The gap is defined as the deviation of the credit-to-GDP ratio from its long-run trend (one-sided HP filter, lambda = 400,000). Grey shaded areas indicate NBER-dated recessions. Data source: Bank for International Settlements, [Credit-to-GDP gaps](https://www.bis.org/statistics/c_gaps.htm).
:::

## Using the notebook

The companion notebook `session_01_visualizations.ipynb` contains all the code needed to reproduce these figures. The notebook is organized into clearly labeled sections with parameters at the top that you can modify.

For **Figure 1**, you can change the list of countries, the time window, and the color scheme. The crisis dates are entered manually from the Laeven-Valencia database to ensure accuracy and reproducibility without requiring an internet connection.

For **Figure 2**, the notebook downloads the BIS credit-to-GDP gap data directly from the BIS Statistics Warehouse API. You can change the country code to plot the gap for any of the 44 countries covered by the BIS. The NBER recession dates are included for the United States; for other countries, you would need to source the relevant business cycle dates.

Both figures are saved as PNG files in the `sessions/` directory when the notebook is executed.

## What to look for

As you examine these figures, keep the following questions in mind. They connect the visual patterns to the conceptual framework developed in the preceding subsections.

In the crisis timeline, which crises appear to cluster together? Can you identify the common shocks that might explain the clustering (e.g., the Volcker interest rate shock for the 1980s Latin American cluster, or the U.S. subprime shock for the 2007-2009 global cluster)?

In the credit-to-GDP gap figure, how far in advance of each crisis does the gap become elevated? Is the gap a "leading indicator" in the sense that it turns positive well before the crisis hits, or does it peak close to the onset of the crisis?

Are there periods when the gap was elevated but no crisis followed? If so, what might have prevented the credit boom from turning into a crisis? These are the questions that will occupy us throughout the rest of the course.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
