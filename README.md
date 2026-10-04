# smartproxy pricing: What You Actually Pay per GB, Every Current Plan, and a Cheaper Per-IP Route

Three different numbers show up when you search for smartproxy pricing. One page says residential starts at $2/GB. Another says the cheapest card is $3.75/GB. A third insists Smartproxy charges $12.50/GB, which hasn't been true for years. All three are describing the same company.

Here's what's going on, what the current rates actually are, and where the per-gigabyte model stops being the cheaper answer.

## Smartproxy is Decodo now, and that's why the prices disagree

Smartproxy rebranded to Decodo. The site footer still reads "decodo.com (formerly smartproxy.com)," existing logins carried over, and the IP pool, dashboard and support team are the same operation. Sources date the switch to 2024 or 2025 depending on who you ask, which is itself a sign of how messy the search results are.

The practical consequence: reviews published under old smartproxy.com URLs still rank, and they quote old rates. Any page telling you residential proxies start at $12.50/GB is selling you a price list from before the rename. The company also keeps a page at decodo.com/smartproxy for people arriving on the old name, which tells you they know the search traffic hasn't caught up.

So if you typed "smartproxy pricing" and landed on Decodo, nothing broke. You're in the right place. It's just a different logo.

## What Smartproxy (Decodo) charges today

Residential rotating proxies are the flagship product and the reason most people search for the price at all. Pricing is per gigabyte, billed as an auto-renewing monthly subscription, and the rate steps down as the plan size grows:

| Plan | Traffic | Rate per GB | Monthly total |
| --- | --- | --- | --- |
| Pay as you go | 1 GB at a time | $4.00 | $4.00/GB |
| Starter | 3 GB | $3.75 | $11.25 |
| Small | 10 GB | $3.50 | $35.00 |
| 25 GB (marked most popular) | 25 GB | $3.25 | $81.25 |
| Growth | 50 GB | $3.00 | $150.00 |
| Pro | 100 GB | $2.75 | $275.00 |
| Scale | 250 GB | $2.50 | $625.00 |
| Enterprise | 1,000 GB | $2.00 | $2,000.00 |

The pricing page also lists a 500 GB step between the 250 GB and 1 TB tiers, and everything above 1 TB goes through a "contact sales" path. All figures are before VAT.

Two details worth noting. The homepage headline "from $2/GB" is real, but that rate lives on the enterprise tier. The cheapest card an ordinary buyer can click is $3.75/GB, an 88% gap between the banner and the checkout. The other detail is the shape of the curve: going from 3 GB to 100 GB, a 33-fold jump in volume, cuts the rate by only about 27%. That curve is friendly to small buyers and noticeably less generous at volume than enterprise providers who halve their rate over the same range.

## Everything else on the same invoice

Residential is only one line item. Decodo's catalogue also includes:

| Product | Billing model | Entry rate | Example tiers |
| --- | --- | --- | --- |
| Residential (rotating) | Per GB, monthly | $3.75/GB self-serve | 3 GB $11.25 up to 1,000 GB $2,000 |
| Static residential (ISP) | Per IP or per GB | from $0.27/IP; $1.30/GB | 3 IPs $9.99; 50 IPs $2.70/IP ($135); 100 IPs $2.60/IP ($260) |
| Datacenter, pay per IP | Per IP | from $0.02/IP | Shared pool, territory-based |
| Datacenter, dedicated | Per IP | from $1.15/IP | 10 IPs $4.70; 100 IPs $35; 1,000 IPs $320 |
| Mobile | Per GB | from $2.25/GB | Same step-down logic as residential |
| Web/SERP/eCommerce API | Per plan, per month | Lite $19 | Basic $49; Standard $99; enterprise custom |
| Site Unblocker | Per 1,000 requests | $0.95 | Managed rotation and CAPTCHA handling |
| Web Scraping API | Per 1,000 requests | $0.09 | Credit-based, free tier with no card |

That breadth is the honest case for Decodo. If you want proxies, a scraping API and an unblocker under one login, it's a stacked platform rather than a proxy vendor.

## Four things on the pricing page that change the real cost

**Bandwidth expires with the billing cycle.** Unused gigabytes don't roll over into next month. You budget for 100 GB, use 70, and the other 30 are gone. Pay-as-you-go avoids that by billing per gigabyte from a wallet balance, but at a fixed $4.00/GB with no volume discount at any size.

