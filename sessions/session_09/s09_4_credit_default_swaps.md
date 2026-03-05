---
title: "9.4 Credit Default Swaps and Synthetic Risk Transfer"
subtitle: Insurance without reserves and the case of AIG
---

Credit default swaps (CDS) were the financial instrument that completed the architecture of the pre-crisis financial system. CDS allowed investors to take on or shed credit risk without buying or selling the underlying bonds, and they created a network of counterparty exposures that connected institutions across the global financial system. The CDS market grew from a notional value of approximately $6 trillion in 2004 to approximately $58 trillion by mid-2007, making it one of the largest financial markets in the world. The market's near-total lack of transparency and regulation would prove to be a critical amplifier of the crisis.

## The mechanics of CDS

A credit default swap is, in economic substance, an insurance contract. The buyer of CDS protection makes periodic premium payments (the "spread") to the seller of protection. In return, the seller agrees to compensate the buyer if a specified "credit event" (typically a default or restructuring) occurs on a specified reference entity (a bond, a loan, or a pool of assets). If no credit event occurs, the seller keeps the premiums. If a credit event occurs, the seller pays the buyer the difference between the face value of the reference asset and its recovery value.

The critical distinction between CDS and traditional insurance is that CDS were not regulated as insurance. The seller was not required to maintain reserves against potential claims, was not subject to insurance regulation, and was not required to hold the reference asset. This meant that anyone could sell CDS protection, including institutions that had no capacity to pay the claims if the credit event occurred. It also meant that anyone could buy CDS protection, even if they did not own the reference asset, creating the possibility of "naked" CDS positions in which the buyer was betting on a default rather than hedging an existing exposure.

## CDS on structured credit products

The application of CDS to mortgage-backed securities and CDOs was the development that connected the CDS market to the housing bubble. CDS on subprime MBS tranches (typically the BBB-rated mezzanine tranches) allowed investors to take synthetic long or short positions on the performance of subprime mortgages. An investor who believed that subprime borrowers would continue to make their payments could sell CDS protection and earn the premium spread. An investor who believed that subprime loans would default could buy CDS protection and earn a large payout if defaults materialized.

The CDS market on subprime MBS was standardized through the **ABX index**, a family of indices launched in January 2006 that tracked the performance of CDS on subprime MBS of different vintages and ratings. The ABX indices provided, for the first time, a liquid and transparent market for pricing subprime credit risk. When the ABX indices began to decline in early 2007, they provided an early and visible signal that the subprime market was deteriorating, well before the losses appeared in the structured credit products themselves.

Critically, CDS allowed the creation of **synthetic CDOs**: CDOs whose underlying assets were not actual mortgages or MBS, but rather CDS contracts referencing MBS. A synthetic CDO could be created without any new mortgages being originated; it was simply a bet between investors on the performance of existing mortgages. The creation of synthetic CDOs dramatically increased the total amount of risk exposure to the subprime market, because there was no limit to the number of CDS contracts that could reference the same underlying pool of mortgages. The total exposure to subprime mortgage risk through synthetic CDOs may have been several times larger than the actual stock of subprime mortgages.

## The case of AIG Financial Products

The most dramatic illustration of the risks created by CDS was the near-collapse of American International Group (AIG), at the time the world's largest insurance company. AIG's subsidiary, AIG Financial Products (AIGFP), had sold CDS protection on approximately $440 billion in notional value of structured credit products, including large positions referencing subprime MBS CDOs.

AIGFP's strategy was based on two assumptions: first, that the CDO tranches it was insuring were AAA-rated and therefore extremely unlikely to default; and second, that AIG's AAA corporate credit rating meant that it would not be required to post collateral against its CDS positions. Both assumptions proved wrong. As the subprime market deteriorated and the value of the referenced CDO tranches declined, AIG's counterparties (primarily the major investment banks) demanded collateral under the terms of the CDS contracts. When AIG's credit rating was downgraded in September 2008, the collateral calls accelerated, and AIG was unable to meet them.

AIG's near-failure threatened the stability of the entire global financial system because its counterparties, the institutions that had purchased CDS protection from AIG, were relying on that protection to hedge their own exposures to mortgage-related assets. If AIG defaulted on its CDS obligations, those institutions would suddenly find themselves unhedged, with enormous direct exposure to the deteriorating mortgage market. The counterparties included virtually every major global bank: Goldman Sachs, Deutsche Bank, Societe Generale, Merrill Lynch, Bank of America, and many others.

The U.S. government's rescue of AIG in September 2008, which eventually totaled approximately $182 billion, was motivated by the fear that AIG's failure would trigger a cascade of losses at its counterparties that could bring down the global banking system. The rescue was enormously controversial, particularly because the CDS counterparties (including Goldman Sachs) were paid in full on their claims, effectively receiving a backdoor bailout at taxpayer expense.

## Systemic implications

The CDS market created systemic risk through several mechanisms. The sheer size of the market (notional values in the tens of trillions of dollars) meant that the potential losses were enormous. The opacity of the market (CDS were traded over-the-counter, with no central clearinghouse and no public reporting of positions) meant that no one, not regulators, not market participants, not even the institutions themselves, could map the network of exposures and identify where the risks were concentrated. And the interconnection created by CDS contracts, in which every institution was both a buyer and a seller of protection, meant that the failure of any major participant would transmit losses to all of its counterparties, which would transmit losses to their counterparties, in a chain reaction that could bring down the entire system.

The CDS market was, in effect, a mechanism for creating the systemic interconnection and counterparty risk that the theoretical literature (subsection 2.4) identifies as a key source of financial fragility. The market grew to its enormous size in the absence of any meaningful regulation, because CDS were classified as neither securities nor insurance and therefore fell outside the jurisdiction of existing regulators. This regulatory gap would be addressed after the crisis by the Dodd-Frank Act's requirement for central clearing of standardized derivatives, but the damage had already been done.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
