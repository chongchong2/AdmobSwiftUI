## 2024-05-24 - Screen Reader Pronunciation of Abbreviated Badges
**Learning:** For iOS accessibility on VoiceOver, always provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges (e.g., use "Advertisement" for "AD" badges) to ensure proper screen reader pronunciation.
**Action:** Always set `isAccessibilityElement = true` and `accessibilityLabel = "Full Word"` for UI elements displaying abbreviations.
