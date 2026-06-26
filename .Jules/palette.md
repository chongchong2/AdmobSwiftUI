## 2024-05-24 - Full-word Accessibility Labels for Badges
**Learning:** Abbreviated UI elements like "AD" badges are read letter-by-letter by VoiceOver, degrading the screen reader experience.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement" instead of "AD") wrapped in `NSLocalizedString` for proper pronunciation and localization.
