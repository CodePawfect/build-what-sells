![Build What Sells — AI prompts for SaaS ideas, search traffic and UGC videos.](assets/banner.png)

[![Prompts: 3 ready to use](assets/badges/prompts.svg)](#copy-paste-prompts) [![For: solo founders](assets/badges/founders.svg)](#copy-paste-prompts) [![Works with: AI agents](assets/badges/agents.svg)](#what-you-need) [![SEO: DataForSEO](assets/badges/seo.svg)](prompts/seo-demand-validation.md) [![UGC: fal.ai](assets/badges/ugc.svg)](prompts/ugc-video-production.md)

**Three free, ready-to-use AI prompts for solo founders and vibe coders: find SaaS ideas with real demand, check their Google traffic potential, and generate UGC videos for TikTok or Instagram.**

## Copy-paste prompts

Pick the one that solves your current problem:

| Your situation | Grab this prompt | What you get |
|---|---|---|
| **“I don't know what to build.”** | [Find SaaS ideas with real demand →](prompts/opportunity-mining.md) | A ranked shortlist of opportunities backed by recurring problems, existing spending and gaps in current tools, with the top five selected for deeper validation. |
| **“I have an idea. Can Google bring me customers?”** | [Validate organic traffic potential →](prompts/seo-demand-validation.md) | Keyword data, buying intent, competitor results and realistic ranking opportunities, ending in a recommendation on whether SEO is a viable acquisition channel. |
| **“I need videos to market my product.”** | [Create UGC with fal.ai →](prompts/ugc-video-production.md) | Your own UGC-style videos for TikTok or Instagram, with the agent handling creator references, shots, speech, captions and editing through fal.ai. |

### What you need

- **Idea discovery:** a research agent with web access. Adjust the builder profile and excluded ideas in the prompt to your situation.
- **SEO validation:** an agent connected to DataForSEO. Fill in your idea, target market and language.
- **UGC production:** an agent with the fal.ai plugin or API access. Fill in your product, audience and creative brief.

Open a prompt, copy its text block into your agent, and run it. You can use each one independently.

The guide below explains how I use the results to choose an idea, assess distribution and decide what to build.

---

## The guide

- [1. Stop asking AI for SaaS ideas](#1-stop-asking-ai-for-saas-ideas)
- [2. Research anything that survives](#2-research-anything-that-survives)
- [3. If SEO is the plan, validate SEO first](#3-if-seo-is-the-plan-validate-seo-first)
- [4. The numbers I actually care about](#4-the-numbers-i-actually-care-about)
- [5. When I would not build for SEO](#5-when-i-would-not-build-for-seo)
- [6. Build smaller than you want to](#6-build-smaller-than-you-want-to)
- [7. Cheap UGC experiments with fal.ai](#7-cheap-ugc-experiments-with-falai)
- [8. My pre-build checklist](#8-my-pre-build-checklist)

---

## 1. Stop asking AI for SaaS ideas

AI is very good at generating ideas that *sound* reasonable.

That is not the same as finding a real problem.

I would rather find this:

> A Shopify merchant exports a supplier CSV every week, fixes the columns in Excel and imports it again.

than this:

> "Build an AI-powered inventory optimization platform for modern commerce teams."

The first one describes behavior. You can investigate it.

The second one mostly describes a landing page.

### What I look for

I want evidence that people already:

- export and re-import CSV files
- copy data between systems
- keep an ugly spreadsheet alive because existing software does not fit
- build the same report every week
- pay a freelancer or assistant for repetitive work
- buy an expensive product for one feature
- complain about the same workflow in reviews
- combine two or three tools to finish one task
- lost a working process because an API, regulation or platform changed

One complaint is interesting.

Ten unrelated people describing the same workaround is much better.

Someone already paying for the workaround is better again.

### Let the agent search for evidence

This is a good job for a research agent because most of the work is boring:

- forums
- GitHub issues
- Reddit
- support threads
- product reviews
- marketplaces
- Upwork
- Fiverr
- YouTube tutorials
- public spreadsheets and templates
- recent API/platform/regulatory changes

I don't ask the agent to invent a product yet.

I ask it to find repeated pain.

**Prompt:** [Opportunity Mining for Solo SaaS →](prompts/opportunity-mining.md)

---

## 2. Research anything that survives

Once something looks promising, I open a separate research thread for it.

The goal is not:

> prove this is a great idea

The goal is:

> find the reason I should *not* build this

I want the agent to look for:

- who has the problem
- how often it happens
- how painful it really is
- what people use today
- what they already pay
- existing competitors
- good-enough substitutes
- complaints about those substitutes
- switching costs
- technical constraints
- whether a small standalone product has enough value
- possible acquisition channels

Then I do it again for the next promising problem.

Research is cheap now. Use that.

You can investigate 20 candidates without maintaining 20 codebases.

---

## 3. If SEO is the plan, validate SEO first

A lot of small founders want the same thing:

> Build once, rank on Google, get customers without cold outreach.

Fair. I like that model too.

But then Google is not "marketing later."

Google is part of the product decision.

Before I build, I want to know whether people search for:

- the problem
- the workflow
- a tool
- software
- an app
- an alternative
- a competitor comparison

I personally use **DataForSEO** for this because an agent can query it directly instead of me clicking around a keyword tool for hours.

### I do not just search the obvious category

If the product idea is a "HubSpot CSV preflight tool", people may not search for that phrase.

They may search for:

- hubspot import duplicate companies
- hubspot csv association error
- hubspot multi select import
- hubspot import overwrite blank values
- validate hubspot csv
- hubspot import tool
- hubspot import alternative

Problem searches matter.

Solution searches usually matter even more.

**Prompt:** [SEO Demand Validation with DataForSEO →](prompts/seo-demand-validation.md)

---

## 4. The numbers I actually care about

I don't decide from one SEO metric.

### Search volume

Does the search exist at all?

A niche SaaS does not need a giant keyword.

I would rather find a collection of small, relevant searches than one huge keyword that has almost nothing to do with buying my product.

### Keyword Difficulty

DataForSEO's Keyword Difficulty estimates the difficulty of reaching Google's top 10 organic results.

For a new domain, I care a lot about long-tail queries where the SERP is still realistically contestable.

But a KD of `8` is not automatically good.

Sometimes nobody competes because nobody cares.

### CPC

CPC is useful because advertisers paying for a query is a decent commercial signal.

It also tells you something else: paid acquisition may get expensive.

If your product is $9/month and clicks cost $12, you should know that before launch.

### Ads Competition

This is not SEO difficulty.

Google Ads competition tells you about paid-search competition.

Keyword Difficulty tells you about organic ranking difficulty.

I keep them separate.

### Intent

This is the part I care about most.

Compare:

```text
how does invoice reconciliation work
```

with:

```text
invoice reconciliation software
```

and:

```text
a2x alternative
```

Those searches are not equally valuable to a SaaS.

The volume might even be lower on the better query.

That is fine.

---

## The rough filter I use

I am looking for some combination of:

```text
real demand
+ relevant intent
+ reachable SERPs
+ enough commercial value
```

Not a magic score.

Not "KD < 20 = build."

Not "10k searches = build."

The numbers need to make sense together.

### Example

**Keyword A**

```text
18,000 searches/month
KD 72
$1.10 CPC
mostly informational intent
SERP full of huge publishers
```

Big number. Not very exciting for a new SaaS domain.

**Keyword B**

```text
170 searches/month
KD 17
$6.40 CPC
clear software intent
several small/niche sites ranking
```

Tiny by comparison.

I would investigate B first.

A solo SaaS does not need to own Google.

It needs a small piece of Google that converts.

---

## 5. When I would not build for SEO

If SEO is supposed to be the main acquisition channel, these make me nervous:

- almost no relevant searches
- lots of searches, but no connection to the product
- only informational intent
- no tool/software/alternative searches
- every relevant SERP is dominated by very strong domains
- "easy" longtails with basically zero demand
- an audience that discovers products somewhere other than Google

In that case I would not automatically kill the product.

I would kill the **SEO assumption**.

Maybe the product belongs in:

- a marketplace
- the Chrome Web Store
- GitHub
- an app store
- a partner ecosystem
- a free tool
- an integration directory
- paid social
- direct sales

But if I don't want sales, don't want social, don't have an audience **and** cannot rank...

I probably should not pretend distribution will solve itself.

---

## 6. Build smaller than you want to

After research, I try to cut the product down to the smallest thing that solves the painful part.

Not:

> replace HubSpot

More like:

> tell me exactly what this CSV is going to break before I import it

Not:

> build new accounting software

More like:

> explain why this payout does not reconcile

Not:

> another SEO suite

More like:

> tell me when something important broke

Companion products are nice because the customer does not have to move their whole business into your software.

You just remove one ugly part of the workflow.

That is often enough for a small SaaS.

---

## 7. Cheap UGC experiments with fal.ai

If the product makes it this far, you still need people to see it.

For TikTok or Instagram experiments, I would not immediately buy an expensive UGC SaaS subscription.

You can use **fal.ai** through its agent plugin or API.

fal has many current image and video models. Different models are priced differently, commonly per generated video or per second of output.

For testing, I would start with a small balance such as **$10–20**, see what actually works, and only spend more after that.

### Don't ask one model to do everything

The useful part is letting an agent treat the ad like a tiny production pipeline.

For example:

```text
creator reference image
        ↓
talking-head shot
        ↓
product B-roll
        ↓
lip sync / audio
        ↓
captions
        ↓
final edit
```

Different models can handle different steps.

Your agent can inspect what is available and choose accordingly.

### Use reference images

For UGC, identity consistency matters more than cinematic quality.

A good workflow is:

1. generate or provide the creator image
2. use it as the identity reference
3. animate that approved image
4. use start/end frames where the model supports them
5. keep your actual product UI out of the generative model whenever possible

For SaaS, I prefer using a real screenshot or screen recording and compositing it into the creative.

AI-generated dashboards still love inventing buttons.

### You don't always need video

For Instagram you can also generate:

- carousel concepts
- backgrounds
- product mockups
- visual hooks
- slide images

Then add the important text yourself.

That avoids the classic AI typography mess.

**Prompt:** [Realistic UGC Production with fal.ai →](prompts/ugc-video-production.md)

---

## 8. My pre-build checklist

Before I give an idea real development time:

- [ ] I found the same problem in more than one place
- [ ] I know who has it
- [ ] I know how they solve it today
- [ ] I know how often it happens
- [ ] I found evidence of existing spend or meaningful pain
- [ ] I know why current solutions are not good enough
- [ ] The product can solve a narrow part without replacing everything
- [ ] I have at least one believable acquisition channel
- [ ] If that channel is SEO, I checked real keyword data
- [ ] I looked at actual SERPs, not just a KD number
- [ ] I know the smallest useful version I can ship
- [ ] I can explain why this is a real problem without mentioning AI

If I cannot answer those, I research more.

That is usually cheaper than another rewrite.

---

## That's it

My process is not complicated.

I try to find boring evidence before I write exciting code.

Sometimes the research kills an idea I wanted to build.

Good.

That is the cheapest possible failure.

If this repo saves you from building one dead SaaS, **star it so you can find it again**.