**Trial and money-back are mutually exclusive.** The 3-day free trial gives you 100 MB and requires a card. After three days your chosen plan activates automatically unless you cancel. Taking that trial makes you ineligible for the 14-day money-back guarantee, because the refund policy requires that you haven't used a free trial. Both offers are real, and you're effectively choosing between them the moment you click.

**The refund has its own conditions.** First purchase only, request inside 14 calendar days, no more than 20% of traffic used on a regular plan or 10% on enterprise.

**Team seats and volume pricing are gated.** Sub-users beyond your plan's allowance cost $10 each, and custom pricing is only available on larger plans through sales, not self-serve.

## Where per-GB pricing stops making sense

Run the arithmetic on a monthly workload and the model gets uncomfortable.

Say you're pushing 200 GB a month. On Decodo's residential ladder, the closest plans are the 250 GB tier at $625 per month, with unused traffic expiring at the end of the cycle. You're paying for the ceiling whether or not you touch it.

Now look at the same volume on a vendor that sells IPs instead of gigabytes. A 200 GB package on 9Proxy costs $200, and it's valid for 180 days rather than one billing cycle. Push that to 2,000 GB and the rate drops to $0.75/GB, or $1,500 with the same half-year validity. The enterprise GB tiers, 3,000 GB upwards, never expire at all.

That gap isn't a trick, it's a different product. Per-GB vendors meter bandwidth against a pool of rotating IPs. 9Proxy's IP-based plans work the opposite way: you buy a fixed number of residential IPs, bandwidth on those IPs is unlimited while they're active, and unused IPs never expire.

## What 9Proxy actually charges for

9Proxy runs two residential models plus bundles, all managed from one dashboard. The IP-based model gives you individual residential IPs with unlimited traffic; each IP stays live anywhere from a few hours to about 24 hours and needs their desktop app for local port forwarding. The GB-based model bills by traffic, generates unlimited endpoints, and works straight from the dashboard with username/password or IP whitelisting, plus targeting by country, state, city, ZIP and ISP. GB traffic carries a 180-day validity, unlimited for enterprise accounts.

The pool is advertised at 20M+ residential IPs across 90+ countries, which is smaller than Decodo's 115M+ across 195+ locations. Worth knowing whether your targets sit in the long tail of countries, because that's where coverage differences bite.

Pricing was adjusted on June 1, 2026 for IP-based and bundle packages. GB-based prices were left alone, which matters if you're comparing against older review tables still floating around quoting $0.015/IP.

### IP-based packages (unlimited bandwidth per IP)

| Package | Rate per IP | Total |
| --- | --- | --- |
| 100 IPs | $0.24 | $24 |
| 500 IPs | $0.144 | $72 |
| 1,000 + 500 bonus IPs | $0.084 | $126 |
| 2,500 IPs | $0.084 | $210 |
| 5,000 IPs | $0.072 | $360 |
| 15,000 IPs | $0.048 | $720 |
| 25,000 IPs | $0.035 | $863 |
| 50,000 IPs | $0.029 | $1,438 |
| 100,000 IPs (business) | $0.023 | $2,300 |
| 200,000 IPs (business) | $0.021 | $4,140 |
| 500,000 IPs (business) | $0.018 | $8,625 |

