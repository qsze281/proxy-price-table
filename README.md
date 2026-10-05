# proxy cheap: Where the real low prices are, how to spot the fake ones, and a full price table

Searching for a cheap proxy usually means one of three things: you need a lot of IPs and don't want a monthly bill, you got burned by a $2/GB headline that turned into $40 because of a minimum commitment, or you just want to test one scraping project without signing a contract.

The word "cheap" is where most of the confusion starts. A $0.50 per GB rate is worthless if you have to buy 100 GB up front. A $1 per GB rate is expensive if 60% of your requests get blocked and you pay for all of them. And a rate that looks flat can double the moment you ask for city-level targeting.

So before the numbers, here's the frame that matters.

## Cheap per gigabyte is not the same as cheap per result

Proxy pricing has three multipliers that sit on top of the advertised per-GB rate:

1. **Minimum spend.** A headline rate that requires a 1 TB commit is a rate you can't actually buy.
2. **Traffic expiry.** If unused GBs die at the end of every billing cycle, you paid for bandwidth you never used. That's the most common hidden markup in the industry.
3. **Targeting surcharges.** Country-level routing is normally included. City, ZIP, state, and ASN filtering often costs extra, which changes your math the moment a project needs local pricing data.
4. **Success rate.** Price divided by success rate is your real cost. A cheap pool that gets blocked on half your targets is more expensive than a mid-priced one that works.

That's the whole checklist. If a provider survives all four, it's genuinely cheap. If it fails one, run the numbers again.

## What the market actually charges

Published per-GB rates move constantly, and plan minimums distort them further, so treat these as approximate entry points reported by third parties rather than fixed facts:

| Provider | Residential entry (reported) | Model |
| --- | --- | --- |
| DataImpulse | $1/GB, $5 minimum | Pay-as-you-go, non-expiring |
| Webshare | ~$1.40/GB | Subscription, cheap datacenter plans |
| Decodo | ~$3.50/GB | Monthly plans |
| IPRoyal | ~$7/GB entry, bulk to ~$1.75/GB | Pay-as-you-go + subscriptions |
| Bright Data | from ~$8.40/GB | Enterprise-leaning |
| HProxy | advertises $0.44/GB entry | Pay-as-you-go |

The spread between the top and bottom of that table is roughly twenty-fold for IPs doing the same job. Some of the difference is real (pool quality, sourcing, support, anti-blocking), and some of it is positioning. Bright Data and Oxylabs price for enterprise buyers who need scale and compliance paperwork. Decodo and SOAX sit in the middle with more tooling and friendlier dashboards.

At the bottom, the battle is between pay-as-you-go providers, and that's where the cost model itself starts to matter more than the number.

## Why DataImpulse sits at the bottom of the price ladder

DataImpulse built its network as an internal data-collection tool before selling access, and the pricing reflects that origin: residential traffic starts at **$1 per GB**, datacenter at **$0.50 per GB**, mobile at **$2 per GB**, and premium residential at **$5 per GB**. There's no subscription, and purchased traffic doesn't expire. You top up, you use it whenever the project runs.

Three things make that rate hold up better than most cheap-looking competitors:

**No expiry.** Buy 50 GB, use 8 GB this month, 12 GB the next. Nothing vanishes at a billing reset, which is where a lot of "cheaper" providers quietly claw back the difference.

**A first-party pool.** DataImpulse sources IPs directly through its own opt-in app instead of reselling another network's traffic. In practice that means the 90M+ residential IPs across 195 countries carry less shared abuse history, which usually shows up as fewer blocks on protected targets. TechRadar's review reported consistently high scraping success rates on the residential pool in their hands-on testing, and the company publishes a 99.51% success rate of its own.

**A $5 entry point.** The starter pack is 5 GB for $5 on residential, 10 GB for $5 on datacenter, or 2.5 GB for $5 on mobile. That's a real test budget rather than a demo, and it doesn't expire while you decide.

