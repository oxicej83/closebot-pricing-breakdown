# closebot pricing: What Each Plan Costs, What the Message Fees Really Are, and Where the Extra Charges Hide

Type "closebot pricing" into Google and you get three numbers fast: $0, $64, $397. That's the easy part. The harder part is figuring out what those numbers actually cover, because CloseBot splits its pricing into two completely different tracks — one for businesses running their own pipeline, one for agencies reselling AI to clients — and each track bills usage differently.

This breakdown walks through the current plans, the message costs behind them, the add-ons that quietly add up, and the honest answer to "is this worth it for my situation."

## CloseBot's plans at a glance

The pricing page currently shows four options: a free tier, a Core plan that splits into business and agency versions, and a custom Growth tier.

| Plan | Who it's for | Price | Billing | Get started |
| --- | --- | --- | --- | --- |
| **Free** | Testing the agent builder or running very low lead volume | $0, forever | No card required | [Start on the free plan](https://app.closebot.com/a?fpr=li87) |
| **Core — Business** | Companies automating their own lead qualification and booking | From $64/mo, or $53/mo billed as $640/yr | Monthly or annual | [Compare Core business pricing](https://app.closebot.com/a?fpr=li87) |
| **Core — Agency** | Agencies building and re-billing AI agents for clients | $397/mo, or $331/mo billed annually | Monthly or annual | [See the agency plan](https://app.closebot.com/a?fpr=li87) |
| **Growth** | Teams needing SLAs, compliance, audits, or very high volume | Custom quote | Annual/contract with sales | [Request Growth pricing](https://app.closebot.com/a?fpr=li87) |

What each one includes:

- **Free:** 1 agent, 1 user seat, 100 monthly messages, 1 MB of knowledge storage, and unlimited account connections.
- **Core — Business:** message costs included in the base price, 15+ templates (50+ extras unlock on annual plans), human support, plus add-ons for users, storage, and agents.
- **Core — Agency:** unlimited agents, re-billing of all costs, a white-label client portal, 15+ templates, and $5 seats you can mark up.
- **Growth:** HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, and a 50+ template library.

## Business plans bake the message cost in. That's the part worth understanding

Most AI tools quote a subscription and then meter every conversation on top. CloseBot's business track does the opposite: your message allowance is inside the base price.

The starting point is 500 messages a month at $64/mo. If you go over your ceiling, overage is billed at a 2x per-message rate drawn from a wallet — so the ceiling isn't a wall, it's a price signal. You can also raise the ceiling yourself to get a cheaper bulk rate, which is what the slider on the pricing page is for.

One billing detail that catches people out: **1 message is 1 segment, unless you're using the Agent Node with the "unlimited potential" option turned on.** In that mode you're billed on token costs instead, and one message can consume several segments. If you're building heavy agents with a lot of tools and long instructions, budget for more than one segment per reply.

Two other things worth knowing before you compare prices:

- **No bring-your-own API key.** CloseBot handles the model layer itself and treats BYOK as a security risk. That means you can't shave costs by plugging in your own OpenAI or Anthropic key. It also means no surprise API bill — which, depending on your tolerance for surprises, is either a feature or a limitation.
- **Currency is USD**, and billing runs month to month with no contract, so you can upgrade, downgrade, or cancel whenever.

## The Agency plan runs on a rebill model, which changes the maths

$397/mo for the agency track sounds like a lot next to a $64 business plan until you look at what it's built to do: you charge clients, CloseBot charges you $0.012 per message, and the difference is yours.

That's the whole pitch. Agencies set their own markup on messages, seats, and storage, and clients top up a wallet that pays you through your Stripe account rather than paying CloseBot directly. The $0.012 per message is a flat published rate, and it's rebillable in full.

Here's the arithmetic, not a promise: 5,000 client messages a month costs you $60 at $0.012. Rebill those at $0.05 and the same volume bills out at $250. Whatever you charge above cost is margin. CloseBot's own marketing materials claim agencies bill anywhere from $100 a month to five figures per client — those are vendor figures describing what some agencies reportedly charge, not a guarantee of what you'll get away with.

The agency plan also includes the white-label client portal, unlimited agents, and the ability to add seats at $5 each (again, markable up). Notice what's not included: storage add-ons and additional agents beyond the base are extra.

If your whole reason for buying CloseBot is selling AI services under your own brand, the agency track is the one that makes that possible. The business plan doesn't expose re-billing or white-labeling, even during the 7-day trial, so if you want to test the reseller workflow, start the trial on the agency side.

## The business plan price climbs with volume

Because message costs are included, the Core business price scales with your monthly AI replies. The documented entry points look like this:

| Monthly messages included | Core business price (billed monthly) |
| --- | --- |
| 500 | $64/mo |
| 1,000 | $84/mo |
| 2,000 | $109/mo |
| 5,000 | $176/mo |

Past 5,000 the slider keeps going — 20K, 50K, 100K, and 100K+ — with the price rising into the hundreds and beyond. If your business plan crosses into that range, it's worth running the agency-track numbers too, because at high volume the re-billable $0.012 rate can work out better even before you resell anything.

## Annual billing is the discount that actually exists

CloseBot doesn't advertise coupon codes. What it does offer is annual pricing at ten months for twelve:

- **Core Business:** $64/mo monthly versus $53/mo billed as $640/yr.
- **Core Agency:** $397/mo monthly versus $331/mo billed annually.

That's roughly 17% off, plus a side benefit — the 50-template bonus library is available on annual plans only. Both tracks still start with a 7-day trial before you're charged.

Coupon codes floating around third-party coupon sites and affiliate marketplaces should be treated as unverified. Some list codes promising $100 off or a percentage discount, but there's no way to confirm from the official pricing page that they'll apply at checkout. Test any code before you assume it works, and don't pick a plan because of a code you haven't validated.

## The charges that aren't on the headline price

Four costs show up after the subscription:

**Extra user seats.** $5 per user on both paid tracks. On the agency plan that's a resale line as well as a cost.

**Knowledge storage above 1 MB.** The base allocation is 1 MB of text, which is roughly 1,000 pages. If your agent needs to pull from a large knowledge library, storage add-ons are priced by volume — cheaper per MB the more you take.

**Additional agents.** One agent can serve unlimited accounts within a single niche, so most agencies don't need many. If you're covering multiple industries with separate agents, expect extra cost per agent.

**Overage.** On the free plan, messages past 100 cost $0.08 each. On business plans, the 2x overage rate kicks in from your wallet. The ceiling keeps the base price low; the overage keeps you honest.

And the biggest one: **the CRM underneath.** CloseBot doesn't connect to Instagram, WhatsApp, or Messenger directly. It answers the text-based channels inside your CRM — HighLevel, HubSpot, LeadConnector, or a custom system. If you already pay for a CRM, that's a cost you've absorbed. If you don't have one, CloseBot isn't a standalone purchase, and the CRM subscription becomes part of the real total.

For context, CloseBot's own published comparison puts HighLevel's conversational AI at $0.02 per message on pay-per-use, or $97 per sub-account per month for the unlimited AI Employee plan. That comparison comes from CloseBot, so read it as a vendor's argument, not a neutral audit — but the $0.012 versus $0.02 per-message gap is the number agencies keep coming back to.

## Free plan and trial: what you can actually do before paying

Two things cover the evaluation stage:

1. **A free-forever plan** capped at 100 messages a month. The accounts on it can connect unlimited sub-accounts, but you get one agent, one seat, and 1 MB of storage.
2. **A 7-day trial of any paid plan** before billing starts.

There are no refunds. CloseBot says so plainly, which makes the trial the only risk-free window you get. Use it on real conversations rather than demo scripts — the quality gap between tools in this category shows up on messy leads, not on the happy path.

If you want to see how the free tier behaves against your actual traffic before committing, 👉 [you can spin up a CloseBot account here](https://app.closebot.com/a?fpr=li87) without a credit card.

## Which plan fits which situation

The pricing question is really an architecture question.

**Pick the free plan** if you're curious whether an agent can handle your lead types at all, or if you run one simple flow and a handful of conversations a month. 100 messages goes further than it sounds for a low-volume local business.

**Pick Core — Business** if you're running a company pipeline (real estate, home services, coaching, clinics) and want predictable costs without metering. $64/mo with 500 messages included is the cheapest paid entry, and the volume ladder stays reasonable through 5,000 messages. If your lead flow is spiky, the wallet-based overage protection saves you from a surprise invoice.

**Pick Core — Agency** if your business model is selling AI setting to clients. The $397/mo only makes sense if you're re-billing, and it stops making sense fast if you're not. The moment you're managing a handful of client accounts and charging for usage, the plan pays for itself — that's the design, not a coincidence.

**Talk to sales about Growth** if you're in a regulated industry, need HIPAA coverage, quarterly audits, an SLA, or you're processing enough volume that a custom agreement beats list pricing.

## What buyers actually report

On G2, CloseBot shows a 4.8-star average across 191 reviews — a legitimately high score for this category, though review averages in SaaS skew positive because unhappy users tend to churn quietly.

Reddit's GoHighLevel community is more mixed. The recurring positive note is that CloseBot's conversational booking and rescheduling run noticeably better than HighLevel's native AI. The recurring complaint is reliability in testing versus live use — at least one thread describes the idea as good while calling the testing and live experience unreliable. Both threads I looked at were discussing the same core trade-off: you're paying for conversation quality and reliability, and when it holds, it's a clear upgrade over a general-purpose CRM chatbot.

Neither set of signals tells you whether it fits your lead volume. That depends on your numbers, not the average score.

## The short version

CloseBot's pricing isn't complicated once you split it in two. Businesses pay $64 a month and up with messages included; agencies pay $397 (or $331 annually) and rebill messages at $0.012 for margin. The free plan is genuinely usable for low volume, the 7-day trial is where you should do your real testing, and annual billing is the only discount you can count on.

Before you buy, work out two numbers: your monthly message volume and whether you already pay for the CRM CloseBot will sit on top of. Those two answers pick the plan for you faster than any feature comparison.

If you'd rather see the current numbers and the volume slider side by side, 👉 [the plans page lays the full breakdown out here](https://app.closebot.com/a?fpr=li87), and you can start on the free tier to test your own conversations before spending anything.

## FAQ

**Does CloseBot have a free plan?**
Yes. It's free forever as long as you stay at or under 100 messages a month, and it includes one agent, one user seat, 1 MB of storage, and unlimited account connections. Messages beyond 100 cost $0.08 each.

**How much does CloseBot cost per month?**
The free tier is $0. Business plans start at $64/mo with 500 messages included, or $53/mo on annual billing ($640/yr), and rise with volume. The agency plan is $397/mo, or $331/mo billed annually.

**Is there a free trial?**
Yes — 7 days on any paid plan before you're charged. There are no refunds, so the trial is your evaluation window. Plans are month to month, so you can cancel without a contract.

**What happens if I go over my message limit?**
On the free plan you pay $0.08 per message over 100. On business plans, overages are drawn from a wallet at a 2x per-message rate, and you can raise your monthly ceiling beforehand to get a cheaper bulk rate.

**How does the agency plan make money?**
You're billed $0.012 per message and can rebill it to clients at your own markup, the same way you can mark up seats and storage. Clients fund a wallet that pays you through your Stripe account, and the gap between your markup and $0.012 is your margin.
