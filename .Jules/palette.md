## 2024-05-18 - VoiceOver Pronunciation for Abbreviations
**Learning:** Screen readers like VoiceOver pronounce abbreviated labels (like "AD") literally or confusingly. Short badges need explicit, full-word `accessibilityLabel` strings for a better a11y experience.
**Action:** Always provide full-word `accessibilityLabel` (e.g., "Advertisement") for abbreviated badges, and ensure they are localized using `NSLocalizedString` for global users.
