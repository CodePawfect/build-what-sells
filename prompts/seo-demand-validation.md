# SEO Demand Validation with DataForSEO

Copy this prompt into an agent that can access the DataForSEO API.

Replace the placeholders before running it.

---

```text
# SEO Demand Validation with DataForSEO

## Objective

Evaluate the following product idea exclusively from the perspective of real SEO demand:

PRODUCT IDEA:
[IDEA_X]

TARGET MARKET:
[DE / US / UK / DACH / ...]

LANGUAGE:
[de / en / ...]

Use DataForSEO as the primary data source.

I want to find out:

1. Are people actively searching for this problem?
2. Which keywords and long-tail queries exist?
3. What is the real monthly search volume?
4. How difficult would it be to rank organically?
5. Is there commercial buying intent?
6. Are there SEO niches through which a new SaaS could realistically grow?

Important:

- Use actual DataForSEO data whenever a metric is requested.
- Do not invent or estimate missing metrics.
- If a metric or endpoint is unavailable, say so.
- Keep SEO Keyword Difficulty separate from Google Ads Competition.
- Use the selected target market and language consistently.

---

## 1. Generate seed keywords

First derive 10–20 seed keywords from the product idea.

Cover different search intentions:

- problem queries
- solution queries
- software / tool queries
- alternative queries
- comparison queries
- "how to" queries
- "[problem] tool"
- "[problem] software"
- "[problem] app"
- "[competitor] alternative"
- "best [category]"
- "[category] for [specific audience]"

Do not search only for the product name or the obvious product category.

Think about how somebody experiencing the underlying problem would search before they even know that software is the solution.

---

## 2. DataForSEO keyword research

Use the available DataForSEO Keyword Data and DataForSEO Labs APIs where appropriate.

Especially consider:

- Keywords for Keywords
- Related Keywords
- Keyword Suggestions
- Keyword Ideas
- Google Search Volume
- Keyword Difficulty / Bulk Keyword Difficulty
- Search Intent
- Keyword Overview

Start from all seed keywords and discover additional relevant queries.

Target:

Analyze at least 200 relevant keywords if enough data exists.

Remove:

- clearly irrelevant keywords
- keywords using the same phrase with a different meaning
- purely informational searches unrelated to the actual problem
- brand searches unless useful for competitor or alternative analysis

Do not keep keywords just to make the dataset larger.

---

## 3. Long-tail discovery

Specifically search for long-tail keywords with:

- 3+ words
- a concrete problem
- a concrete use case
- a specific target audience
- commercial or transactional intent

Especially interesting:

Search Volume:
10–500 searches / month

Keyword Difficulty:
0–30

Intent:
clear problem, product or buying intent

But:

A keyword is NOT automatically interesting just because Keyword Difficulty is low.

Always evaluate:

DEMAND × INTENT × RANKING OPPORTUNITY

A KD 5 keyword with no useful search intent is not an opportunity.

---

## 4. Collect the following data per keyword

Create a table:

| Keyword | Search Volume | Keyword Difficulty | CPC | Ads Competition | Intent | Longtail | Relevance |
|---|---:|---:|---:|---:|---|---|---|

### Search Volume

Monthly search volume for the selected market.

### Keyword Difficulty

SEO Keyword Difficulty from DataForSEO.

Do NOT confuse this with Google Ads Competition.

### CPC

Google Ads CPC.

Use CPC as a signal that advertisers may see economic value in the query.

Do not treat CPC as proof of willingness to pay for this specific SaaS.

### Ads Competition

Report Google Ads Competition / Competition Index separately.

### Intent

Classify:

- Informational
- Commercial Investigation
- Transactional
- Navigational

### Longtail

Yes / No

### Relevance

Rate actual relevance to the product idea:

- High
- Medium
- Low

Be strict.

---

## 5. Build keyword clusters

Cluster keywords by the actual search problem.

Example:

### Cluster A — Direct core problem

Queries that directly describe the problem.

### Cluster B — Tool / software

Users already searching for software that solves the problem.

### Cluster C — Alternatives / competitors

Users searching for alternatives to existing products.

### Cluster D — Workflow / how-to

Users currently trying to solve the problem manually.

### Cluster E — Long-tail use cases

Specific industries, audiences or workflows.

For each cluster report:

- number of relevant keywords
- estimated combined search volume
- median Keyword Difficulty
- average CPC
- dominant search intent
- commercial intent: Low / Medium / High
- five best keywords

Do not blindly add keyword volumes when queries strongly overlap or represent the same underlying search demand.

---

## 6. Find the best SEO opportunities

Identify the 20 most interesting keywords for a new SaaS.

Prioritize keywords with:

- strong product relevance
- clear search intent
- low to moderate difficulty
- measurable search volume
- preferably CPC > 0
- SERPs not exclusively dominated by extremely strong domains

Do NOT simply sort by search volume.

For each selected keyword, briefly explain why it matters.

---

## 7. Find BOFU keywords

Explicitly search for Bottom-of-Funnel queries such as:

- "[category] software"
- "[category] tool"
- "best [category]"
- "[category] alternative"
- "[competitor] alternative"
- "[competitor] vs"
- "[problem] software"
- "[problem] automation"
- "[problem] app"

Report them separately:

| BOFU Keyword | Volume | KD | CPC | Intent |
|---|---:|---:|---:|---|

Give these queries extra weight during product validation.

---

## 8. Separate problem demand from solution demand

Distinguish:

### Problem Demand

People search for the problem but may not know software could solve it.

Examples:

- how to reconcile X
- why does X not match Y
- how to track X manually
- how to export X to Y

### Solution Demand

People explicitly search for:

- tools
- software
- apps
- automation
- services
- alternatives

Weight Solution Demand more strongly when evaluating SaaS search demand.

Do not ignore Problem Demand if the product could naturally educate and convert those users.

---

## 9. SEO opportunity assessment

Do not create artificial mathematical precision.

Evaluate every meaningful cluster qualitatively.

### Demand

- Low
- Medium
- High

### Commercial Intent

- Low
- Medium
- High

### SEO Difficulty

- Low
- Medium
- High

### SaaS Relevance

- Low
- Medium
- High

### Long-Tail Depth

- Low
- Medium
- High

Explain the reasoning behind each assessment.

---

# Final analysis

Answer the following questions concisely.

## Demand

How much relevant search demand actually exists?

Report:

- total relevant search volume
- search volume of High-Relevance keywords
- search volume of commercially relevant keywords
- BOFU search volume

Do NOT blindly sum strongly overlapping keywords.

Call out uncertainty where necessary.

---

## SEO entry points

Which 3–5 keyword clusters are the most realistic entry points for a brand-new domain?

For each cluster show concrete example keywords including:

- Search Volume
- Keyword Difficulty
- CPC

Explain why a new site might realistically compete.

---

## Long-tail opportunity

Are there enough long-tail queries with:

KD ≤ 30
+
clear product relevance
+
real search demand?

Show the strongest examples.

Do not call something an opportunity just because KD is low.

---

## Commercial signal

Evaluate the commercial signal using:

- CPC
- Ads Competition
- BOFU searches
- Tool / Software searches
- Alternative searches
- Comparison searches

Determine whether the search behavior suggests meaningful economic demand.

Remember:

CPC and advertiser activity are signals, not proof of SaaS willingness to pay.

---

## SERP reality check

For the strongest candidate keywords, inspect who currently ranks.

Look for:

- dominant authority sites
- SaaS landing pages
- niche websites
- forums
- Reddit
- directories
- weak or outdated pages
- pages only partially matching the search intent

Determine whether a new specialized domain has a realistic opening.

Keyword Difficulty alone is not enough.

---

## Conclusion

Classify the idea from an SEO-acquisition perspective as:

### BUILD

Strong organic demand
+
reachable keywords
+
commercial intent
+
credible SEO entry points

### VALIDATE

Interesting signals exist, but demand, ranking opportunity or purchase intent remains uncertain.

### KILL SEO

Too little relevant search demand or SERPs are structurally unsuitable for an SEO-driven go-to-market strategy.

Important:

KILL SEO does NOT automatically mean KILL PRODUCT.

It means SEO is probably not a strong primary acquisition channel for this product.

Support the conclusion with the 5–10 most important numbers discovered during the analysis.

End with:

1. strongest keyword
2. strongest BOFU keyword
3. easiest credible entry keyword
4. highest commercial-intent cluster
5. biggest SEO risk
6. recommended next validation step
```