[👉 See 9Proxy's IP-based package rates](https://bit.ly/9-Proxy)

IPs are only deducted when a connection is actually established, so setting up a session doesn't burn inventory. Paying in crypto adds a 5% IP bonus.

### GB-based packages

| Package | Rate per GB | Total | Validity |
| --- | --- | --- | --- |
| 5 GB | $3.00 | $15 | 180 days |
| 50 + 5 GB bonus | $2.10 | $105 | 180 days |
| 100 GB | $1.50 | $150 | 180 days |
| 200 GB | $1.00 | $200 | 180 days |
| 1,000 GB | $0.80 | $800 | 180 days |
| 2,000 GB | $0.75 | $1,500 | 180 days |
| 3,000 GB (enterprise) | $0.72 | $2,160 | No expiry |
| 6,000 GB (enterprise) | $0.70 | $4,200 | No expiry |
| 10,000 GB (enterprise) | $0.68 | $6,800 | No expiry |

[👉 Check the current 9Proxy GB package pricing](https://bit.ly/9-Proxy)

Notice the entry point: $15 for 5 GB against $11.25 for 3 GB on Decodo's smallest card. The small end is comparable. Everything above 50 GB is where the two models separate, partly on rate and partly on whether your traffic survives the month.

### Bundle packages (IPs plus bandwidth)

| Bundle | Package | Price |
| --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 |
| Popular | 1,500 IPs + 50 GB | $180 |
| Pro | 5,000 IPs + 500 GB | $720 |

[👉 Compare 9Proxy bundle packages](https://bit.ly/9-Proxy)

Bundles suit mixed workloads where some jobs need the same identity across a session and others just need volume and rotation.

### The one comparison that explains the whole difference

Decodo's closest per-IP product is static ISP: 100 IPs at $2.60 each, or $260 per month. 9Proxy's 5,000 IP package costs $360 total, with unlimited bandwidth on each IP, and unused IPs that never expire.

They aren't identical products, and the differences are the point. Decodo's ISP addresses are static and yours for the billing cycle. 9Proxy's residential IPs live hours to about a day, then you move on, which is why they're cheap and why they suit volume work rather than long-lived fixed identities.

## Which one to pick, by workload

**Small, occasional jobs under 25 GB.** Decodo's $11.25 starter is a straightforward entry, the 3-day trial proves connectivity, and the platform gives you APIs and an unblocker you might grow into.

**High-volume residential scraping on a monthly cadence.** The per-GB subscription model forces you to buy a ceiling and forfeit what you don't use. 9Proxy's IP plans remove the meter entirely, and the GB packs hold their value for six months instead of one cycle.

**Work that needs datacenter, ISP or mobile lines.** Decodo, without much debate. 9Proxy sells residential only, with no datacenter, ISP or mobile products and no managed scraping API.

**Work that needs static addresses for months.** Decodo's ISP tier or its dedicated datacenter IPs. Residential IPs rotating every few hours won't hold a long-lived identity.

**Teams sharing one budget.** 9Proxy's enterprise tier includes team mode with an owner plus up to five members, shared bandwidth that doesn't expire inside the team, per-member traffic controls and activity logs. On Decodo, extra sub-user slots are $10 each.

[👉 Start a 9Proxy account and pick an IP, GB or bundle package](https://bit.ly/9-Proxy)

## What to check before you buy 9Proxy

The cheap rates come with real constraints, and they're easier to plan around than to discover later.

There's no self-serve free trial on the site. Trial IPs have been offered through community channels, including the vendor's own forum posts where they hand out free test IPs depending on availability, but you shouldn't count on a no-cost test the way you can with Decodo's 100 MB.

The refund terms are narrow. Published credit-refund conditions essentially cover IPs that die within about 60 seconds, and 9Proxy's Trustpilot profile carries friction from buyers who couldn't recover spend on an unsuitable purchase. Test small before scaling.

Support for media streaming on IP-based plans is being withdrawn under an updated acceptable use policy, so anyone buying for YouTube or similar platforms should confirm current terms first.

The IP-based model needs a desktop app for local port forwarding. The GB model doesn't, which is one reason cloud and automation setups lean that way.

Coverage is 20M+ IPs across 90+ countries rather than 115M+ across 195+. For mainstream targets that rarely matters. For obscure geographies it does.

## FAQ

**Is Smartproxy the same company as Decodo?**
Yes. Same Lithuanian company, same infrastructure, accounts and support team, new name. Reviews under smartproxy.com URLs describe the same service, though any prices in them predate the current rates.

**Is residential really $2/GB?**
Only at 1,000 GB enterprise volume. The cheapest self-serve card is $3.75/GB, or $11.25 for the 3 GB starter.

**Does Decodo offer a free trial?**
A 3-day trial with 100 MB, card required, no upfront charge, with the chosen plan activating automatically afterwards. Using it disqualifies you from the 14-day money-back guarantee.

**What's the cheapest way to run a lot of residential traffic?**
If your work tolerates IPs that rotate every few hours, per-IP pricing with unlimited bandwidth beats per-GB pricing by a wide margin once you're past the smallest tiers. If you need a fixed identity held for weeks, it doesn't, and you should stay on a static ISP or dedicated plan.
