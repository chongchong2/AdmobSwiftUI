## 2024-08-30 - VoiceOver Pronunciation for UI Badges
**Learning:** Screen readers like VoiceOver may mispronounce abbreviated UI elements (e.g., reading "AD" as "add" instead of spelling it out or saying "Advertisement").
**Action:** Always provide full-word `accessibilityLabel` strings wrapped in `NSLocalizedString` for abbreviated UI badges to ensure proper pronunciation.
