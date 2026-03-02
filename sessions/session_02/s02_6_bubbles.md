---
title: "2.6 Rational Bubbles and Irrational Exuberance"
subtitle: Asset pricing, speculation, and the limits of efficiency
---

Almost every major financial crisis is preceded by a dramatic run-up in the price of some asset: tulips in 1637, South Sea Company shares in 1720, railroad stocks in the 1840s, real estate in Japan in the 1980s, technology stocks in the late 1990s, U.S. housing in the mid-2000s. Whether these run-ups constitute "bubbles," meaning episodes in which asset prices depart significantly and persistently from their fundamental value, is one of the most contentious questions in economics. The answer matters greatly for crisis theory and policy: if bubbles can be identified in real time, regulators might be able to intervene before they burst; if they cannot, the scope for preventive policy is limited.

This subsection surveys the theory of asset price bubbles from three perspectives: the rational bubble literature, the efficient markets critique, and behavioral finance. Each offers a different account of why asset prices sometimes rise to levels that, in retrospect, appear unsustainable.

## Fundamental value and the bubble component

The standard framework for thinking about asset prices in finance is the **present value model**. The fundamental value of an asset is the discounted sum of its expected future payoffs (dividends, rents, coupons, or other cash flows):

$$
P_t^f = \sum_{k=1}^{\infty} \frac{E_t[D_{t+k}]}{(1+r)^k}
$$

where $P_t^f$ is the fundamental price at time $t$, $D_{t+k}$ is the payoff at time $t+k$, $r$ is the discount rate (assumed constant for simplicity), and $E_t$ denotes the expectation conditional on information available at time $t$.

A **bubble** is defined as the difference between the actual market price and the fundamental value:

$$
B_t = P_t - P_t^f
$$

If $B_t > 0$, the asset is overpriced relative to fundamentals; the buyer is paying more than the discounted value of the future cash flows. If $B_t = 0$ at all times, the market is "efficient" in the sense that prices fully reflect fundamental value.

This definition is precise in principle but difficult to apply in practice, because the fundamental value depends on expectations about future cash flows and discount rates, neither of which is directly observable. Much of the debate about bubbles reduces to disagreements about these unobservable quantities.

## Rational bubbles

The theory of **rational bubbles** shows that asset prices can deviate from fundamental value even when all agents are fully rational, have common knowledge of the structure of the economy, and form expectations in a manner consistent with rational expectations ({cite:t}`Blanchard1979`).

The basic logic is straightforward. The standard no-arbitrage condition for a risky asset requires that the expected return on the asset equals the required return:

$$
E_t[P_{t+1} + D_{t+1}] = (1+r) P_t
$$

This condition has many solutions. One is the fundamental solution, where $P_t = P_t^f$. But there are also "bubble" solutions of the form $P_t = P_t^f + B_t$, where the bubble component $B_t$ satisfies:

$$
E_t[B_{t+1}] = (1+r) B_t
$$

This equation says that the expected growth rate of the bubble must equal the required rate of return. As long as this condition holds, a rational investor is willing to hold the asset at the bubble price, because the expected capital gain from the growing bubble compensates for the fact that the price exceeds fundamental value. No one is being fooled; everyone knows the price is above fundamentals. But each investor expects to be able to sell to someone else at a still higher price before the bubble bursts.

Rational bubbles have several important theoretical properties. First, once a bubble starts, it must grow over time at the rate $r$. A bubble that stopped growing would violate the no-arbitrage condition, because investors would have no reason to hold an overpriced asset. This implies that rational bubbles grow explosively, which is consistent with the accelerating price increases observed in the late stages of historical booms.

Second, a rational bubble can never restart once it has burst. If the bubble component falls to zero, the no-arbitrage condition can only be satisfied with $B_t = 0$ for all future periods. This means that rational bubble theory cannot explain repeated boom-bust cycles in the same asset, which is a significant limitation given the historical evidence of recurring episodes.

Third, rational bubbles cannot exist in assets with finite lives. If an asset expires at some known date $T$, the bubble must be zero at $T$ (because there is no one to sell to after the asset expires), which by backward induction implies that the bubble must be zero at all prior dates. This rules out rational bubbles on assets like bonds, options, and other finite-maturity instruments, but not on assets with potentially infinite lives like equities and land.

