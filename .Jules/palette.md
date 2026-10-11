## 2024-10-11 - VoiceOver Pronunciation of Abbreviations
**Learning:** Screen readers like VoiceOver may mispronounce short UI abbreviations (e.g., reading "AD" as individual letters or unrelated words instead of "Advertisement"), leading to a confusing accessibility experience.
**Action:** Always provide full-word, localized `accessibilityLabel` strings for abbreviated UI elements or badges, and ensure they have `isAccessibilityElement = true`.
