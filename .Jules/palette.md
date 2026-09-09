## 2024-05-24 - Accessible "AD" Badges
**Learning:** VoiceOver screen readers struggle with UI abbreviations like "AD", often pronouncing them strangely. Explicitly setting full-word `accessibilityLabel` strings is essential for these abbreviated badges to ensure they are read out clearly to users.
**Action:** Always provide full-word `accessibilityLabel` attributes wrapped in `NSLocalizedString` for abbreviated labels or badges like "AD" to optimize the experience for screen reader users.
