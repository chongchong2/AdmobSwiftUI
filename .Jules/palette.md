## 2024-05-18 - VoiceOver Pronunciation for UI Badges
**Learning:** Abbreviated UI labels like "AD" badges are read literally by VoiceOver (e.g., "A-D"), causing poor accessibility for visually impaired users.
**Action:** Always add full-word `accessibilityLabel` (e.g., "Advertisement") and `isAccessibilityElement = true` to abbreviated labels, and ensure they are wrapped in `NSLocalizedString` for localization.
