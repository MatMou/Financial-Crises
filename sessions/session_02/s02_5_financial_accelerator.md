---
title: "2.5 The Financial Accelerator and Credit Cycles"
subtitle: Amplification mechanisms in macroeconomic models
---

The preceding subsections established that financial markets are prone to adverse selection, moral hazard, coordination failures, and contagion. These are microeconomic results about individual markets and institutions. But financial crises are macroeconomic events: they cause recessions, increase unemployment, and reduce output for years. To understand how micro-level financial frictions produce macro-level economic fluctuations, we need models that embed financial frictions in a general equilibrium framework.

This subsection surveys two foundational contributions that accomplished this task: the Bernanke-Gertler-Gilchrist financial accelerator and the Kiyotaki-Moore model of credit cycles. Both models show how financial frictions amplify and propagate shocks, turning small disturbances into large fluctuations. They provide the theoretical foundation for the macroprudential policy framework discussed in Session 17 and for the empirical early warning indicators discussed in Session 16.

## The external finance premium

The starting point for both models is the observation that external finance (borrowing from a bank or issuing securities on the capital market) is more expensive than internal finance (using retained earnings or cash on hand). In a frictionless world, the Modigliani-Miller theorem tells us that the source of finance does not matter: the cost of capital is determined by the riskiness of the investment, not by how it is financed. But in a world with information asymmetries, the cost of external finance exceeds the cost of internal finance by an amount that reflects the lender's cost of evaluating, monitoring, and enforcing the loan contract. This wedge is called the **external finance premium**.

The external finance premium is not constant. It depends on the borrower's financial condition, particularly on the borrower's **net worth**, meaning the difference between the value of the borrower's assets and the value of the borrower's liabilities. When net worth is high, the borrower can pledge more collateral, which reduces the lender's risk and therefore reduces the premium. When net worth is low, the borrower has less collateral, the lender bears more risk, and the premium rises. This negative relationship between borrower net worth and the external finance premium is the key mechanism that generates amplification.

## The Bernanke-Gertler-Gilchrist financial accelerator

The financial accelerator, developed by Bernanke, Gertler, and Gilchrist (1999), formalizes the amplification mechanism in a dynamic general equilibrium model ({cite:t}`BernankeGertlerGilchrist1999`). The model builds on an earlier paper by Bernanke and Gertler (1989), which introduced the idea into a simple real business cycle framework.

The model economy contains households, firms (entrepreneurs), and a financial intermediary (bank). Entrepreneurs own capital, which they use in production, and they finance their capital holdings partly with internal funds (net worth) and partly with external borrowing from the bank. The bank faces a costly state verification problem: after the entrepreneur's project has been realized, the bank cannot costlessly observe the project's return. If the bank wants to verify the return (which is necessary when the entrepreneur claims the project failed and cannot repay the loan), it must pay an auditing cost. This auditing cost is the source of the external finance premium.

The optimal lending contract in this environment is a standard debt contract: the entrepreneur pays a fixed amount if the project succeeds (and the bank does not audit) and the bank seizes whatever is available if the project fails (the bank does audit). The external finance premium, the difference between the interest rate on the loan and the risk-free rate, is increasing in the leverage ratio (the ratio of borrowing to net worth). Entrepreneurs with more net worth relative to their borrowing pay a lower premium; entrepreneurs with less net worth pay a higher premium.

The financial accelerator operates through the following mechanism. Consider a negative shock to the economy, say a decline in productivity or a fall in asset prices. This shock reduces the income and the net worth of entrepreneurs. The decline in net worth increases the external finance premium, which raises the cost of investment. Higher investment costs lead to a decline in investment, which reduces output and employment. The decline in economic activity further reduces entrepreneurial income and asset prices, which further reduces net worth, which further raises the external finance premium. The process feeds on itself, amplifying the initial shock.

The amplification works in both directions. During a boom, rising asset prices and profits increase entrepreneurial net worth, which reduces the external finance premium, which stimulates investment, which raises output and asset prices further. The financial accelerator thus generates procyclical leverage (net worth rises during booms and falls during busts) and countercyclical risk premia (the external finance premium falls during booms and rises during busts), both of which are consistent with empirical observations about credit markets.

