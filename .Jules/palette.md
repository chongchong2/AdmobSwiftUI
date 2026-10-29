## 2024-05-24 - Screen Reader Pronunciation for Badge Abbreviations
**Learning:** iOS VoiceOver often reads short acronyms like "AD" incorrectly. Providing a full-word `accessibilityLabel` like "Advertisement" (localized correctly) and enabling `isAccessibilityElement = true` ensures an optimal native screen reader experience.
**Action:** Always provide full-word, properly localized accessibility labels for abbreviated UI elements or badges.
