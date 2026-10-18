## 2024-05-24 - Accessible Ad Badges
**Learning:** Abbreviated visual badges (like "AD") are poorly pronounced by VoiceOver and lack context for screen reader users. Furthermore, UILabel badges need explicit accessibility labels to ensure proper pronunciation.
**Action:** Always set `isAccessibilityElement = true` and provide a full-word `accessibilityLabel` (e.g., "Advertisement") for abbreviated badges, and ensure they are wrapped in `NSLocalizedString` for proper localization.