Fourth, rational bubbles are compatible with efficient markets in a specific sense: the expected return on the asset (including the capital gain from the growing bubble) equals the required return. Markets are "informationally efficient" in that prices reflect all available information, including the information that a bubble exists. This is a reminder that market efficiency, as defined in finance theory, does not imply that prices equal fundamental values.

## The efficient markets critique

The strongest opposition to the bubble concept comes from the **efficient markets hypothesis** (EMH), particularly in the form articulated by Eugene Fama. In Fama's framework, asset prices always reflect fundamental values because rational, well-informed traders will buy underpriced assets and sell overpriced assets until prices equal fundamentals. If prices deviate from fundamentals, these deviations are too small and too short-lived to be profitably exploited, and therefore do not constitute economically meaningful bubbles ({cite:t}`Fama2014`).

The EMH critique of bubbles rests on several arguments.

First, if a bubble were identifiable in real time, rational traders would short the overpriced asset and drive its price back to fundamentals. The fact that asset prices sometimes appear to be above fundamental value, in this view, simply reflects our inability to measure fundamental value accurately. Apparent bubbles may actually reflect rational revisions of expectations about future cash flows or discount rates. The run-up in technology stocks in the late 1990s, for example, might reflect rational (if ultimately incorrect) expectations about the profitability of internet companies rather than irrational speculation.

Second, the EMH proponents point to the joint hypothesis problem. Any test of whether asset prices deviate from fundamental values requires a model of what fundamental values should be. If the test rejects the hypothesis that prices equal fundamental values, this could mean either that there is a bubble or that the model of fundamental value is wrong. It is impossible to distinguish between these two interpretations without additional information.

Third, Fama and others argue that the concept of a "bubble" is too vague to be scientifically useful. Ex post, almost any large price increase followed by a large decline can be labeled a bubble, but this labeling has no predictive content. The challenge is to identify a bubble while it is inflating, which the critics argue has never been accomplished with any reliability.

These arguments are logically sound but leave many economists unsatisfied, because they seem to imply that no price movement, no matter how extreme or how clearly disconnected from fundamentals, can be identified as a bubble. The Japanese real estate bubble of the 1980s (during which the grounds of the Imperial Palace in Tokyo were estimated to be worth more than the entire state of California), the dot-com bubble (during which companies with no revenues traded at valuations exceeding those of established industrial firms), and the U.S. housing bubble (during which house prices relative to rents and incomes reached unprecedented levels) all appear, in retrospect, to have involved prices that were dramatically above any plausible measure of fundamental value.

## Behavioral finance and the limits of arbitrage

**Behavioral finance** offers a different account of bubbles, one that does not require investors to be fully rational and does not rely on the no-arbitrage condition to discipline prices. The behavioral approach rests on two pillars: systematic deviations from rationality in investor behavior, and the limits of arbitrage that prevent rational traders from fully correcting the resulting mispricings.

Robert Shiller, who shared the 2013 Nobel Prize with Fama, has been the most prominent advocate of the behavioral view. In *Irrational Exuberance* (2000, revised 2005 and 2015), Shiller argued that asset price booms are driven by a combination of psychological and sociological factors that produce waves of optimism and pessimism that are not justified by fundamentals ({cite:t}`Shiller2015`).

The psychological factors include several well-documented biases. **Overconfidence** leads investors to overestimate their ability to pick winning investments and to underestimate risk. **Extrapolation bias** leads investors to project recent price trends into the future, buying assets whose prices have been rising and selling assets whose prices have been falling, which amplifies price movements. **Herding** leads investors to follow the crowd, either because they infer information from others' behavior or because professional money managers face career risk from underperforming their peers. **Anchoring** causes investors to fix on recent price levels as references, adjusting insufficiently when fundamentals change. **Loss aversion** makes investors reluctant to sell assets at a loss, which can delay price corrections.

Shiller also emphasized the role of **narratives**, the stories that people tell about why prices are rising. During the dot-com boom, the narrative was that the internet had fundamentally changed the economy and that traditional valuation metrics no longer applied. During the housing boom, the narrative was that house prices had never fallen nationally and that rising homeownership was both economically sound and morally virtuous. These narratives are self-reinforcing: rising prices make the narrative more plausible, which attracts more buyers, which pushes prices higher.

