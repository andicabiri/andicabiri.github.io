---
title: "Beyond the Multiple #1: Prices Are Not the Same as Values"
date: 2026-03-29
categories: [Beyond the Multiple]
---

In 2013, the Nobel Memorial Prize in Economics was shared by three Americans: Eugene Fama, Lars Peter Hansen, and Robert Shiller. The decision was not without irony. Fama had spent his career arguing that market prices accurately reflect all available information. Shiller had spent his career showing that they don't. The Royal Swedish Academy of Sciences awarded them the prize jointly, noting that collectively their work "laid the foundation for the current understanding of asset prices" — a foundation built, apparently, on a productive disagreement.

The disagreement can be summarized in two characters:

$$P \neq V$$

Price is not the same as value. This is the starting point for everything that follows in this series.

## Why do prices deviate from values?

In a perfectly efficient market, every security's market price $$P$$ would equal its intrinsic value $$V$$ at all times. In practice, three categories of friction prevent this:

- **Direct transaction costs** — the explicit costs of buying and selling: brokerage fees, bid-ask spreads, taxes on capital gains. These create a wedge between the price at which an asset trades and the price at which arbitrage becomes profitable.
- **Indirect transaction costs** — the cost of holding a position until prices converge to values. Even if you are right about a mispricing, you may run out of patience, capital, or both before the market agrees with you. This is not a trivial risk.
- **Information costs** — the time, effort, and resources required to produce a reliable estimate of value in the first place. A biotech company that expenses its R&D and discloses little about its pipeline is far more expensive to analyze than a financial holding company whose assets are marked to market on the balance sheet. Higher information costs mean fewer analysts willing to do the work, which means prices deviate from values for longer.

These three frictions are not just academic categories. They explain why mispricing is most severe in precisely the markets where it is hardest to exploit — illiquid stocks, opaque business models, assets with long convergence horizons.

## The estimation problem

Here is where it gets uncomfortable. Even if we accept that $$P \neq V$$, we cannot directly observe $$V$$. The true intrinsic value of an asset is not a number that appears anywhere. It has to be estimated. Call that estimate $$V_e$$.

This means the apparent mispricing we can actually measure — the gap between our estimated value and the current price — is not the same as the true mispricing. It is the sum of two things:

$$V_e - P = (V - P) + (V_e - V)$$

Where:

- $V - P$ is the true mispricing — what we are trying to identify
- $$V_e - V$$ is our own estimation error — the noise we introduce

In other words, every time an analyst looks at a stock and says "this is cheap," they are making two implicit claims simultaneously: that the market is wrong, and that their own valuation is right. Both claims could be false. Either one could dominate the other.

This has a practical consequence that is easy to state but hard to internalize: the analyst's job is not just to find situations where $$V - P$$ is large. It is also to minimize $$V_e - V$$, because a large estimation error can make a fairly priced asset look mispriced, and a genuinely mispriced asset look fairly priced.

## What drives estimation error?

Three factors determine how large $$V_e - V$$ tends to be:

The first is the **choice of the basis of value** — what you are actually trying to estimate. Intrinsic value, fair market value, and investment value are not the same thing, and confusing them is a common source of error. Intrinsic value is the present value of the cash flows an asset will generate, based on your specific forecasts. Fair market value — formalized in IFRS 13 as "the price that would be received to sell an asset in an orderly transaction between market participants" — is what a hypothetical rational buyer and seller would agree on, regardless of your forecasts. Investment value goes further: it includes the synergies a specific acquirer could extract, which is why M&A buyers routinely pay 20–30% premiums over market prices. The right basis depends entirely on the purpose of the valuation.

The second is the **choice of valuation model**. A dividend discount model applied to a company that doesn't pay dividends, or a liquidation value approach applied to a going concern, will produce estimates that are systematically biased. The model has to be consistent with what you are valuing and why.

The third is the **translation of forecasts into a value figure** — which sounds mechanical but is not. The same set of cash flow projections can produce valuations that differ by 30–40% depending on the assumed terminal growth rate, the length of the explicit forecast period, or the target capital structure used in the discount rate. These are not rounding errors. They are judgment calls, and each one compounds the others.

## A worked example

Consider a share trading at €100. Your fundamental analysis suggests an intrinsic value of €120, which you expect the market to recognize within 12 months. The opportunity cost of capital is 10%. Should you buy?

The naive answer is yes — there is a 20% upside. The correct answer requires accounting for all three types of transaction costs:

| Item | Amount |
|------|--------|
| Purchase price | −€100.00 |
| Purchasing fees (0.5%) | −€0.50 |
| Sale proceeds at €120 | +€120.00 |
| Selling fees (0.5%) | −€0.60 |
| Tax on capital gain (10%) | −€2.00 |
| Cost of fundamental analysis | −€6.00 |
| Opportunity cost (10% × €106.50) | −€10.65 |
| **Net margin** | **+€0.25** |

The investment is barely profitable — and this assumes your estimate of €120 is exactly right. If $$V_e - V$$ is even slightly negative, the trade destroys value.

This is not an argument against active investing. It is an argument for taking estimation error seriously. The margin between a good investment and a bad one is often thinner than it appears, and most of that margin is consumed by costs that analysts either ignore or underestimate.

## The implication

Prices are noisy signals. They contain information — markets are not random — but they are not reliable measures of value, particularly at any given point in time. The empirical evidence is consistent: the P/V ratio of broad market indices oscillates significantly around its long-run mean, with deviations that can persist for years. The internet bubble of the late 1990s was not an anomaly. It was an extreme case of a pattern that repeats in milder form continuously.

The analyst's task, then, is not to trust prices or to ignore them. It is to estimate values carefully, minimize estimation error deliberately, and be honest about the difference between the two.

That gap — between $$V_e$$ and $$V$$ — is where most valuation mistakes live. The rest of this series is about how to make it smaller.