Several features of the financial accelerator deserve emphasis.

First, the amplification mechanism is **quantitatively significant**. In calibrated versions of the model, the financial accelerator can roughly double the response of output to a given shock compared to a model without financial frictions. This helps explain why recessions associated with financial crises tend to be deeper and longer than "normal" recessions.

Second, the amplification depends on the **initial balance sheet conditions**. If the economy enters a downturn with high levels of entrepreneurial net worth, the financial accelerator is weak because borrowers have substantial collateral buffers. If the economy enters with low net worth and high leverage, the accelerator is strong. This connects the Bernanke-Gertler-Gilchrist model to Minsky's insight that the buildup of fragility during a boom determines the severity of the subsequent bust.

Third, the model provides a formal basis for the **credit channel** of monetary policy transmission. Monetary policy affects the economy not only through the traditional interest rate channel (changes in the policy rate alter the cost of borrowing directly) but also through the balance sheet channel (changes in interest rates and asset prices affect borrower net worth, which affects the external finance premium, which affects investment). The credit channel implies that monetary policy has larger effects when balance sheets are weak than when they are strong, and that financial conditions can amplify or attenuate the impact of policy changes.

## The Kiyotaki-Moore model of credit cycles

A complementary model was developed by Nobuhiro Kiyotaki and John Moore in their 1997 paper "Credit Cycles" ({cite:t}`KiyotakiMoore1997`). The Kiyotaki-Moore model generates amplification through a different mechanism: the dual role of assets as both factors of production and collateral for borrowing.

In the Kiyotaki-Moore model, there are two types of agents: productive entrepreneurs (who have good investment opportunities but insufficient internal funds) and less productive agents (who have excess funds but fewer opportunities). Entrepreneurs borrow from the less productive agents, using their landholdings as collateral. A key assumption is that debt contracts are imperfectly enforceable: the maximum that a borrower can credibly promise to repay is determined by the value of the collateral, not by the value of the investment project. This collateral constraint is the source of the financial friction.

The amplification mechanism in Kiyotaki-Moore is driven by the interaction between asset prices and borrowing capacity. When land prices rise, entrepreneurs' collateral increases in value, which allows them to borrow more, which allows them to buy more land, which pushes land prices up further. When land prices fall, the mechanism works in reverse: collateral values decline, borrowing capacity shrinks, entrepreneurs are forced to sell land, which pushes prices down further.

The distinctive feature of the Kiyotaki-Moore model is the emphasis on **persistence** rather than just amplification. The model generates credit cycles that are longer and more persistent than the underlying shocks. A temporary productivity shock can set off a multi-period cycle of rising and then falling asset prices, credit, and output, because the balance sheet adjustments take time to work through the system. The "credit cycle" of the title is not just a response to the business cycle; it is a self-contained dynamic that can outlast the shock that triggered it.

The Kiyotaki-Moore model also generates **fire-sale externalities**. When a negative shock forces entrepreneurs to sell assets, the resulting decline in asset prices reduces the borrowing capacity of other entrepreneurs, who may in turn be forced to sell. This pecuniary externality means that the social cost of asset price declines exceeds the private cost, because the effects are transmitted through the collateral channel to other borrowers. This externality provides a theoretical rationale for macroprudential regulation: policies that limit leverage or require countercyclical capital buffers can reduce the severity of fire-sale dynamics and improve welfare.

## Comparing the two models

The Bernanke-Gertler-Gilchrist and Kiyotaki-Moore models share the fundamental insight that financial frictions create amplification mechanisms through which small shocks produce large fluctuations. But they differ in several important respects.

The source of the friction differs. In Bernanke-Gertler-Gilchrist, the friction is costly state verification: the lender cannot costlessly observe the borrower's return. In Kiyotaki-Moore, the friction is limited enforcement: the borrower can walk away from the debt, and the lender can only seize the collateral. These are different microeconomic stories, but they produce similar macroeconomic dynamics.

