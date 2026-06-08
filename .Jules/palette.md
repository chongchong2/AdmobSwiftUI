## 2024-05-18 - Full-word localized VoiceOver labels for abbreviated tags
**Learning:** Screen readers (VoiceOver) pronounce "AD" ambiguously. Using the full word "Advertisement" wrapped in `NSLocalizedString` for `accessibilityLabel` ensures accurate pronunciation and handles multi-language support.
**Action:** Always provide expanded full-word definitions in `accessibilityLabel` for badges, tags, or abbreviations (like "AD", "Promo", "Btn") to ensure proper screen reader pronunciation.
