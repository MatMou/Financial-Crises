---
title: "1.2 Types of Financial Crises"
subtitle: Banking, currency, sovereign debt, twin, and triple crises
---

In subsection 1.1, we established the conceptual distinction between economic crises and financial crises. But the category "financial crisis" is itself very broad. A bank run in 19th century England, a currency collapse in 1990s Asia, and a sovereign default in Latin America are all financial crises, but they involve different institutions, different mechanisms, and different policy responses.

The academic literature has converged on a standard taxonomy that distinguishes five main types of financial crises: banking crises, currency crises, sovereign debt crises, twin crises, and triple crises. This subsection presents each type in detail. For each, we discuss the definition, the identification criteria used in the major databases, the core economic mechanism, and an illustrative historical example.

## Banking crises

### Definition

A **systemic banking crisis** is an episode in which a significant portion of a country's banking system becomes insolvent or illiquid, resulting in widespread bank failures, bank runs, or large-scale government interventions to prevent the collapse of the banking sector.

The word "systemic" is important. Individual bank failures happen regularly and are a normal part of a market economy. A systemic banking crisis is different: it involves the banking system as a whole, or at least a significant share of it, and it threatens the ability of the financial system to perform its basic intermediation and payment functions.

### Identification criteria

The most widely used identification methodology is that of {cite:t}`LaevenValencia2020`, who define the start of a systemic banking crisis as a year in which two conditions are simultaneously met. First, there must be **significant signs of financial distress** in the banking system. These signs include bank runs, large losses in the banking system, and bank liquidations. Second, there must be **significant banking policy interventions** in response to the losses. The policy interventions they track include deposit freezes, bank nationalizations, bank restructuring through the creation of asset management companies, significant bank recapitalizations using government funds, and the extension of blanket guarantees to depositors and creditors.

The requirement that both conditions be met simultaneously is deliberate. Financial distress alone is not sufficient, because minor episodes of bank stress occur frequently and do not rise to the level of a systemic crisis. Policy interventions alone are also not sufficient, because governments sometimes intervene preemptively before significant distress materializes. The combination of both conditions is what identifies a genuinely systemic episode.

The Reinhart and Rogoff dataset ({cite:t}`Reinhart2009`) uses a somewhat broader definition. They identify a banking crisis when one of two events occurs: either bank runs that lead to the closure, merging, or government takeover of one or more financial institutions, or the closure, merging, takeover, or government assistance of an important financial institution that marks the start of a string of similar outcomes for other institutions. Their dataset extends much further back in time (to 1800 for many countries), but at the cost of somewhat less systematic identification criteria.

### The core mechanism

The fundamental fragility of banks arises from the mismatch between their assets and liabilities. Banks fund themselves primarily with short-term deposits (which can be withdrawn on demand) and invest in long-term, illiquid loans (which cannot be called in quickly). This **maturity mismatch** means that banks are inherently vulnerable to runs: if enough depositors withdraw at the same time, the bank cannot liquidate its assets fast enough to pay everyone, even if the underlying loans are sound.

{cite:t}`DiamondDybvig1983` formalized this insight in what has become the canonical model of bank runs. In their framework, a bank run is a coordination failure with multiple equilibria. In the "good" equilibrium, depositors trust that the bank is solvent, leave their deposits in place, and the bank functions normally. In the "bad" equilibrium, depositors fear that other depositors will withdraw, so they rush to withdraw first, and the resulting run forces the bank into insolvency. The run is self-fulfilling: the bank was solvent before the run started, but the run itself causes insolvency by forcing the premature liquidation of assets at fire-sale prices.

In practice, systemic banking crises are rarely caused by pure coordination failures of the Diamond-Dybvig type. They are more commonly the result of a period of excessive lending and risk-taking during a credit boom. When the boom ends, borrowers default, the value of banks' loan portfolios declines, and banks' capital is eroded. If the losses are large enough, banks become insolvent in a fundamental sense (not just because of a coordination failure), and the crisis follows.

