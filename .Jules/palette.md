## 2024-05-18 - VoiceOver Pronunciation for UI Badges
**Learning:** Screen readers often mispronounce short abbreviated UI badges (like "AD" being read as the word "add" instead of "advertisement").
**Action:** Always provide full-word `accessibilityLabel` strings wrapped in `NSLocalizedString` for abbreviated UI badges to ensure screen readers announce them properly to users.
