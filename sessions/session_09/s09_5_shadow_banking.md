---
title: "9.5 The Shadow Banking System"
subtitle: Banking without a safety net
---

The financial intermediation that supported the housing boom and the securitization machine occurred largely outside the regulated banking system, in a network of institutions and markets that came to be known as the **shadow banking system**. The shadow banking system performed the same core economic function as the traditional banking system, maturity transformation (borrowing short-term to fund long-term investments), but without the regulatory safeguards that had been erected after the Great Depression to prevent bank runs: deposit insurance, capital requirements, and access to the central bank's lender-of-last-resort facility. When the crisis hit, the shadow banking system proved just as vulnerable to runs as the uninsured banks of the 1930s, and the resulting panic would transmit the crisis from the mortgage market to the entire financial system.

## The architecture of shadow banking

The shadow banking system was not a single institution or market; it was a chain of institutions and instruments that collectively replicated the function of traditional banking.

**Asset-backed commercial paper (ABCP) conduits and structured investment vehicles (SIVs)** were off-balance-sheet entities, typically sponsored by large banks, that purchased long-term assets (primarily mortgage-backed securities and other structured credit products) and funded them by issuing short-term commercial paper (typically maturing in 30-90 days). The ABCP market grew from approximately $650 billion in 2004 to over $1.2 trillion by mid-2007. The conduits and SIVs were performing classic maturity transformation: borrowing short (through commercial paper) and lending long (through MBS holdings). But because they were structured as off-balance-sheet entities, they were not subject to the capital requirements that applied to on-balance-sheet bank assets.

**Repo markets** provided another channel for shadow banking. In a repurchase agreement (repo), a financial institution sells a security to a counterparty with an agreement to repurchase it at a slightly higher price the following day (or within a few days). Repo is economically equivalent to a collateralized short-term loan: the institution borrows cash overnight, pledging the security as collateral. Investment banks relied heavily on repo funding to finance their holdings of MBS, CDOs, and other assets. By 2007, the repo market was estimated at approximately $10 trillion.

The vulnerability of repo funding to runs was analyzed by Gary Gorton, who described the repo market as a form of banking in which the collateral (the securities pledged in the repo transaction) served the same function as deposit insurance: it provided the lender with assurance that its funds were safe ({cite:t}`Gorton2010`). But unlike deposit insurance, which is a government guarantee that does not depend on the value of any specific asset, repo collateral is only as good as the market value of the underlying security. When the value of the collateral falls (because of losses on the underlying mortgages), the repo lender demands more collateral (a "haircut" increase), or refuses to roll over the repo entirely. The result is a **repo run**, functionally identical to a bank run but occurring in the wholesale funding market rather than at the teller window.

**Money market mutual funds** were the shadow banking system's equivalent of bank deposits. Money market funds invested in short-term instruments (including ABCP and repo) and promised investors a stable net asset value of $1 per share. The promise of a stable NAV made money market funds function like bank accounts: investors treated their money market fund balances as cash, writing checks against them and expecting immediate liquidity. But unlike bank deposits, money market fund shares were not insured by the FDIC. If the fund's investments lost value and the NAV fell below $1 ("breaking the buck"), investors would bear the losses, which created an incentive to withdraw at the first sign of trouble.

**Investment banks** (Goldman Sachs, Morgan Stanley, Merrill Lynch, Lehman Brothers, Bear Stearns) were the hubs of the shadow banking system. They originated and traded the structured credit products, provided the repo financing, sponsored the ABCP conduits, and connected the various components of the system. The investment banks were regulated by the SEC rather than by the banking regulators, and they were not subject to the same capital requirements as commercial banks. In 2004, the SEC relaxed the net capital rule for the five largest investment banks, allowing them to increase their leverage ratios from approximately 12:1 to as high as 33:1. This regulatory change, which was made at the request of the investment banks themselves, would prove catastrophic.

## The vulnerability to runs

The shadow banking system was vulnerable to runs for the same fundamental reason that uninsured banks are vulnerable to runs: it relied on short-term funding to finance long-term, illiquid assets. The Diamond-Dybvig model (subsection 2.4) applies directly. As long as the short-term funders (ABCP investors, repo counterparties, money market fund investors) believed that the underlying assets were safe and that other funders would continue to roll over their funding, the system functioned smoothly. But if confidence was lost, each funder had an incentive to withdraw before the others, because the institution's illiquid assets could not be sold quickly enough to repay all funders simultaneously. The run equilibrium was always available, and it was only the fragile edifice of confidence that kept it from being selected.

The shadow banking system lacked all of the safeguards that had been designed to prevent runs in the traditional banking system. There was no deposit insurance for ABCP or repo or money market fund shares. There were no capital requirements to absorb losses before they reached the short-term funders. And there was no lender of last resort that could provide emergency liquidity to shadow banking institutions facing a run. The Federal Reserve could lend to commercial banks through the discount window, but it had no mechanism (and, initially, no legal authority) to lend to investment banks, ABCP conduits, or money market funds.

When the crisis hit in 2007-2008, the shadow banking system experienced the functional equivalent of the banking panics of the 1930s: a massive, self-reinforcing run in which short-term funders withdrew their capital, forcing institutions to sell assets at fire-sale prices, which depressed asset values, which triggered further withdrawals. The run on the shadow banking system was the central mechanism of the global financial crisis, and the policy response (discussed in Session 10) was largely directed at stopping the run by extending the government safety net to cover the shadow banking system.

---

## References

:::{bibliography}
:filter: docname in docnames
:::
