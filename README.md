# LisaHost review: pricing, residential IP quality, refund policy, and who this China-optimized VPS actually suits

If you searched for a LisaHost review, chances are you already know the basic pitch: a Hong Kong-based VPS provider that sells native and dual-ISP residential IPs across the US, Hong Kong, Japan, Singapore, Taiwan, the UK, Germany, Korea, and Vietnam, with routing optimized for mainland China access. What you probably want to know is whether the network actually performs the way the marketing claims, what the real prices are once you get past the "starting from" numbers, and whether the refund policy and support are trustworthy enough to hand over a payment.

This review pulls together the current official pricing pages, third-party technical benchmarks, and the handful of public customer reviews that exist, so you can make a decision based on what's actually documented rather than repeated marketing copy.

## What LisaHost is actually selling

LisaHost has been operating since 2017, with its base of operations in Hong Kong. Unlike a generic budget VPS shop that just resells whatever IP block a datacenter hands it, LisaHost built its entire catalog around IP sourcing. That means two distinct product families running in parallel across every region: native IP VPS (a clean IP allocated from a regional pool, but still recognizable as a hosting-range address) and dual-ISP residential IP VPS (an address that's registered to a home broadband ISP, so platforms like TikTok, Instagram, or a payment gateway see it as an ordinary home internet connection rather than a server farm).

This distinction actually matters for search intent here. People running TikTok account operations, cross-border e-commerce storefronts, or trying to keep a ChatGPT/Claude session stable from a fixed US or Japanese IP care a lot more about "does this IP look like a real household" than they do about raw CPU benchmarks. LisaHost's whole positioning leans into that gap, backed by routing through premium Chinese carrier paths — CN2 GIA, AS9929, AS4837, and CMI — depending on the region.

Every plan runs on KVM virtualization with NVMe SSD storage (a couple of legacy US plans still use plain SSD), gets provisioned automatically, and ships with a 48-hour no-questions-asked refund window — with one important exception covered further down.

## Full pricing breakdown: LisaHost's annual special lineup

LisaHost consolidates its most cost-effective plans into a single "Annual Special" catalog that spans nearly every region it operates in. This is the section most people searching for a LisaHost review actually care about, since it's where the real value (or lack of it) becomes obvious. All prices below are the official annual list prices in Chinese yuan (CNY), pulled directly from the current pricing page.

| Plan | Region / IP Type | CPU / RAM | Bandwidth | Monthly Traffic | Annual Price | Purchase |
| --- | --- | --- | --- | --- | --- | --- |
| US 9929 Premium – Non-native IP | Los Angeles, standard IP | 1C / 1GB, 10GB SSD | 50Mbps | 200GB | ¥199/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| US 9929 Premium – Native IP | Los Angeles, native IP | 1C / 1GB, 10GB SSD | 50Mbps | 400GB | ¥299/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| US 4837 Dual-ISP Residential | Los Angeles, residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 600GB | ¥399/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| US New York Dual-ISP Residential | New York, residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 600GB | ¥399/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| US Chicago Dual-ISP Residential | Chicago, residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 600GB | ¥399/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Singapore Native IP | Singapore, BGP native IP | 1C / 1GB, 10GB NVMe | 300Mbps | 2000GB | ¥466/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| UK Dual-ISP Residential | UK, BGP residential IP | 1C / 1GB, 10GB NVMe | 300Mbps | 2000GB | ¥466/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Japan Native IP | Japan, China-optimized | 1C / 1GB, 10GB NVMe | 100Mbps | 600GB | ¥499/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| US 9929 Dual-ISP Residential | Los Angeles, residential IP | 1C / 1GB, 10GB NVMe | 50Mbps | 600GB | ¥499/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Germany 9929 Dual-Stack Native | Frankfurt, IPv4+IPv6 | 1C / 1GB, 10GB NVMe | 100Mbps | 600GB | ¥499/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Hong Kong CMI/CU2/CN2 | Hong Kong, ISP-grade IP | 1C / 1GB, 10GB NVMe | 50Mbps | 600GB | ¥566/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Korea Dual-ISP Residential | Korea, residential IP | 1C / 1GB, 10GB NVMe | 50Mbps | 1000GB | ¥699/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Vietnam Dual-ISP Residential | Vietnam, residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 1000GB | ¥699/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Hong Kong iCable Residential | Hong Kong, residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 1000GB | ¥699/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Hong Kong HGC Residential | Hong Kong, residential IP | 1C / 1GB, 10GB NVMe | 50Mbps | 600GB | ¥799/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| US LA Astound Residential VDS* | Los Angeles, home broadband IP | 1C / 1GB, 10GB NVMe | 100Mbps | 1000GB | ¥899/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| US Seattle Atlas Residential VDS* | Seattle, home broadband IP | 1C / 1GB, 10GB NVMe | 100Mbps | 1000GB | ¥899/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Japan ISP Static Residential VDS* | Japan, static residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 1000GB | ¥899/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Japan IIJ Dual-ISP Residential VDS* | Japan, IIJ residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 1000GB | ¥999/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |
| Germany Dual-ISP Residential VDS* | Frankfurt, residential IP | 1C / 1GB, 10GB NVMe | 100Mbps | 1000GB | ¥1099/year | [ View this plan](https://lisahost.com/aff.php?aff=7175&gid=29) |

*Plans marked with an asterisk are flagged by LisaHost as "special products." Refunds on these are issued only as site credit, not back to your original payment method — worth knowing before you commit to a Japan IIJ, Germany residential, or US Astound/Atlas plan.

Beyond this annual catalog, most of these product lines also sell monthly billing with higher-spec tiers. The US 9929 Dual-ISP Residential family, for example, scales from a Lite tier at ¥68/month (1 core, 1GB RAM, 50Mbps) up through Basic (¥88/month), Advanced (¥158/month), and a Deluxe tier at ¥899/month with 4 cores, 4GB RAM, and 8TB of traffic. There are also two unlimited-traffic tiers — Unlimited Lite at ¥498/month (20Mbps cap) and Unlimited Pro at ¥1288/month (50Mbps cap) — for people who'd rather not think about monthly traffic counters at all. The Hong Kong CMI/CU2/CN2 line follows a similar structure, running from ¥88/month up to ¥1988/month for the unlimited Pro tier.

## The coupon code situation

Multiple independent sources — third-party review blogs and coupon aggregator sites that track LisaHost separately from each other — consistently list the same working code: **TS-CBP205DQJE**, good for a recurring 10% discount across the entire catalog. It's described as reusable and carrying over into renewals, and it reportedly stacks with LisaHost's own billing-cycle discounts (roughly 10% off quarterly, 20% off annual, 30% off biennial versus the monthly list price). That would put the cheapest annual entry plan, listed at ¥199/year, down closer to ¥179/year once the code is applied.

That said, coupon codes on any hosting site can rotate or expire without notice, so treat this as "currently reported as working by several sources" rather than a guaranteed price. Enter it at checkout and confirm the discount actually reflects in your order summary before you pay — if it doesn't apply, check LisaHost's own announcements page for whatever code has replaced it.

## Does the network actually perform? What independent tests show

Marketing pages will tell you the network is clean and fast. Independent technical reviews paint a more specific, and more useful, picture. A detailed benchmark of the US New York high-bandwidth plan found genuinely strong disk performance (NVMe-backed 4K random and sequential read/write with no bottlenecks) and excellent connectivity to US and European destinations, with near-zero packet loss on the international backbone. The dual-ISP residential IP did what it's supposed to do: it unlocked mainstream US streaming services and passed as a legitimate residential connection for social media and e-commerce testing.

The same review flagged real limitations, though. Single-core CPU performance is modest — fine for lightweight scraping, proxy work, or running a couple of automation accounts, not something you'd want for compiling code or running a database under load. Return routing to mainland China varied sharply by carrier: China Unicom got the best path, China Telecom saw noticeable peak-hour congestion, and China Mobile traffic was rerouted through the UK, producing high latency and heavy packet loss. Connectivity to other parts of Asia — Japan, Korea, Hong Kong, Taiwan, Southeast Asia — was also weak from that particular US node, which makes sense given it's optimized for US/EU traffic, not Asia-Pacific.

A separate hands-on test of the entry-level US 9929 dual-ISP plan (the ¥68/month Lite tier) reached a similar conclusion: it's a reasonable pick for testing a fixed AI-tool exit point or light SSH/remote work, but the reviewer was explicit that it's "not a performance VPS" and cautioned against assuming residential IP status guarantees permanent platform trust — they recommended running new accounts at low frequency for at least a week before scaling up.

## What actual customers say

Public, verifiable customer feedback on LisaHost is thin. Its Trustpilot profile currently shows only two reviews, and both are one-star. One customer described a refund dispute where money that was supposedly returned automatically to the original payment method instead went missing, requiring manual follow-up to resolve. The other review is a short, blunt accusation of being scammed, without further detail. Two reviews isn't a statistically meaningful sample, but it's also the only independently-hosted, unaffiliated feedback available at the time of writing, and it's worth factoring in — particularly the refund complaint, given that a chunk of LisaHost's own catalog (the "special product" VDS plans listed above) already carries a reduced, site-credit-only refund policy.

Beyond Trustpilot, most of what's published about LisaHost online comes from VPS review blogs and coupon-aggregator sites that also carry their own affiliate links, so treat glowing write-ups (including the more promotional "digital marketing agency" testimonials floating around some blog networks) with the same skepticism you'd apply to any sponsored content.

## Refund policy and support: the fine print that matters

LisaHost's terms of service back up the 48-hour refund promise, but with conditions worth reading before you buy: refunds don't apply to a service that's already used more than 5% of its allocated bandwidth (or 20GB, whichever is smaller), and setup or payment-processing fees are non-refundable. Requests made after the 48-hour window are handled case by case, with no guaranteed outcome. Support runs through a standard ticket system, and the company itself states it doesn't offer any service-level guarantee — disruptions or downtime aren't grounds for compensation under its own terms. None of this is unusual for a budget VPS provider, but it does mean you shouldn't treat the 48-hour window as a long evaluation period; test hard and fast if you're on the fence.

## Who should actually buy LisaHost, and who shouldn't

> If your use case depends on an IP address that looks like a real household — TikTok account management, e-commerce storefronts sensitive to fraud scoring, or keeping an AI tool session tied to one location — the dual-ISP residential lines are the reason to consider LisaHost at all. If you just need a fast, general-purpose VPS with strong CPU and no particular IP requirements, cheaper mainstream providers will likely serve you better.

People running social media operations across multiple accounts, cross-border e-commerce targeting US or Asian markets, or anyone trying to keep streaming and AI-tool access stable from a specific region are the clearest fit. The China-optimized routing on the US 9929/4837, Hong Kong CMI, and Japan native IP lines also makes sense for anyone accessing these services regularly from mainland China, where the last-mile connection quality genuinely differs from a plain international BGP route.

On the other hand, if you need heavy CPU for compiling or rendering, consistent low latency across multiple Asian markets from a single US-based node, or documentation and support primarily in English, LisaHost's catalog and service structure aren't really built for that. The bandwidth caps on entry-tier plans (10–50Mbps on several regions) are also a real constraint if you're planning anything beyond light automation or a small website.

## Quick FAQ

**Is LisaHost legitimate?**
It's an operating company with a public pricing page, terms of service, and years of activity since 2017, plus documented third-party technical benchmarks. That said, its public review footprint is small, and the two available Trustpilot reviews raise a specific concern about refund handling — worth weighing against the more favorable technical benchmarks before you commit larger sums.

**What's the cheapest way to try it?**
The ¥199/year non-native US 9929 plan is the lowest committed price point, but if you want to test performance for your specific use case first, the monthly Lite/Basic tiers (from roughly ¥68/month depending on region) let you cancel within 48 hours if it doesn't fit.

**Do the residential IPs guarantee my account won't get flagged?**
No provider can promise that. A residential attribution reduces the chance of automated detection compared to an obvious datacenter IP, but platform enforcement also looks at account behavior, not just IP type.

**Which regions are actually optimized for mainland China access?**
Based on official routing descriptions, the US 9929, US 4837, Hong Kong CMI/CU2/CN2, Hong Kong HGC, Japan native IP, Korea, and Vietnam lines are China-direct optimized. Singapore, Taiwan, UK, and Germany run on standard international BGP routing, and LisaHost itself recommends relaying those through a Hong Kong or Japan node for better performance from China.

## Bottom line

LisaHost's core value proposition holds up under scrutiny for a specific audience: people who need a residential or native IP in a particular country, paired with China-aware routing on a subset of its lines, at prices that undercut most premium "clean IP" competitors. The independent technical reviews back up the network and disk performance claims for US/EU-facing traffic, and the pricing — especially in the annual catalog — is genuinely competitive for what it offers.

Where you should stay cautious is the CPU ceiling on entry plans, the inconsistent China Mobile/Telecom routing depending on region, the "special product" refund carve-outs on several VDS lines, and the very small pool of independent customer reviews, two of which describe a rocky refund experience. If your workload fits squarely into what LisaHost is built for, starting small on a monthly plan and testing your specific platform and routing needs before moving to an annual commitment is the sensible way to find out if it works for you.
