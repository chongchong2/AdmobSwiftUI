## 2026-07-08 - VoiceOver and Abbreviated UI Badges
**Learning:** VoiceOver mispronounces abbreviated UI badges (like 'AD'). Even when text is visible as 'AD', we must provide a full-word accessibility label (e.g., 'Advertisement') and ensure it is wrapped in `NSLocalizedString` for proper localization.
**Action:** Always add `isAccessibilityElement = true` and a localized, full-word `accessibilityLabel` to abbreviated UI elements/badges.
