## 2024-05-23 - VoiceOver pronunciation for abbreviated labels
**Learning:** VoiceOver reads abbreviated badges (like "AD") awkwardly or as individual letters, creating a poor accessibility experience for screen reader users.
**Action:** Always provide full-word `accessibilityLabel` attributes (e.g., "Advertisement") for abbreviated UI elements or badges, and ensure they are fully localized using `NSLocalizedString` for proper screen reader pronunciation.
