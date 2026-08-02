## 2024-05-24 - Full-word Accessibility Labels for Badges
**Learning:** In iOS applications, custom UI components with abbreviated text badges (like "AD") require full-word accessibility labels ("Advertisement") wrapped in `NSLocalizedString` for accurate VoiceOver pronunciation.
**Action:** Always add explicit `isAccessibilityElement = true` and localized `accessibilityLabel` to abbreviated badges.
