---
title: "16.1 Early Warning Systems: The Logic and the Evidence"
subtitle: Can we see crises coming?
---

The idea that financial crises might be predicted, or at least that their probability might be estimated in advance, has motivated a large body of empirical research. The earliest systematic early warning systems (EWS) were developed in the late 1990s in response to the emerging market crises (Session 7), and the literature expanded enormously after the GFC exposed the inadequacy of the pre-crisis monitoring framework. This subsection introduces the two main approaches to early warning and examines the evidence on their predictive performance.

## The signal extraction approach

The signal extraction approach, pioneered by Kaminsky, Lizondo, and Reinhart (1998) in their influential "leading indicators" paper, works as follows. The researcher identifies a set of candidate indicators (such as credit growth, current account deficits, real exchange rate appreciation, equity price increases, and real estate price increases) and examines whether these indicators tend to behave abnormally in the period (typically 12-24 months) before a crisis. For each indicator, a threshold is chosen such that the indicator is "on" when it exceeds the threshold and "off" otherwise. The threshold is optimized to balance the trade-off between correctly predicting crises that occur (minimizing missed crises, or Type II errors) and incorrectly predicting crises that do not occur (minimizing false alarms, or Type I errors).

The signal extraction approach is intuitive and transparent. Each indicator is evaluated independently, and its predictive power is measured by its noise-to-signal ratio: the ratio of false alarms to correct signals. Indicators with low noise-to-signal ratios are useful predictors; those with high ratios are not. The approach can combine multiple indicators into a composite index by counting the number of indicators that are simultaneously "on."

The Kaminsky-Lizondo-Reinhart study found that the most useful individual indicators for currency crises were the real exchange rate, credit growth, the current account balance, and the level of international reserves. Subsequent extensions to banking crises by Demirguc-Kunt and Detragiache (1998), Borio and Lowe (2002), and others found that credit growth and asset prices were the most reliable predictors of banking crises.

## The regression-based approach

The regression-based approach uses multivariate regression (typically logit or probit models) to estimate the probability of a crisis as a function of multiple indicators simultaneously. The dependent variable is a binary indicator of crisis (1 if a crisis occurs within a specified horizon, 0 otherwise), and the independent variables are the candidate indicators.

The regression approach has the advantage of allowing for interactions between indicators and of providing a single probability estimate that summarizes the information in all indicators. Its disadvantage is that it requires the researcher to specify a functional form for the relationship between the indicators and the crisis probability, and that the results can be sensitive to the sample period, the crisis definition, and the choice of indicators.

The most influential regression-based studies for banking crises include Schularick and Taylor (2012), who showed that credit growth is a powerful predictor of banking crises across 14 advanced economies over 140 years, and Jordà, Schularick, and Taylor (2011), who extended this analysis to show that credit-intensive recessions are associated with slower recoveries (subsection 3.1).

## The crisis definition problem

A fundamental challenge for all early warning systems is the **crisis definition**. Different studies use different definitions of what constitutes a crisis (banking crisis, currency crisis, sovereign debt crisis, or some combination), and the results can be sensitive to the definition used. The Laeven-Valencia database (subsection 1.4), which identifies systemic banking crises based on a combination of quantitative criteria (significant banking sector losses, government intervention) and qualitative judgment, has become the standard reference, but it is not immune to classification disputes.

The crisis definition also affects the evaluation of predictive performance. A narrow definition (only the most severe crises) produces fewer events, which makes it harder to distinguish signal from noise. A broad definition (including minor banking sector stress episodes) produces more events but may include episodes that are qualitatively different from the severe crises that policymakers most want to predict.

## The Type I / Type II trade-off

The central challenge of early warning systems is the trade-off between false alarms (predicting a crisis that does not occur) and missed crises (failing to predict a crisis that does occur). A system that issues a warning whenever any indicator is slightly elevated will catch most crises but will also produce many false alarms. A system that issues a warning only when multiple indicators are strongly elevated will produce fewer false alarms but will miss crises that develop through unusual channels.

The appropriate balance depends on the costs of each type of error. If the cost of a missed crisis (which may produce a severe recession and financial system collapse) far exceeds the cost of a false alarm (which may produce some unnecessary precautionary tightening), then the system should be calibrated to minimize missed crises, even at the cost of more false alarms. This asymmetry argues for a relatively sensitive threshold, which is the approach adopted by the BIS in its credit-to-GDP gap indicator (subsection 16.2).

---

## References

:::{bibliography}
:filter: docname in docnames
:::
