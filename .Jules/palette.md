## 2024-05-18 - Accessibility for Abbreviated Ad Tags
**Learning:** Screen readers often pronounce abbreviated labels like "AD" incorrectly (e.g., spelling it out as "A D").
**Action:** Always provide a full-word `accessibilityLabel` (e.g., "Advertisement") for abbreviated badges, and ensure it is wrapped in `NSLocalizedString` for proper localization.
