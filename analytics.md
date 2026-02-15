---
title: Analytics
---

<p class="page-intro">A lightweight analytics experience for understanding prompt usage, quality signals, and contributor activity.</p>

## Snapshot

<div class="stats-grid">
  <div class="stat-card"><div class="stat-value">12.4k</div><div>Prompt views (30d)</div></div>
  <div class="stat-card"><div class="stat-value">4.7k</div><div>Prompt copies (30d)</div></div>
  <div class="stat-card"><div class="stat-value">38%</div><div>Copy-to-view rate</div></div>
  <div class="stat-card"><div class="stat-value">+14%</div><div>Monthly growth</div></div>
</div>

## Content performance

| Page | Views | Copies | Conversion |
| --- | ---: | ---: | ---: |
| Home Prompt List | 8,910 | 3,102 | 34.8% |
| Analytics | 1,820 | 714 | 39.2% |
| Maps UI | 1,270 | 511 | 40.2% |
| About | 403 | 89 | 22.1% |

## Weekly trend (prototype)

<svg width="100%" viewBox="0 0 720 240" role="img" aria-label="Weekly prompt copy trend chart">
  <rect x="0" y="0" width="720" height="240" fill="#ffffff" stroke="#d0d7de"/>
  <line x1="50" y1="200" x2="680" y2="200" stroke="#8c959f" />
  <line x1="50" y1="40" x2="50" y2="200" stroke="#8c959f" />
  <polyline fill="none" stroke="#1f6feb" stroke-width="4" points="50,180 140,165 230,150 320,160 410,135 500,120 590,95 680,88"/>
  <g fill="#1f6feb">
    <circle cx="50" cy="180" r="4"/><circle cx="140" cy="165" r="4"/><circle cx="230" cy="150" r="4"/>
    <circle cx="320" cy="160" r="4"/><circle cx="410" cy="135" r="4"/><circle cx="500" cy="120" r="4"/>
    <circle cx="590" cy="95" r="4"/><circle cx="680" cy="88" r="4"/>
  </g>
  <text x="55" y="30" fill="#57606a" font-size="14">Prompt copies over time</text>
</svg>

## What to improve next

- Add date filters and segment by device type.
- Add top search queries to understand user intent.
- Track edits inside prompt blocks to identify customization behavior.
