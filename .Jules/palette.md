## 2024-10-20 - Ensure Full-Word Accessibility Labels for UI Badges
**Learning:** Short UI badges (like "AD") need explicitly spelled out VoiceOver strings to ensure screen readers don't mispronounce them.
**Action:** Always add explicit `accessibilityLabel` strings (like "Advertisement") with `isAccessibilityElement = true` for informative non-interactive text badges.
