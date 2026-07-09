# Palette's Journal

## 2026-07-07 - [README Accessibility Enhancements]
**Learning:** Profile READMEs often use HTML tables for multi-column layouts. Without `role="presentation"`, screen readers treat these as data tables, which can be confusing. Additionally, many social badges and stats cards lack descriptive alt text or aria-labels.
**Action:** Always add `role="presentation"` to layout tables in READMEs and ensure every icon-only link has an `aria-label`.

## 2026-07-07 - [Visual Consistency in Data Viz]
**Learning:** Data visualizations like contribution graphs and view counters often default to brand colors (GitHub green, Blueviolet) which can clash with a highly stylized profile theme. Synchronizing these colors with the overall UI palette (e.g., Glassmorphism) creates a more immersive and professional experience.
**Action:** Identify and customize color parameters in third-party badges and animations to match the repository's primary design tokens.

## 2026-07-09 - [Interactive Dashboard Elements]
**Learning:** Profile READMEs often function as dashboards. Static stats cards and animations (like the contribution snake) can be frustrating if they aren't interactive. Wrapping them in links to the source data (GitHub profile, repositories, or contribution graph) makes the "dashboard" feel alive and provides immediate value to visitors.
**Action:** Always wrap stats cards, contribution graphs, and significant badges in links to their respective live destinations on GitHub, ensuring each has a descriptive `aria-label`.
