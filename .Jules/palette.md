## 2024-05-24 - VoiceOver Pronunciation for Abbreviations
**Learning:** Screen readers like VoiceOver incorrectly pronounce abbreviated labels (e.g., "AD") as individual letters or unrelated words if they lack a descriptive accessibilityLabel. Providing a full-word accessibility label, wrapped in NSLocalizedString for localization, is critical for usability.
**Action:** Always provide full-word accessibility labels (e.g., "Advertisement") for abbreviated badges or UI elements, ensuring proper localized VoiceOver pronunciation.
