---
title: "15.4 AI, Algorithmic Trading, and New Sources of Systemic Risk"
subtitle: When machines make the decisions
---

The increasing role of artificial intelligence and algorithmic trading in financial markets creates new sources of systemic risk that do not fit neatly into the frameworks developed in earlier sessions. The risks are not primarily about fraud, leverage, or maturity mismatch (the traditional sources of financial fragility), but about the behavior of complex, interacting automated systems that can produce emergent dynamics, including crashes, contagion, and herding, that no individual participant intended or anticipated.

## Algorithmic trading and market microstructure

Algorithmic trading, the use of computer programs to execute trades based on pre-specified rules, now accounts for the majority of trading volume in equity, foreign exchange, and fixed-income markets. High-frequency trading (HFT), the most technologically intensive form of algorithmic trading, operates on timescales measured in microseconds and accounts for approximately 50% of U.S. equity trading volume.

The systemic risk from algorithmic trading arises not from any individual algorithm but from the interaction of many algorithms operating simultaneously. When multiple algorithms respond to the same market signals in the same way (because they are based on similar models, trained on the same data, or optimized for the same objectives), their collective behavior can amplify market movements rather than dampen them. The **Flash Crash** of May 6, 2010, in which the Dow Jones Industrial Average fell approximately 1,000 points (approximately 9%) and recovered within minutes, was the first major demonstration of this risk. The crash was triggered by a large sell order that interacted with HFT algorithms in a way that produced a cascading sell-off far out of proportion to the initial order.

Subsequent episodes of extreme market volatility, including the August 2015 flash crash, the February 2018 "Volmageddon" (in which exchange-traded products linked to volatility indices collapsed), and the March 2020 Treasury market disruption (subsection 13.2), have all involved algorithmic trading dynamics that amplified the initial shock.

## Model monoculture

A more subtle risk is **model monoculture**: the possibility that the widespread adoption of similar AI models by financial institutions could create correlated behavior that amplifies systemic risk. If many banks, asset managers, and trading firms use similar machine learning models to assess credit risk, price assets, and make trading decisions, they may all reach similar conclusions simultaneously, producing herding behavior that amplifies booms and busts.

The risk is analogous to the model failures that contributed to the GFC: the Gaussian copula model (subsection 9.3) was used by virtually every major financial institution to price and risk-manage CDOs, and when the model's assumptions proved wrong, every institution was affected simultaneously. AI models, which are more complex and less transparent than the Gaussian copula, could produce similar correlated failures if the assumptions embedded in their training data prove invalid under stress conditions.

The opacity of AI models, particularly deep learning models, creates an additional challenge. Unlike traditional financial models, whose assumptions can be examined and challenged, deep learning models are "black boxes" whose decision-making processes are difficult to interpret. If a complex AI model produces an unexpected output during a market stress event, the difficulty of understanding why the model behaved as it did could delay the appropriate policy response.

## AI in financial decision-making

Beyond trading, AI is increasingly being used for credit underwriting, insurance pricing, fraud detection, regulatory compliance, and portfolio management. The systemic risks from these applications are less immediate than the risks from algorithmic trading but potentially more significant over the longer term.

**Credit underwriting by AI** raises concerns about procyclicality. If AI models are trained on historical data in which credit losses were low (as they were during the post-GFC period of low interest rates and rising asset prices), the models may underestimate credit risk during good times and then abruptly tighten credit when conditions deteriorate, amplifying the credit cycle. The parallel to the pre-GFC period, when risk models calibrated on favorable historical data systematically underestimated the probability of a housing downturn, is direct.

**Algorithmic herding in portfolio management** could amplify asset price movements. If AI-driven portfolio management systems, managing trillions of dollars in assets, use similar models to make allocation decisions, their collective buying and selling could amplify market movements, increase correlations across asset classes, and reduce the diversification benefits that portfolio theory assumes.

## Regulatory challenges

The regulation of AI-driven financial activity poses novel challenges. Traditional financial regulation assumes that human decision-makers are ultimately responsible for the actions of financial institutions. When decisions are made by algorithms, the allocation of responsibility becomes unclear. The speed at which algorithmic systems operate (microseconds for HFT, seconds to minutes for AI-driven trading) exceeds the capacity of human oversight, creating the possibility of significant damage before any human can intervene. And the complexity of AI models makes it difficult for regulators to assess whether the models are operating safely.

Regulatory responses have been incremental. Circuit breakers (automatic trading halts triggered by large price movements) address the most extreme manifestations of algorithmic instability but do not address the underlying causes. Requirements for algorithm testing and risk management (such as those in the EU's MiFID II directive) impose procedural safeguards but do not address the systemic risks created by the interaction of many algorithms. The development of regulatory frameworks that are adequate to the risks of AI-driven finance remains an open challenge.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
