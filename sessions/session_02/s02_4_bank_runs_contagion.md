---
title: "2.4 Bank Runs and Contagion"
subtitle: Coordination failures and systemic risk
---

The information asymmetry framework explains why credit markets are fragile, but it does not fully explain the most dramatic feature of financial crises: the bank run. A bank run is a sudden, self-reinforcing withdrawal of deposits that can destroy a solvent institution in a matter of hours. Bank runs are coordination failures: each depositor's decision to withdraw is individually rational given the expectation that other depositors will also withdraw, even though the collective outcome (the destruction of the bank) is worse for everyone than the alternative (no run). This subsection examines the theory of bank runs, starting with the foundational Diamond-Dybvig model, and then extends the analysis to contagion, where the failure of one institution triggers failures at others through direct exposures, information spillovers, or fire-sale dynamics.

## Why banks are special: maturity transformation and fragility

Before turning to the formal model, it is worth restating why banks are uniquely vulnerable to runs. The essential function of a bank is **maturity transformation**: banks fund long-term, illiquid assets (loans to businesses, mortgages, government securities) with short-term, liquid liabilities (demand deposits, overnight borrowing). This transformation is economically valuable because it allows savers who want liquidity to fund borrowers who need long-term capital. But it also creates a structural mismatch: at any given moment, the bank's liquid assets are far smaller than its liquid liabilities. If all depositors demanded their money at the same time, the bank could not pay them, even if the bank is solvent in the sense that the total value of its assets exceeds the total value of its liabilities.

This structural vulnerability is not a design flaw; it is inherent in the business of banking. A bank that held all of its assets in liquid form (cash, short-term government securities) would be immune to runs but would be unable to perform its core function of funding long-term investment. The tension between the liquidity of liabilities and the illiquidity of assets is what makes banking both useful and fragile.

## The Diamond-Dybvig model

The canonical model of bank runs was developed by Douglas Diamond and Philip Dybvig in their 1983 paper "Bank Runs, Deposit Insurance, and Liquidity" ({cite:t}`DiamondDybvig1983`). The model is remarkable for its simplicity and its ability to generate several key features of real-world banking crises from a small number of assumptions.

The model has three periods (0, 1, 2) and a large number of identical agents. Each agent has an endowment of one unit of a consumption good at period 0. There is a production technology that yields a return $R > 1$ per unit invested if the investment is held to maturity at period 2, but yields only the original unit if the investment is liquidated early at period 1. The technology is productive but illiquid: early liquidation destroys value.

At period 0, agents do not know whether they will need to consume at period 1 (they are "early" or "impatient" consumers) or at period 2 (they are "late" or "patient" consumers). The type is revealed privately to each agent at the beginning of period 1. A fraction $t$ of agents turn out to be early consumers and a fraction $1-t$ are late consumers. In the absence of financial intermediation, each agent faces a choice at period 0: invest the entire endowment in the illiquid technology (which is profitable if the agent turns out to be a late consumer but costly if the agent turns out to be early) or hold it as cash (which is safe but earns no return).

A bank improves on this autarky outcome by pooling the agents' endowments and offering a demand deposit contract. The contract promises each depositor a fixed payment $r_1 > 1$ if they withdraw at period 1, and whatever remains of the bank's assets if they withdraw at period 2. Because the bank serves a large number of depositors and the fraction of early consumers is known (or can be reliably estimated by the law of large numbers), the bank can keep enough liquid assets on hand to serve the early consumers while investing the rest in the illiquid technology. The late consumers receive a return that is higher than $r_1$ because the bank's illiquid investments have had time to mature.

This arrangement is welfare-improving: it provides insurance against liquidity risk that agents cannot obtain on their own. But it also creates the possibility of a bank run.

## Multiple equilibria: the good equilibrium and the run equilibrium

The Diamond-Dybvig model has two Nash equilibria.

In the **good equilibrium**, only the early consumers withdraw at period 1 and the late consumers wait until period 2. The bank has enough liquid assets to pay the early consumers $r_1$ each. The remaining assets mature at period 2 and generate enough to pay the late consumers a return that exceeds $r_1$. Everyone is better off than in autarky.

