## 2024-05-24 - VoiceOver Pronunciation for Ad Badges
**Learning:** VoiceOver struggles with abbreviations like "AD" on ad badges, reading them incorrectly. This is a common accessibility issue pattern specific to this app's components.
**Action:** Always provide a full-word `accessibilityLabel` (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated UI elements to ensure proper screen reader pronunciation.
