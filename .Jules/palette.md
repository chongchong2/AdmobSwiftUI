## 2026-09-14 - Improve VoiceOver for Ad Badges
**Learning:** Abbreviated UI elements like "AD" badges are often mispronounced by VoiceOver (e.g. as the word "add"), which causes confusion for screen reader users.
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") for abbreviated UI elements or badges, and ensure these labels are wrapped in `NSLocalizedString` for proper localization.
