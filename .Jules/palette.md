## 2024-08-13 - VoiceOver on Abbreviated Labels
**Learning:** In native iOS UI, abbreviated badges like "AD" are often mispronounced by screen readers (e.g. as "add" instead of "A D" or "Advertisement").
**Action:** Always provide full-word `accessibilityLabel` strings (wrapped in `NSLocalizedString` for proper localization) for abbreviated UI elements or badges to ensure proper screen reader pronunciation.
