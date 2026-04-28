## 2024-04-28 - Improve VoiceOver pronunciation for Ad badges
**Learning:** Abbreviated UI elements like "AD" badges in UIKit components need explicit, full-word `accessibilityLabel`s (e.g., "Advertisement") to ensure VoiceOver pronounces the word instead of spelling out the letters.
**Action:** When implementing badges or short abbreviations, always apply `isAccessibilityElement = true` and provide a descriptive `accessibilityLabel`.
