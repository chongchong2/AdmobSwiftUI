## 2024-05-18 - VoiceOver Pronunciation for Ad Badges
**Learning:** Screen readers like VoiceOver pronounce abbreviated labels like "AD" literally, spelling them out as letters rather than speaking the full word, which degrades accessibility for visually impaired users.
**Action:** Always provide full-word `accessibilityLabel` properties wrapped in `NSLocalizedString` (e.g. `Advertisement`) for badge components that display an abbreviated or acronym-based text to ensure they are spoken clearly and properly localized.
