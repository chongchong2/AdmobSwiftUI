## 2026-08-14 - Screen Reader Pronunciation for Badges
**Learning:** Abbreviated UI badges (like "AD") are often pronounced poorly by iOS VoiceOver (e.g., reading it as a word instead of spelling it out, or vice versa).
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement" for "AD" badges), wrapped in `NSLocalizedString`, to ensure proper screen reader pronunciation.
