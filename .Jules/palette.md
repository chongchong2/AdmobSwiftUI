
## 2024-10-08 - Accessible Ad Badges
**Learning:** Abbreviated UI elements like "AD" badges are read literally by VoiceOver (e.g., "A-D"), which can be confusing for screen reader users.
**Action:** Always set `isAccessibilityElement = true` and provide a full-word `accessibilityLabel` wrapped in `NSLocalizedString` for abbreviated badges to ensure proper pronunciation.
