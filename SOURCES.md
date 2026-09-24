# Research notes

The README was rewritten after reviewing web-writing research and several high-star GitHub repositories.

This file is deliberately separate from the main README. The README should be useful first, not read like a research paper.

## What changed from the first draft

### 1. Less "playbook voice"

The first draft used a lot of polished slogans, symmetrical contrasts and repeated one-line declarations.

That scans well, but too much of it starts to feel generated.

The rewrite uses:

- first person
- concrete examples
- fewer slogans
- fewer callout boxes
- fewer decorative headings
- normal transitions
- occasional longer sentences

### 2. The useful thing appears early

The opening names the three ready-to-use prompts and their audience. Each prompt is linked immediately, alongside the reader's problem and the result they can work toward: a shortlist of SaaS opportunities, an organic-traffic assessment or UGC videos. Tool requirements follow, then the longer guide.

Nielsen Norman Group repeatedly finds that web users scan rather than read linearly and recommends concise copy, meaningful headings, bullets, one idea per paragraph and an inverted-pyramid structure.

Sources:

- https://www.nngroup.com/articles/how-users-read-on-the-web/
- https://www.nngroup.com/articles/inverted-pyramid/
- https://www.nngroup.com/articles/concise-scannable-and-objective-how-to-write-for-the-web/

### 3. AI-specific writing guidance

NN/g's 2025 research on product-specific GenAI found that generated answers often violate established web-writing rules. Their recommendation is still simple: concise, scannable, plain language, important information first.

Source:

- https://www.nngroup.com/articles/genai-write-for-the-web/

### 4. Prompts moved out of the README

The long prompts are useful, but they destroy the reading flow when embedded directly in the article.

They now live under `/prompts/` and are linked from the relevant section.

That keeps the README short while preserving the full copy-paste material.

This also resembles high-star reference repositories that use the README as a map into useful material:

- https://github.com/codecrafters-io/build-your-own-x
- https://github.com/public-apis/public-apis
- https://github.com/donnemartin/system-design-primer
- https://github.com/sindresorhus/awesome

### 5. A visual introduction with useful badges

The cover gives the project a visual identity and introduces its three uses: ideas, search traffic and UGC. Five linked badges surface the prompt count, audience and tools, with direct routes into the relevant sections.

The banner and badges are stored in the repository. The concrete value proposition and prompt links follow immediately below them.

### 6. Active, direct sentences

Google's technical-writing guidance recommends active voice for most technical writing and favors shorter, simpler sentences.

Sources:

- https://developers.google.com/tech-writing/one/active-voice
- https://developers.google.com/tech-writing/one/short-sentences

## Technical sources used to verify claims

### DataForSEO

DataForSEO documents Keyword Difficulty as a 0–100 logarithmic metric about difficulty/chance of reaching the first top-10 organic results. Its keyword endpoints also expose search volume, CPC, paid competition and search intent.

- https://docs.dataforseo.com/v3/dataforseo_labs-google-overview/
- https://docs.dataforseo.com/v3/dataforseo_labs-google-keyword_suggestions-live/
- https://docs.dataforseo.com/v3/dataforseo_labs-google-bulk_keyword_difficulty-live/

### fal.ai

fal documents output-based video pricing. Depending on the model, video can be billed per second or per generated video.

- https://fal.ai/pricing
- https://fal.ai/explore/text-to-video-apis

## Style rule of thumb

The target is not "make AI text harder to detect."

The target is:

> write something a developer would still choose to read if nobody told them how it was produced.

That usually means being more specific, less promotional and less obsessed with sounding clever.