👉 [Compare all four DataImpulse proxy types and current rates](https://bit.ly/dataimPulse)

## The full plan and price table

Here's the complete published lineup across all four proxy types. Every plan uses the same billing model: pay-as-you-go, non-expiring traffic, no subscription, free country targeting, HTTP(S) and SOCKS5 support.

| Proxy type | Plan | Traffic | Price | Per GB | Notes | Buy |
| --- | --- | --- | --- | --- | --- | --- |
| Residential | Intro | 5 GB | $5 | $1.00 | Rotating + sticky, country targeting | [Start with the 5 GB residential pack](https://bit.ly/dataimPulse) |
| Residential | Basic | 50 GB | $50 | $1.00 | Adds 24/7 human support | [Check the 50 GB residential tier](https://bit.ly/dataimPulse) |
| Residential | Advanced | 1 TB | $800 | $0.80 | Dedicated account manager, custom features | [See the 1 TB residential rate](https://bit.ly/dataimPulse) |
| Residential | Custom+ | 5 TB+ | Custom (from $4,000) | Volume-based | Enterprise terms, 5 TB quoted around $0.70/GB | [Ask about custom residential volume](https://bit.ly/dataimPulse) |
| Datacenter | Intro | 10 GB | $5 | $0.50 | Randomized subnets, 99.9% uptime | [Grab 10 GB of datacenter traffic for $5](https://bit.ly/dataimPulse) |
| Datacenter | Basic | 100 GB | $50 | $0.50 | Same features, bigger bucket | [See the 100 GB datacenter pack](https://bit.ly/dataimPulse) |
| Datacenter | Advanced | 1 TB | $450 | $0.45 | Dedicated account manager | [Check the 1 TB datacenter rate](https://bit.ly/dataimPulse) |
| Datacenter | Custom+ | 5 TB+ | Custom (from $2,250) | Volume-based | Enterprise scale | [Request custom datacenter pricing](https://bit.ly/dataimPulse) |
| Mobile | Intro | 2.5 GB | $5 | $2.00 | 3G/4G/5G/LTE carrier IPs | [Try mobile proxies from $2/GB](https://bit.ly/dataimPulse) |
| Mobile | Basic | 25 GB | $50 | $2.00 | Adds 24/7 support | [See the 25 GB mobile pack](https://bit.ly/dataimPulse) |
| Mobile | Advanced | 1 TB | $1,600 | $1.60 | Dedicated account manager | [Check the 1 TB mobile tier](https://bit.ly/dataimPulse) |
| Mobile | Custom+ | 5 TB+ | Custom (from $8,000) | Volume-based | Enterprise configuration | [Ask about custom mobile volume](https://bit.ly/dataimPulse) |
| Premium residential | Intro | 1 GB | $5 | $5.00 | Filtered top-quality IPs, all targeting included | [See the premium residential entry pack](https://bit.ly/dataimPulse) |
| Premium residential | Basic | 10 GB | $50 | $5.00 | Adds 24/7 support | [Check the 10 GB premium pack](https://bit.ly/dataimPulse) |
| Premium residential | Custom+ | 5 TB+ | Custom (from $20,000) | Volume-based | Enterprise, personalized setup | [Request premium residential pricing](https://bit.ly/dataimPulse) |

A few things worth noticing in that table.

The volume discount is real but conservative. Residential drops from $1.00 to $0.80 per GB at 1 TB, and mobile from $2.00 to $1.60. The 1 TB tier is a 20% discount. If you only ever use 20 or 30 GB a month, you'll stay at the entry rate, and that's fine, because the entry rate is already the cheap part.

Datacenter is where the arithmetic gets silly. $0.50 per GB with 20M+ IPs, sub-100ms response times, and IPs you can hold for up to 30 minutes. For scanning public directories, checking pricing pages, or any target without serious bot detection, paying residential rates for that work is just money on the floor.

Mobile is the one tier where "cheap" needs context. $2 per GB is low for carrier IPs, where $5 to $15 per GB is normal, but mobile traffic only makes sense on targets that fingerprint devices: app APIs, Instagram, TikTok, and platform work where an LTE fingerprint matters. If your job works fine on residential, $2/GB is $1/GB more than you needed to spend.

## Same volume, same job: what the price gap looks like

Per-GB rates are abstract. Here's what they cost at the volumes people actually buy, using the published rates above. Plan minimums and subscription structures will shift these numbers, so treat it as a direction rather than a quote.

| Need | DataImpulse | At ~$3.50/GB | At ~$8.40/GB |
| --- | --- | --- | --- |
| 10 GB residential | $10 | $35 | $84 |
| 50 GB residential | $50 | $175 | $420 |
| 1 TB residential | $800 | $3,500 | $8,400 |
| 100 GB datacenter | $50 | varies by plan | varies by plan |

For a low-volume scraper pulling 10 GB a month, the difference between the cheapest tier and a mid-market provider is $25. For anyone running a terabyte, it's a few thousand dollars, which is why the "cheap" question tends to split into two very different conversations.

## Where the cheap price can bite you

An honest read of the setup means naming the tradeoffs, not just the rate card.

**Advanced targeting on residential costs double.** Country targeting is included in the base rate. State, city, ZIP, and ASN filtering on residential is billed at 2× the standard per-GB rate, so a project that needs ZIP-level accuracy effectively runs at $2/GB, not $1. Datacenter plans list the finer targeting options as included, but AIMultiple flagged this as something worth confirming with support before you budget on it, and that's reasonable advice.

**There's no managed scraping API.** DataImpulse sells raw proxy connections for people who write their own code. You handle requests, parsing, retries, and CAPTCHA logic yourself. If what you actually want is an unblocking API where you send a URL and get HTML back, this isn't that product.

**No free trial.** The $5 starter is the entry point. There is a 7-day money-back option on Intro plans for card payments, conditional on having used less than 80% of the traffic, and crypto purchases on Intro plans aren't refundable. Read that condition before assuming you can burn through 5 GB and ask for a refund.

**Mobile and premium discounts start late.** Both only get cheaper at the 1 TB tier, so the smaller packs stay at their entry rates.

**Concurrency caps at 2,000 threads** by default, with higher limits available on request.

None of those are dealbreakers, but they're the difference between $1/GB as a marketing number and $1/GB as your actual bill.

## How to start cheaply without wasting a pack

The mistake people make with cheap proxies is buying 100 GB, discovering the pool gets blocked on their specific targets, and then comparing providers by headline rate instead of by result. The order that works better:

1. **Pick the cheapest tier that could plausibly do the job.** Datacenter first at $0.50/GB, residential at $1/GB for defended targets, mobile only if device fingerprinting is the blocker.
2. **Buy the smallest pack.** 10 GB of datacenter or 5 GB of residential for $5 is enough to run a real test, and because the traffic doesn't expire, a partial test isn't wasted money.
3. **Test against your actual targets.** Not a generic IP-checker page. The sites you plan to scrape, with your scripts, your request rate, and your session settings.
4. **Measure cost per successful request.** Price divided by success rate. On a 70% success rate, a $1/GB pool behaves like $1.43/GB. That number tells you more than any rate card.
5. **Scale on actual usage.** The 1 TB residential rate of $0.80/GB is there when you need it, and there's no penalty for not getting there.

Rotating connections run on port 823 for HTTP(S) and 824 for SOCKS5, sticky sessions stay on one IP for 1 to 120 minutes with 30 minutes as the default, and country targeting is a username parameter rather than a dashboard click. Setup is credential-based, so Python, cURL, Puppeteer, Playwright, and anti-detect browsers all work with the standard examples in the docs.

👉 [Run a real test with 5 GB of non-expiring residential traffic](https://bit.ly/dataimPulse)

## FAQ

**What's the cheapest residential proxy per GB right now?**

Among providers that publish their rates and don't require a volume commitment, DataImpulse sits at $1/GB for residential, $0.50/GB for datacenter, and $2/GB for mobile, with a $5 minimum. Some newer providers advertise lower entry rates, and bulk commitments elsewhere can beat the entry number, so the honest answer is that $1/GB is the floor among established pay-as-you-go options, not the absolute cheapest number in existence.

**Is there a free trial?**

No. The cheapest way in is the $5 starter pack across all four proxy types. Intro plans carry a 7-day money-back option for card payments if you've used under 80% of the traffic, and crypto purchases on Intro plans aren't refundable.

**Does the traffic expire if I don't use it?**

Not at DataImpulse, which is the main reason its effective cost tends to be lower than subscription competitors with similar per-GB rates. Unused gigabytes sit in your account until a script consumes them. Subscription providers typically zero out unused bandwidth every billing cycle.

**Is a cheap proxy safe to use?**

The risk isn't the price, it's the sourcing. Providers that resell third-party pools inherit all the abuse history attached to those IPs, which is why the block rates are higher. DataImpulse sells first-party pool access sourced through an opt-in app, holds ISO certification, and states GDPR compliance for its sourcing model. Free proxy lists are a different category entirely and usually cost you your traffic, not just your time.

**How much traffic do I actually need to start?**

Lower than most people assume. Plain HTML fetches typically run in the tens to low hundreds of kilobytes each, so a few gigabytes covers thousands of requests. Pages heavy with JavaScript, images, or video cost far more per fetch, and it's worth logging your own average early rather than guessing. Start with the smallest pack, measure, then decide whether 50 GB or 1 TB is the right next step.

👉 [Check every DataImpulse plan and current per-GB rate](https://bit.ly/dataimPulse)

Cheap proxies aren't hard to find. Cheap proxies that survive contact with your actual targets, don't expire your unused balance, and don't double your bill the moment you ask for a city name in the targeting string are a shorter list. Check the minimum, check the expiry, check the targeting surcharge, and check the success rate on your own traffic. Everything else is brochure copy.
