# Palette's Journal

## 2026-07-07 - [README Accessibility Enhancements]
**Learning:** Profile READMEs often use HTML tables for multi-column layouts. Without `role="presentation"`, screen readers treat these as data tables, which can be confusing. Additionally, many social badges and stats cards lack descriptive alt text or aria-labels.
**Action:** Always add `role="presentation"` to layout tables in READMEs and ensure every icon-only link has an `aria-label`.
