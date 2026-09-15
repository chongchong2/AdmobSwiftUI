## 2026-09-15 - Accessibility labels for abbreviated UI elements
**Learning:** Screen readers often mispronounce abbreviated UI elements like "AD" badges, reading them as "add" instead of "Advertisement".
**Action:** Always provide full-word `accessibilityLabel` strings wrapped in `NSLocalizedString` for abbreviated UI elements or badges to ensure proper screen reader pronunciation.
