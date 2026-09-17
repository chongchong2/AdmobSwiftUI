## 2024-05-24 - VoiceOver Pronunciation for Abbreviated Badges
**Learning:** Abbreviated UI badges like "AD" are often poorly pronounced by screen readers (e.g., read as a word instead of individual letters or the full word).
**Action:** Always provide a full-word `accessibilityLabel` (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated badges to ensure correct VoiceOver pronunciation.
