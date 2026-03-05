---
title: "9.3 Securitization: CDOs, Tranching, and the Alchemy of AAA"
subtitle: How risky mortgages were transformed into apparently safe securities
---

The securitization of subprime mortgages was the central mechanism through which risks that originated in the U.S. housing market were transformed, amplified, and distributed throughout the global financial system. The process involved a series of financial engineering techniques, most importantly **tranching**, that appeared to transform pools of risky mortgages into securities that were overwhelmingly rated AAA, the highest possible credit rating. Understanding how this alchemy worked, and why it failed, is essential for understanding the crisis.

## The basic securitization process

In its simplest form, mortgage securitization involves pooling a large number of individual mortgages into a single portfolio and then issuing securities (bonds) backed by the cash flows from the mortgage pool. The securities, called **mortgage-backed securities** (MBS), entitle the holder to a share of the interest and principal payments made by the borrowers in the pool. The process converts illiquid, individual mortgages into liquid, tradeable securities, which can be sold to a wide range of investors.

The basic MBS structure was not new. Ginnie Mae had been issuing pass-through MBS (in which each security holder received a pro-rata share of the pool's cash flows) since 1970, and Fannie Mae and Freddie Mac had been issuing them since the early 1980s. These "agency" MBS were backed by conforming mortgages (loans that met the GSEs' underwriting standards) and carried the implicit guarantee of the U.S. government, which made them essentially risk-free with respect to credit risk.

What was new in the 2000s was the application of securitization to **non-agency** or **private-label** mortgages: subprime, Alt-A, and jumbo loans that did not meet the GSEs' standards and did not carry a government guarantee. These loans had significantly higher default risk, and the challenge for the securitizers was to find investors willing to buy securities backed by these riskier loans. The solution was tranching.

## Tranching: creating a capital structure

Tranching is the process of dividing the cash flows from a mortgage pool into multiple classes (tranches) with different priorities of payment and different levels of risk. The typical private-label MBS had three broad categories of tranches.

The **senior tranche** (typically 75-85% of the pool) had the first claim on the cash flows. It would receive all scheduled interest and principal payments until it was fully repaid. Losses from defaults in the underlying mortgage pool would not reach the senior tranche until the subordinate tranches had been entirely wiped out. The senior tranche was typically rated AAA.

The **mezzanine tranches** (typically 10-20% of the pool) were subordinate to the senior tranche. They absorbed losses after the equity tranche was exhausted but before the senior tranche was affected. The mezzanine tranches were typically rated from AA down to BBB.

The **equity tranche** (sometimes called the "first loss" piece, typically 2-5% of the pool) absorbed the first losses from defaults. It was unrated and was typically retained by the securitizer or sold to specialized investors.

The logic of tranching is a form of **credit enhancement**: by concentrating the default risk in the subordinate tranches, the senior tranche is protected and can receive a high credit rating. If the underlying pool has an expected loss rate of, say, 5%, then a subordination level of 10% means that the pool would have to lose more than 10% before the senior tranche suffered any loss. If the rating models indicated that a 10% loss was extremely unlikely (based on historical default rates and house price assumptions), the senior tranche could be rated AAA.

## CDOs: the second layer of alchemy

The problem was that the mezzanine tranches of subprime MBS, rated BBB to A, were difficult to sell. Investors who wanted safe assets bought the senior tranches; investors who wanted high returns bought the equity tranches; but few investors wanted the mezzanine tranches, which offered moderate returns for substantial risk.

The solution was the **collateralized debt obligation** (CDO). A CDO pooled together the mezzanine tranches of many different MBS and then applied the same tranching technique a second time. The senior tranche of the CDO, which had first claim on the cash flows from the underlying mezzanine tranches, was typically rated AAA. The CDO thus performed a second round of alchemy: it took BBB-rated securities as inputs and produced AAA-rated securities as outputs.

The mathematics of the CDO depended critically on the assumption of **low default correlation** among the underlying securities. If the mezzanine tranches of different MBS were unlikely to default simultaneously (because they were backed by mortgages from different regions, different originators, and different borrower types), then the probability that enough of them would default to reach the CDO's senior tranche was extremely small. The AAA rating was justified, mathematically, by the diversification benefit of pooling.

This assumption was the Achilles' heel of the entire structure. The models assumed that mortgage defaults across different regions and originators were largely independent, based on the historical experience in which housing downturns had been regional rather than national. But the housing boom of the 2000s was national, driven by nationwide factors (low interest rates, relaxed underwriting standards, the originate-to-distribute model), which meant that when the boom ended, the bust would also be national. Default correlations that the models treated as low would prove to be near-perfect: when house prices fell, they fell everywhere, and the mezzanine tranches of MBS across the entire country suffered losses simultaneously. The diversification that was supposed to protect the CDO's senior tranche proved illusory.

## CDO-squared and the amplification of risk

Some investment banks created **CDO-squared** (CDO²) structures: CDOs whose underlying assets were not mortgages or MBS mezzanine tranches, but rather the mezzanine tranches of other CDOs. The CDO-squared applied the tranching technique a third time, producing yet another set of AAA-rated securities.

CDO-squared structures amplified the sensitivity to the underlying mortgage performance to an extraordinary degree. A small increase in the default rate of the underlying mortgages could wipe out the equity and mezzanine tranches of the original MBS, which would wipe out the equity and mezzanine tranches of the CDO, which would wipe out the equity and mezzanine tranches of the CDO-squared. The senior tranche of the CDO-squared, which was rated AAA, could suffer total losses from a mortgage default rate that was only modestly higher than the rate the models had anticipated. The leverage embedded in the structure was enormous, but it was hidden by the AAA rating.

## The scale of the machine

By 2006, the securitization machine was producing structured credit products at an extraordinary pace. Approximately $1.2 trillion in private-label MBS were issued in 2006 alone. CDO issuance reached approximately $520 billion in 2006. The total stock of outstanding structured credit products (MBS, CDOs, CDO-squareds, and other variants) was measured in trillions of dollars. The products were held by investors around the world: European banks, Asian central banks, U.S. pension funds, insurance companies, and money market mutual funds all held significant quantities of AAA-rated structured credit products.

The global distribution of the securities meant that when the underlying mortgages began to default in 2007, the losses were transmitted instantaneously to financial institutions around the world. The securitization machine had not eliminated risk; it had dispersed risk so widely that no one knew where it was concentrated, which would prove to be a critical source of uncertainty during the panic of 2007-2008.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
