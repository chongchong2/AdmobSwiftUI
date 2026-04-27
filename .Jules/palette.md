
## 2026-04-27 - Clarifying Ad Badges for VoiceOver
**Learning:** VoiceOver reads the common UI abbreviation 'AD' as the word 'add', creating a confusing experience for screen reader users encountering native ad components. Adding an explicit `accessibilityLabel` like 'Advertisement' is necessary for clarity.
**Action:** Always provide full-word accessibility labels for abbreviated UI elements or badges to ensure proper screen reader pronunciation.
