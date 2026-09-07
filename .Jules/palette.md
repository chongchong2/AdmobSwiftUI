## 2024-05-24 - VoiceOver Pronunciation for Ad Badges
**Learning:** Screen readers often mispronounce abbreviated badges like "AD" (reading it as a word or individual letters out of context), confusing visually impaired users.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") for abbreviated badges, and wrap them in `NSLocalizedString` for proper localization.
