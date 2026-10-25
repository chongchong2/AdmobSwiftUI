## 2024-05-15 - Improve Screen Reader Pronunciation for Badges
**Learning:** Short abbreviated UI elements or badges (like "AD") are unhelpful or mispronounced by VoiceOver. Screen readers require full-word `accessibilityLabel` strings for clear pronunciation.
**Action:** Always provide full-word `accessibilityLabel` (e.g., "Advertisement") for abbreviated badges, and ensure they are wrapped in `NSLocalizedString` for proper localization. Ensure `isAccessibilityElement = true` is set on non-interactive UI elements like UILabels used as badges so VoiceOver can read them.
