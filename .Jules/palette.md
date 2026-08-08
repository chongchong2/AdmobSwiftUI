## 2024-05-24 - VoiceOver Pronunciation for Ad Badges
**Learning:** VoiceOver struggles with abbreviated UI badges like "AD", often spelling them out or mispronouncing them, which creates a poor accessibility experience in ad-supported components.
**Action:** Always provide full-word `accessibilityLabel` strings wrapped in `NSLocalizedString` (e.g., "Advertisement") for abbreviated badges to ensure correct screen reader pronunciation and localization support.
