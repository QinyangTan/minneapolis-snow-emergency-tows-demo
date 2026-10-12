# Three Days, Three Rules — Live Minneapolis Snow Emergency Visualization

**[▶ Open the interactive dashboard](https://qinyangtan.github.io/minneapolis-snow-emergency-tows-demo/)**

CSCI 5609 · University of Minnesota · Minneapolis historical Snow Emergency towing records.

## Explore in three clicks

1. **Choose an emergency** (for example **Bridge**) to update the citywide day bars, totals, and neighborhood map together.
2. **Choose Day 1, 2, or 3**, then click a neighborhood to inspect the observed tow count.
3. **Brush Day 2 shares** to highlight which of the nine separate emergencies fit the selected range. Use **Explore all charts ↗** to reveal the constellation, side-by-side maps, recurrence and comparison analysis.

The compact overview opens by default; deeper explanations are available on demand. Interactions work with mouse or keyboard, and the layout adapts to mobile.

## Data and interpretation

- **5,423 observed tow records** from **nine complete historical emergencies** in the published City-derived dataset.
- **87 Minneapolis neighborhoods** in the interactive map. **68 observations** are not assigned to map neighborhoods, but remain included in citywide totals.
- Day compositions use citywide records; mapped neighborhood totals can be smaller. Counts are **not** individual parking/towing probabilities.
- Brushing an event share range **highlights events**; it does not aggregate unrelated storms or assert a statistically significant causal pattern.

This is a descriptive educational data visualization, **not** City parking guidance, an enforcement forecast, a risk predictor, or a causal inference.

## Verification and release

The corresponding private development repository passed **22 Chromium end-to-end browser tests** and a GitHub Pages project-path smoke test for the October 2026 linked-dashboard release. Those automated checks are **not** a substitute for participant-based usability evaluation or manual screen-reader review.

This public repository contains only **compiled static HTML/CSS/JavaScript** and **processed public City data** needed to run the website. Application source, research notes, team work, and private coursework remain in a separate private repository.

[▶ Launch the live visualization](https://qinyangtan.github.io/minneapolis-snow-emergency-tows-demo/)