The amplification mechanism differs. In Bernanke-Gertler-Gilchrist, the amplification works through the external finance premium: lower net worth raises the cost of borrowing. In Kiyotaki-Moore, the amplification works through the collateral constraint: lower asset prices reduce borrowing capacity directly. In practice, both mechanisms are likely to be at work simultaneously.

The dynamics differ. The Bernanke-Gertler-Gilchrist model emphasizes contemporaneous amplification: the shock is larger because of the financial friction. The Kiyotaki-Moore model emphasizes dynamic propagation: the effects of the shock are spread over time as balance sheets adjust. Both features are observed in real financial crises, which tend to involve both a sharp initial contraction and a slow, painful recovery.

## The leverage cycle

The models discussed above were developed in the 1990s and early 2000s, before the global financial crisis. The crisis stimulated a burst of new research that extended and enriched the basic framework. One of the most influential contributions was the concept of the **leverage cycle**, developed by John Geanakoplos (2010) ({cite:t}`Geanakoplos2010`).

Geanakoplos argued that the standard focus on interest rates as the key variable in credit markets is incomplete. What matters equally, and often more, is the **margin** or **haircut**: the fraction of the asset's value that the borrower must finance with their own equity. When margins are low (leverage is high), small changes in asset prices produce large changes in equity values, which produce large changes in borrowing capacity. When margins are high (leverage is low), the same asset price change has a much smaller effect on equity and borrowing capacity.

The leverage cycle arises because margins are endogenous and procyclical. During booms, when volatility is low and asset prices are rising, lenders reduce margin requirements because the perceived risk of loss is low. Lower margins allow borrowers to take larger positions, which pushes asset prices up further, which further reduces perceived risk, which further reduces margins. During busts, the process reverses: rising volatility and falling asset prices cause lenders to raise margin requirements. Borrowers who can no longer meet the higher margin requirements are forced to sell assets, which depresses prices further.

The leverage cycle has two important implications. First, it generates much larger fluctuations in asset prices and credit than models that focus only on interest rates. In Geanakoplos's framework, the collapse is driven not by a rise in interest rates but by a rise in margins, which forces deleveraging even when interest rates are low. This is consistent with the experience of the 2007-2009 crisis, during which interest rates were cut to near zero but credit contracted sharply because margin requirements rose and collateral values fell.

Second, it suggests a distinct policy instrument: regulation of leverage or margins. If the central bank sets minimum margin requirements that are countercyclical (high during booms, low during busts), it can moderate the leverage cycle and reduce the amplitude of asset price fluctuations. This is one of the intellectual foundations of the macroprudential toolkit discussed in Session 17.

## From theory to the real world

The financial accelerator, the Kiyotaki-Moore credit cycle, and the Geanakoplos leverage cycle have collectively transformed macroeconomics. Before these models, the dominant macroeconomic frameworks (real business cycle models, new Keynesian models) treated the financial sector as a frictionless intermediary that played no independent role in business cycle dynamics. After the global financial crisis demonstrated the catastrophic consequences of financial fragility, these models became central to both academic research and policy analysis.

Central banks now routinely use DSGE models with financial frictions (including versions of the financial accelerator) to analyze monetary policy and to assess financial stability risks. The Basel III framework, with its countercyclical capital buffer and leverage ratio, is grounded in the theoretical insight that procyclical leverage creates systemic risk. Stress testing exercises use network models of contagion (subsection 2.4) combined with balance-sheet amplification mechanisms (this subsection) to evaluate the resilience of the banking system to adverse scenarios.

At the same time, the models have significant limitations. They generate amplification but not the kind of catastrophic, nonlinear collapses that characterize the worst crises. They typically assume that the financial friction is a permanent feature of the environment rather than something that evolves endogenously (as Minsky argued). And they have difficulty generating the sudden freezes in credit markets that are among the most distinctive features of financial crises. The challenge of building models that combine the amplification mechanisms of the financial accelerator with the coordination failures of Diamond-Dybvig and the endogenous fragility of Minsky remains one of the most active frontiers of macroeconomic research.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