The distinction between illiquidity (the bank cannot meet short-term obligations even though its assets are worth more than its liabilities) and insolvency (the bank's liabilities exceed its assets) is critical for policy. A liquidity crisis can be resolved by central bank lending (the lender of last resort function). An insolvency crisis requires recapitalization, restructuring, or resolution. Misdiagnosing an insolvency problem as a liquidity problem, or vice versa, leads to costly policy errors. This distinction will be a recurring theme in the course.

### Illustrative example: the Nordic banking crisis (1991-1995)

In the late 1980s, Finland, Norway, and Sweden experienced a rapid credit boom following financial deregulation. Banks expanded lending aggressively, particularly to the real estate sector. When asset prices collapsed in the early 1990s, banks suffered massive losses. In Finland, bank losses amounted to roughly 8% of GDP. In Sweden, the two largest banks required government support. Norway had already experienced significant bank failures starting in 1988.

The Nordic crisis is often cited as a relatively well-managed episode. The Swedish government responded with a blanket guarantee of all bank liabilities, established a bank restructuring agency, and forced losses on shareholders while protecting depositors and creditors. This approach became a model for subsequent crisis management, although it was not without controversy. The key lesson from the Nordic experience is that financial deregulation, when it is not accompanied by adequate supervision and prudential regulation, can set the stage for a severe banking crisis even in advanced economies with strong institutions.

## Currency crises

### Definition

A **currency crisis** is a sharp, sudden depreciation of a country's currency. In a fixed exchange rate regime, it takes the form of a speculative attack that forces the abandonment of the peg. In a flexible exchange rate regime, it takes the form of a rapid and disorderly decline in the value of the currency.

### Identification criteria

The standard quantitative definition, introduced by {cite:t}`FrankelRose1996`, identifies a currency crisis as a nominal depreciation of the currency of at least 25% against the U.S. dollar that is also at least 10 percentage points greater than the rate of depreciation in the previous year. The second condition is designed to filter out countries that experience persistently high but stable rates of depreciation (as in chronic high-inflation economies), which are not "crises" in the usual sense.

{cite:t}`LaevenValencia2020` use a similar approach, defining a currency crisis as a nominal depreciation of at least 30% that is also at least 10 percentage points higher than the depreciation in the preceding year. The slightly higher threshold reflects a preference for capturing only severe episodes.

An alternative approach, used by Eichengreen, Rose, and Wyplosz (1995), constructs an **exchange market pressure index** that combines changes in the exchange rate, changes in foreign exchange reserves, and changes in interest rates. A crisis is identified when this index exceeds a certain threshold (typically two standard deviations above the mean). This approach has the advantage of capturing episodes where the authorities successfully defend the peg through reserve depletion or interest rate hikes without an actual depreciation, which would be missed by a depreciation-based definition.

### The core mechanism: three generations of models

The theoretical literature on currency crises has evolved through three "generations" of models, each motivated by a different set of crisis experiences.

**First-generation models** were introduced by {cite:t}`Krugman1979` and formalized by Flood and Garber (1984). These models explain currency crises as the inevitable consequence of inconsistent macroeconomic policies. A government runs a fiscal deficit that is financed by money creation (seignorage). Under a fixed exchange rate, this monetary expansion is inconsistent with the peg: as domestic credit expands, the central bank gradually loses foreign exchange reserves to maintain the fixed rate. Rational speculators, anticipating that reserves will eventually be exhausted, launch a speculative attack before they actually run out, forcing an abrupt devaluation. In this framework, the crisis is entirely predictable and the speculators are simply responding rationally to an unsustainable policy. The crises in Mexico (1973-1982) and Argentina (1978-1981) are classic illustrations of the first-generation mechanism.

**Second-generation models** were developed by Obstfeld (1994, 1996) in response to the European Exchange Rate Mechanism (ERM) crisis of 1992. In the ERM crisis, countries like the United Kingdom and Italy were not running the kind of obviously unsustainable fiscal policies described by first-generation models. Their exchange rate pegs were under pressure because of a conflict between the fixed exchange rate and domestic macroeconomic objectives: maintaining the peg required high interest rates at a time when the domestic economy was weak. Obstfeld showed that in this setting, currency crises can be **self-fulfilling**. If speculators believe that the government will abandon the peg, they attack the currency. Defending the peg becomes more costly (requiring even higher interest rates), which makes the government more likely to abandon it. The attack thus validates itself. Crucially, second-generation models feature **multiple equilibria**: the same set of economic fundamentals can be consistent with either a successful defense of the peg or a speculative attack and devaluation. Whether a crisis occurs depends on expectations and coordination among speculators.

**Third-generation models** emerged after the Asian financial crisis of 1997-1998. The Asian crisis did not fit neatly into either first-generation or second-generation frameworks. The affected countries (Thailand, Indonesia, South Korea) did not have large fiscal deficits, and the crisis did not seem driven by a conflict between the exchange rate and domestic monetary policy. Instead, the crisis appeared to involve a combination of private-sector balance sheet vulnerabilities, sudden capital flow reversals, and contagion across countries. Third-generation models, developed by Krugman (1999), Chang and Velasco (1999), and others, emphasize the role of private-sector balance sheets, particularly the **currency mismatch** problem: firms and banks that borrow in foreign currency but earn revenue in domestic currency. When the domestic currency depreciates, the real burden of foreign-currency debt increases sharply, pushing firms and banks into insolvency. This balance-sheet effect creates a vicious circle: the depreciation causes insolvency, which causes capital flight, which deepens the depreciation.

### Illustrative example: the ERM crisis (1992)

In September 1992, the European Exchange Rate Mechanism came under intense speculative pressure. The United Kingdom had joined the ERM in 1990 at what many considered an overvalued exchange rate. By 1992, the British economy was in recession, and maintaining the peg required interest rates that were painfully high for the domestic economy. George Soros and other speculators bet heavily against the pound, selling pounds and buying Deutsche marks. On September 16, 1992 (later known as "Black Wednesday"), the Bank of England spent billions of pounds in foreign exchange reserves and raised interest rates twice in a single day, but was unable to defend the peg. The pound was withdrawn from the ERM and depreciated sharply. Italy followed the same day.

The ERM crisis is the textbook case for second-generation models. The UK government's policy fundamentals were not obviously unsustainable in the first-generation sense, but the conflict between the exchange rate commitment and domestic economic conditions created a vulnerability that speculators could exploit. Interestingly, the post-crisis outcome was favorable for the UK economy: freed from the constraint of the exchange rate peg, the Bank of England was able to lower interest rates, and the economy recovered relatively quickly.

## Sovereign debt crises

### Definition

A **sovereign debt crisis** occurs when a government defaults on its debt obligations (fails to make a scheduled interest or principal payment) or restructures its debt on terms that are significantly less favorable to creditors than the original contract. The default can be on external debt (denominated in foreign currency and owed to foreign creditors), domestic debt (denominated in local currency and owed to domestic creditors), or both.

### Identification criteria

{cite:t}`Reinhart2009` identify a sovereign external default as "the failure of a government to meet a principal or interest payment on the due date." They also include episodes where the debt is rescheduled on terms less favorable to creditors than the original terms, even if the government does not technically miss a payment. For domestic debt, they use a broader definition that also includes the forcible conversion of foreign-currency deposits into local currency at below-market rates and the freezing of bank deposits.

{cite:t}`LaevenValencia2020` define a sovereign debt crisis as a sovereign default or restructuring, as identified by Standard & Poor's or by the presence of an IMF program with access above 100% of the country's quota. They track sovereign debt crises alongside banking crises and currency crises to study the sequencing and interaction between different types.

An important distinction is between **outright default** (the government simply stops paying) and **debt restructuring** (the government negotiates with creditors to change the terms of the debt). Restructurings can involve extensions of maturity, reductions in the coupon rate, or reductions in the face value of the debt (a "haircut"). The Greek debt restructuring of 2012, which imposed a haircut of approximately 53.5% on private bondholders, is the largest sovereign debt restructuring in history by face value.

### The core mechanism

Sovereign defaults differ from corporate defaults in a fundamental way. When a corporation defaults, creditors can seize its assets through bankruptcy proceedings. When a sovereign defaults, there is no equivalent enforcement mechanism. A government cannot be forced into liquidation, and its assets (tax revenues, natural resources, infrastructure) cannot easily be seized by foreign creditors. This means that sovereign lending is sustained not by collateral but by the borrower's **willingness** to pay, which in turn depends on the costs of default.

{cite:t}`EatonGersovitz1981` formalized this idea in a model where a sovereign borrows from international capital markets and can choose to default at any time. The cost of default is exclusion from future borrowing (loss of access to international capital markets). In equilibrium, the sovereign repays its debts as long as the cost of continued debt service is less than the cost of being shut out of capital markets. Default occurs when the debt burden becomes so large that the costs of repayment exceed the costs of exclusion.

In practice, the costs of sovereign default go beyond market access. Defaults are associated with output contractions, disruptions to the domestic financial system (particularly when banks hold large amounts of government debt), damage to the country's reputation and credit rating, and political costs for the government in power. {cite:t}`ReinhartRogoff2011` show that banking crises often precede or accompany sovereign defaults, suggesting a close link between the two types of crises.

### Illustrative example: the Argentine default (2001)

In the 1990s, Argentina operated a currency board that pegged the peso to the U.S. dollar at a one-to-one rate. The currency board was initially successful in bringing down inflation, but it left Argentina vulnerable to external shocks. When the U.S. dollar appreciated in the late 1990s and commodity prices fell, Argentina's exports became uncompetitive, the economy entered recession, and the fiscal deficit widened. The government borrowed heavily to finance the deficit, and by 2001, the debt burden had become unsustainable.

In December 2001, Argentina defaulted on roughly $95 billion in sovereign debt, the largest sovereign default in history at that time. The default was accompanied by the collapse of the currency board (the peso was devalued and then floated, losing about 70% of its value), a severe banking crisis (a deposit freeze was imposed to prevent bank runs), and a deep economic contraction (GDP fell by about 11% in 2002). The Argentine crisis was thus simultaneously a sovereign debt crisis, a currency crisis, and a banking crisis, illustrating how different crisis types can interact and amplify each other.

## Twin crises

### Definition

A **twin crisis** is the simultaneous or near-simultaneous occurrence of a banking crisis and a currency crisis. The term was introduced by {cite:t}`KaminskyReinhart1999` in their influential study of the interaction between the two types.

### The core mechanism

Kaminsky and Reinhart showed that twin crises are not simply the coincidence of two separate events. The two crises tend to be causally linked, with a common set of antecedents and mutually reinforcing dynamics.

The typical sequence, based on their analysis of 76 currency crises and 26 banking crises in 20 countries between 1970 and 1995, works as follows. The process often begins with **financial liberalization**, which loosens lending standards and allows a rapid expansion of credit. The credit boom fuels a surge in asset prices and an appreciation of the real exchange rate. At some point, the boom reverses: asset prices fall, borrowers default, and the banking system comes under stress. The weakening of the banking system undermines confidence in the currency. At the same time, the central bank faces a conflict between defending the exchange rate (which requires high interest rates) and supporting the banking system (which requires low interest rates and ample liquidity). This conflict is often resolved in favor of abandoning the exchange rate peg, triggering the currency crisis. The resulting depreciation, in turn, deepens the banking crisis through balance-sheet effects (if banks or their borrowers have foreign-currency liabilities).

A key finding of {cite:t}`KaminskyReinhart1999` is that twin crises tend to be **significantly more severe** than either banking crises or currency crises occurring in isolation. The output losses are larger, the fiscal costs are higher, and the recovery takes longer. This is because the two crises reinforce each other: the banking crisis weakens the currency, and the currency crisis deepens the banking problems, creating a vicious circle.

### Illustrative example: the Asian financial crisis (1997-1998)

The Asian financial crisis of 1997-1998 is the canonical example of twin crises in multiple countries simultaneously. Thailand, Indonesia, South Korea, and Malaysia all experienced banking crises and currency crises in close succession. The crisis began in Thailand in July 1997, when the government was forced to abandon the peg of the baht to the U.S. dollar after a speculative attack. The devaluation exposed the extent of currency mismatches in the Thai banking and corporate sectors: firms that had borrowed in U.S. dollars to fund investments in baht-denominated assets found that the real burden of their debt had increased sharply.

The crisis spread rapidly to Indonesia, South Korea, and Malaysia through contagion. In Indonesia, the rupiah lost more than 80% of its value against the dollar, and the banking system effectively collapsed, requiring a massive government recapitalization. In South Korea, several large conglomerates (chaebols) defaulted, and the country required a $58 billion IMF bailout. The Asian crisis demonstrated that twin crises in emerging markets with open capital accounts and significant foreign-currency borrowing can be extraordinarily destructive.

## Triple crises

### Definition

A **triple crisis** is the simultaneous or near-simultaneous occurrence of a banking crisis, a currency crisis, and a sovereign debt crisis. Triple crises are rare but represent the most severe form of financial crisis.

### The core mechanism

Triple crises arise when the feedback loops between banking fragility, exchange rate pressure, and sovereign debt sustainability all activate at the same time. The typical dynamic involves a banking crisis that forces the government to bail out the banking sector, which increases public debt. The rising public debt raises concerns about sovereign creditworthiness, which increases borrowing costs for the government. If the government's debt is denominated in foreign currency, a depreciation of the exchange rate further increases the real debt burden. The rising sovereign risk, in turn, feeds back to the banking system because banks typically hold large amounts of government bonds on their balance sheets. This creates a **triple doom loop** where banking risk, sovereign risk, and currency risk all reinforce each other.

{cite:t}`LaevenValencia2020` find that sovereign debt and currency crises tend to coincide with or follow banking crises, rather than preceding them. This sequencing is consistent with the mechanism described above: the banking crisis comes first, and the fiscal cost of resolving it contributes to the sovereign debt crisis.

### Illustrative example: the Greek crisis (2010-2015)

Greece entered the global financial crisis of 2007-2009 with large fiscal deficits that had been understated in official statistics. In late 2009, the newly elected government revealed that the fiscal deficit was far larger than previously reported (approximately 12.7% of GDP rather than the 3.7% originally stated). This disclosure triggered a sovereign debt crisis: Greek government bond yields spiked, and Greece lost access to international capital markets.

The sovereign debt crisis was tightly linked to a banking crisis. Greek banks held large amounts of Greek government bonds, so the rise in sovereign risk directly eroded their capital. The banking system required multiple rounds of recapitalization using public funds, which further increased public debt. Although Greece is a member of the Eurozone and therefore does not have its own currency, the crisis had strong currency-crisis-like dynamics: the inability to devalue forced the adjustment onto the real economy through "internal devaluation" (wage and price cuts), which deepened the recession. The crisis ultimately required three successive bailout programs from the European Union and the IMF, totaling more than 260 billion euros, and a sovereign debt restructuring in 2012.

## Interactions and overlaps

The five categories described above are analytically useful, but the boundaries between them are often blurred in practice. The Argentine crisis of 2001 combined all three types. The European sovereign debt crisis involved banking crises and sovereign debt crises interacting through the doom loop, with currency-crisis dynamics operating within a monetary union. The Asian crisis of 1997-1998 was primarily a twin crisis but also involved sovereign debt problems in Indonesia.

One of the central messages of this course is that **crises rarely come in pure form**. The most severe episodes involve the interaction of multiple crisis types, and understanding these interactions is essential for both diagnosis and policy response. The Kindleberger-Minsky framework (which we will study in Session 2) provides a useful narrative template for understanding how different types of crises emerge and interact during a single episode.

---

## Readings for this subsection

**Required:**

Laeven, L. and Valencia, F. (2020). Systemic Banking Crises Database II. *IMF Economic Review*, 68(2), 307-361. Sections I-III.

Kaminsky, G. L. and Reinhart, C. M. (1999). The Twin Crises: The Causes of Banking and Balance-of-Payments Problems. *American Economic Review*, 89(3), 473-500.

**Recommended:**

Krugman, P. (1979). A Model of Balance-of-Payments Crises. *Journal of Money, Credit and Banking*, 11(3), 311-325.

Obstfeld, M. (1996). Models of Currency Crises with Self-Fulfilling Features. *European Economic Review*, 40(3-5), 1037-1047.

Diamond, D. W. and Dybvig, P. H. (1983). Bank Runs, Deposit Insurance, and Liquidity. *Journal of Political Economy*, 91(3), 401-419.

Eaton, J. and Gersovitz, M. (1981). Debt with Potential Repudiation: Theoretical and Empirical Analysis. *Review of Economic Studies*, 48(2), 289-309.

Reinhart, C. M. and Rogoff, K. S. (2011). From Financial Crash to Debt Crisis. *American Economic Review*, 101(5), 1676-1706.

Claessens, S. and Kose, M. A. (2013). Financial Crises: Explanations, Types, and Implications. *IMF Working Paper* WP/13/28.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
