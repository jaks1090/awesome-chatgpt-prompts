---
title: Maps UI
---

<p class="page-intro">A refreshed maps GUI concept for navigating prompt collections by topic, region, and contribution density.</p>

<div class="maps-layout">
  <aside class="panel">
    <h3>Filters</h3>
    <p><strong>Topic</strong></p>
    <p>☑️ Education<br>☑️ Productivity<br>☐ Healthcare<br>☑️ Developer Tools</p>
    <p><strong>Interaction</strong></p>
    <p>☑️ Most copied<br>☑️ Recently updated<br>☐ Beginner-friendly</p>
    <p><strong>Density</strong></p>
    <p>Low ●○○<br>Medium ●●○<br>High ●●●</p>
  </aside>

  <section class="panel">
    <h3>Prompt Discovery Map</h3>
    <div class="mock-map"></div>
    <p style="margin-top:0.8rem; color:#57606a;">Pins represent high-performing prompt clusters. Hover cards and route overlays can be added in a future iteration.</p>
  </section>
</div>

## UI improvements included

- **Cleaner visual hierarchy** with separated filter panel and map canvas.
- **Scannable controls** for topic, interaction type, and density.
- **Prototype-ready map zone** that can be replaced by Leaflet/Mapbox/Google Maps later.
- **Accessible labels** and readable contrast for quick exploration.

## Next map features

1. Click a pin to open prompt cards in a side sheet.
2. Add a timeline slider to replay prompt popularity over time.
3. Offer saved map views (e.g., "Top This Week", "New & Rising").
