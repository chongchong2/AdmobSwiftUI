## 2024-05-18 - VoiceOver Pronunciation for Ad Badges
**Learning:** In iOS, "AD" text is often mispronounced or read letter-by-letter by VoiceOver, causing confusion for screen reader users trying to understand the context of the badge.
**Action:** Always provide a full-word `accessibilityLabel` string for abbreviated UI elements or badges (e.g., use 'Advertisement' for 'AD' badges), ensuring they are wrapped in `NSLocalizedString` for proper localization.