The second pillar of behavioral finance is the **limits of arbitrage**, formalized by Shleifer and Vishny (1997). Even if some investors recognize that an asset is overpriced, they may be unable or unwilling to bet against the bubble. Short selling is costly and risky: the bubble may persist longer than the arbitrageur's capital, leading to forced liquidation at a loss ("the market can remain irrational longer than you can remain solvent," as the saying attributed to Keynes goes). Professional money managers who bet against a bubble may underperform their peers during the inflation of the bubble and face withdrawal of funds by their clients. Arbitrage against a mispricing is therefore a risky and potentially career-ending strategy, which means that mispricings can persist for extended periods ({cite:t}`ShleiferVishny1997`).

The combination of investor biases (which push prices away from fundamentals) and limits of arbitrage (which prevent rational traders from fully correcting the mispricing) can generate large, persistent deviations of asset prices from fundamental values, that is, bubbles in the ordinary sense of the word.

## Heterogeneous beliefs and disagreement

A more recent literature has explored a middle ground between the rational and behavioral approaches. Models of **heterogeneous beliefs** show that asset price booms can arise when investors hold different expectations about future payoffs and short selling is costly or restricted ({cite:t}`Scheinkman2003`).

In these models, the asset is held by the most optimistic investors (those who place the highest value on the expected future payoffs). When short selling is limited, pessimistic investors cannot express their views by selling the asset short. The market price therefore reflects the beliefs of the optimists rather than the average belief of all market participants. Moreover, the asset commands a **speculative premium** beyond what even the most optimistic investor would pay based on fundamentals alone, because each buyer anticipates the possibility of reselling the asset to an even more optimistic buyer in the future. This resale option has value and is reflected in the current price.

This framework generates bubble-like dynamics without requiring any investor to be irrational. Each investor is acting on their own honest assessment of the asset's value; the problem is that the market systematically overweights the most optimistic assessments. When uncertainty is high (as it often is for new technologies or during periods of rapid economic change), the dispersion of beliefs is wide, the speculative premium is large, and the scope for overpricing is greatest.

## Policy implications: to prick or not to prick

The question of whether bubbles exist, and whether they can be identified in real time, has direct implications for financial crisis prevention policy.

If the EMH is correct and bubbles cannot be reliably identified, then the best policy is to focus on building a resilient financial system that can withstand the consequences of large asset price declines, rather than trying to prevent the price increases in the first place. This is the "lean versus clean" debate: should policymakers try to "lean against the wind" by tightening monetary or regulatory policy when they suspect a bubble is forming, or should they focus on "cleaning up" after the bubble bursts?

The pre-crisis consensus, associated particularly with Alan Greenspan and Ben Bernanke, was that central banks should not try to identify or deflate bubbles. The argument was that bubbles are difficult to identify, that the tools available to central banks (interest rates) are too blunt to target specific asset prices, and that the costs of raising interest rates to deflate a suspected bubble (higher unemployment, slower growth) might exceed the costs of cleaning up after the bubble bursts.

The global financial crisis severely damaged this consensus. The costs of cleaning up turned out to be vastly larger than anyone had anticipated: the deepest recession since the 1930s, a decade of slow growth in many advanced economies, lasting political consequences. Many policymakers and economists have since argued that more aggressive action to lean against the housing credit boom, whether through higher interest rates, tighter mortgage lending standards, or both, could have reduced the severity of the crisis.

The current mainstream position, reflected in the macroprudential framework discussed in Session 17, is a pragmatic compromise. Central banks should not use interest rates to target specific asset prices (this is too imprecise and too costly), but they should use macroprudential tools (loan-to-value limits, countercyclical capital buffers, stress testing) to limit the buildup of leverage and credit growth during asset price booms. The goal is not to prevent asset prices from rising, but to ensure that the financial system is resilient enough to withstand a correction when it comes.

This is essentially a return to the insight that Minsky articulated decades earlier: the problem is not the bubble per se but the financial fragility that builds up alongside it. Whether asset prices are "too high" relative to fundamentals is a question that may be unanswerable in real time. Whether the financial system has accumulated dangerous levels of leverage and maturity mismatch is a question that can, at least in principle, be measured and addressed through regulation. The credit-to-GDP gap (subsection 1.5), leverage ratios, and other macroprudential indicators are tools for answering this second question, regardless of whether one believes the first question has a meaningful answer.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
