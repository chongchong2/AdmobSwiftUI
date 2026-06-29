## 2024-05-24 - Screen Reader Abbreviations
**Learning:** Abbreviated badges like "AD" are often pronounced poorly by screen readers (e.g., read as "add" instead of spelling it out). Full-word explicit labels are needed for native iOS accessibility.
**Action:** When encountering abbreviated UI elements (like "AD" for advertisement), explicitly set the `accessibilityLabel` using the full expanded word (e.g., `accessibilityLabel = NSLocalizedString("Advertisement", bundle: .module, comment: "...")`). Ensure these full words are also properly localized.