In the **run equilibrium**, all depositors, both early and late consumers, attempt to withdraw at period 1. Because the bank has invested a portion of its assets in the illiquid technology, it cannot pay $r_1$ to every depositor. It must liquidate its illiquid assets at a loss, and the total proceeds are insufficient to pay everyone. The bank fails, and depositors who arrive late in the queue (determined by random sequential service, or "first come, first served") receive nothing. In this equilibrium, even a patient consumer who does not need the funds at period 1 finds it rational to withdraw, because the patient consumer expects the bank to fail and therefore expects to receive nothing at period 2. The run is self-fulfilling: the belief that the bank will fail causes the bank to fail.

The existence of multiple equilibria is the key result. The run equilibrium is not caused by bad fundamentals (the bank's assets are sufficient to pay all depositors if the game is played out to period 2); it is caused by a coordination failure among depositors. Each depositor's decision depends on what they expect other depositors to do, and there is nothing in the model that pins down which equilibrium is selected. This is what makes bank runs so dangerous: they can occur even at fundamentally solvent banks, and they can be triggered by anything that shifts depositor expectations, a rumor, a news report, the failure of another bank, or simply a change in sentiment.

## Deposit insurance and the lender of last resort

Diamond and Dybvig showed that the run equilibrium can be eliminated by government-provided deposit insurance. If the government credibly promises to pay depositors the full value of their deposits even if the bank fails, then no patient consumer has an incentive to withdraw early, because the deposit is guaranteed regardless of what other depositors do. The run equilibrium disappears, and only the good equilibrium survives.

This result provides a powerful theoretical justification for deposit insurance, which had been introduced in the United States in 1933 (the FDIC) and has since been adopted in virtually every country with a developed banking system. It also provides a justification for the lender of last resort function discussed in subsection 2.1: if the central bank stands ready to lend to solvent but illiquid banks, depositors have less reason to run, because they know the bank can meet withdrawal demands even in a period of stress.

However, as discussed in subsection 2.3, deposit insurance and lender-of-last-resort facilities create moral hazard. If depositors are protected, they have no incentive to monitor the riskiness of their bank. If banks expect to be rescued, they have an incentive to take excessive risk. The Diamond-Dybvig model highlights the fundamental trade-off in financial regulation: policies that eliminate runs also create the conditions for excessive risk-taking, which makes the system vulnerable to a different kind of crisis.

## Extensions: sunspots, global games, and information-based runs

The original Diamond-Dybvig model leaves the selection between the good equilibrium and the run equilibrium unexplained. Subsequent work has addressed this gap in two main ways.

The **sunspot** approach interprets the shift from the good equilibrium to the run equilibrium as driven by an extrinsic random variable, a "sunspot," that has no fundamental significance but that serves as a coordination device. If all depositors observe the same sunspot and interpret it as a signal of a forthcoming run, the run becomes self-fulfilling. This interpretation is consistent with the historical observation that bank runs are often triggered by events that, in retrospect, seem trivial relative to the magnitude of the resulting crisis. A headline, a rumor, or the failure of an unrelated institution can serve as a focal point that coordinates depositor beliefs onto the run equilibrium.

The **global games** approach, developed by Carlsson and van Damme (1993) and applied to bank runs by Morris and Shin (1998) and Goldstein and Pauzner (2005), provides a more structural resolution ({cite:t}`GoldsteinPauzner2005`). In a global game, depositors receive private, noisy signals about the bank's fundamental value. When the signal is very good, each depositor knows that the bank is solvent and does not run. When the signal is very bad, each depositor knows the bank is insolvent and runs. For intermediate signals, each depositor must infer the behavior of other depositors from their own signal, and the model generates a unique equilibrium in which the probability of a run depends continuously on the bank's fundamentals. This approach has the attractive feature of preserving the coordination-failure interpretation of Diamond-Dybvig while generating sharper predictions about when runs will occur.

A third extension involves **information-based runs**, where the run is triggered by the arrival of genuine negative information about the bank's asset quality. In this interpretation, the run is not a pure coordination failure but a rational response to news that the bank may be insolvent. The distinction between a "pure" coordination-failure run (Diamond-Dybvig) and an "information-driven" run has important policy implications: deposit insurance can prevent the first type but not the second, because an insolvent bank should be closed rather than rescued. In practice, the two types are difficult to distinguish, because the same event (a decline in asset values, a deterioration in the economic outlook) can both reveal information about insolvency and trigger a coordination failure.

## From individual bank runs to systemic contagion

The Diamond-Dybvig model analyzes a single bank in isolation. Real financial crises involve the simultaneous distress of many institutions, often spreading from one institution to the next. This phenomenon, financial contagion, can operate through several channels.

**Direct balance sheet contagion** occurs through interbank lending and derivative exposures. When bank A fails, bank B (which has lent to bank A or holds securities issued by bank A) suffers losses. If those losses are large enough to impair bank B's solvency or liquidity, bank B may also fail, causing losses at bank C, and so on. The pattern of interbank exposures determines the potential for cascading failures. Allen and Gale (2000) showed that the structure of the interbank network matters: "complete" networks in which every bank is connected to every other bank are more resilient than "incomplete" networks in which banks are connected in chains or clusters, because in complete networks losses are spread widely rather than concentrated ({cite:t}`AllenGale2000`).

**Information contagion** (or the "wake-up call" effect) occurs when the failure of one institution causes depositors or creditors of other institutions to reassess their risk. If bank A fails because of exposure to a particular asset class (say, subprime mortgages), creditors of bank B may wonder whether bank B has similar exposures. Even if bank B is fundamentally sound, the increase in uncertainty can trigger a run or a withdrawal of funding. This channel does not require any direct exposure between the two institutions; it operates through the updating of beliefs.

**Fire-sale contagion** occurs when a distressed institution is forced to sell assets at below-fair-market prices. If other institutions hold similar assets, the fire sale depresses the market value of their portfolios, reducing their capital and potentially triggering further forced sales. This mechanism was analyzed by Shleifer and Vishny (1992) in the context of asset market liquidity, and it was a central feature of the 2007-2009 crisis, during which the forced liquidation of portfolios by distressed institutions drove down asset prices across the board, imposing losses on institutions that were not otherwise exposed to the original source of distress ({cite:t}`ShleiferVishny2011`).

**Common exposure** is sometimes classified separately from contagion proper, though its effects are similar. When many institutions are exposed to the same risk factor (such as the U.S. housing market in the mid-2000s, or the sovereign debt of peripheral European countries in the early 2010s), a single shock can cause widespread distress simultaneously, without any need for direct linkages or fire sales. The clustering of bank failures during the global financial crisis was driven in large part by common exposure to mortgage-related assets, rather than by contagion from one institution to the next.

## Network models of systemic risk

The recognition that the structure of financial interconnections matters for systemic risk has led to the development of network models of the financial system. In these models, financial institutions are represented as nodes in a network, and their exposures to each other are represented as edges. The stability of the system depends on the topology of the network: how many connections each institution has, how concentrated the connections are, and whether there are "hubs" whose failure would cause disproportionate damage.

Early network models, including the Allen-Gale framework mentioned above, established the basic result that diversification is generally stabilizing (spreading exposures widely reduces the impact of any single default) but that extreme diversification can be destabilizing if it creates channels through which a large shock propagates to every institution simultaneously. Acemoglu, Ozdaglar, and Tahbaz-Salehi (2015) formalized this result, showing that densely connected networks are resilient to small shocks (because losses are absorbed by many counterparties) but fragile to large shocks (because the same dense connections transmit the losses to every corner of the system) ({cite:t}`AcemogluOzdaglarTahbazSalehi2015`). The system exhibits a "robust yet fragile" property: it is stable in normal times and catastrophically unstable in extreme times.

These network models have had a significant influence on post-crisis financial regulation. The designation of "systemically important financial institutions" (SIFIs), the development of stress testing frameworks that account for interconnections, and the push for central clearing of derivatives (which replaces a complex web of bilateral exposures with a simpler hub-and-spoke structure centered on a clearinghouse) all reflect the insight that the network structure of the financial system is a first-order determinant of systemic risk.

## Synthesis

The theories surveyed in this subsection and the preceding one (subsection 2.3) provide the microeconomic foundations for understanding financial fragility. Banks are fragile because of maturity transformation. Depositors face a coordination problem that can produce self-fulfilling runs. Adverse selection and moral hazard cause credit markets to ration, freeze, or misprice risk. And the interconnections among institutions create channels through which the failure of one can cause the failure of many.

These mechanisms operate at the level of individual institutions and markets. The next subsection (2.5) shows how they are embedded in macroeconomic models that explain why financial frictions amplify business cycle fluctuations and can turn small shocks into deep recessions.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
