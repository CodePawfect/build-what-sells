# Visual assets

The README cover is `banner.png` (2172 × 724 pixels, 3:1). It was edited with the built-in Imagegen tool and is stored here so the repository can display it directly. The original wordmark and supporting line sit over a full-width Search Console-style graph with blue and violet daily curves, uneven growth, plateaus and setbacks.

The five badges under `badges/` are editable SVGs. Their mint accent matches the cover. Each badge links to a relevant prompt or README section, and all text is also available through descriptive image alternatives.

## Banner generation prompt

```text
Use case: precise-object-edit
Asset type: replacement GitHub README cover banner, very wide 3:1 landscape, ideally 2160 x 720 pixels.
Input image 1: edit target. Preserve its exact brand wordmark and supporting text, while replacing the entire scene behind it.

Primary request: Remove the three-dimensional research cards, magnifying glass, phone, all icons, tabletop and studio setting. Replace the whole background with a clean, flat, high-fidelity search-performance line chart inspired by the plotting area of Google Search Console. It should feel like a practical analytics graph, not an AI illustration.

Keep unchanged: the large left-aligned wordmark "Build What Sells", bold clean sans-serif, "Build What" in warm white and "Sells" in mint green. Keep its approximate size and position from the input. Keep the small widely spaced line underneath, exactly "IDEAS / SEARCH TRAFFIC / UGC", with gray letters and mint slashes. These are the only words in the image.

Background: flat dark graphite chart surface across the ENTIRE banner, with subtle thin horizontal grid lines. Two distinct fine blue and violet daily time-series polylines, inspired by clicks and impressions, extend from the left edge to near the right edge. Chart should occupy the full background, not a small widget on the right. Attenuate the chart behind the existing left-hand wordmark enough to keep the text crisp; let its detail show clearly across the open right side and below the text. No hard rectangular panel behind the logo.

Graph realism: roughly 150-200 densely spaced daily points connected by crisp straight segments, with irregular day-to-day fluctuations. Begin low with a long uneven slow start. Gradually build traffic in several stages with weekly dips of varying depth, occasional abrupt spikes and corrections, a noticeable sustained setback in the middle, and a later choppy plateau before further growth. Growth is clear across the whole span, but the data must NOT rise monotonically. Vary the amplitudes and frequency. Make the two series correlated but visibly different, not copied parallel traces. The last point is slightly below a recent peak, not the highest point. Retain generous room above the highest peaks.

Style: restrained, matter-of-fact, precisely rendered flat chart lines like a real analytics plot. Thin lines, no thick painted strokes, no neon glow, no gradients beneath the lines, no area fill, no volumetric effects, no perspective.
Constraints: no icons, 3D objects, arrows, bar charts, decorative elements, floating cards, metric totals, invented performance claims, browser chrome, device frame, extra headings, axes text, annotations, disclaimer text, 'illustration' labels, 'test data' labels, footnotes, watermarks or Google logo. Preserve clean safe margins and make the existing title easily readable at README scale. Output the finished banner only.
```
