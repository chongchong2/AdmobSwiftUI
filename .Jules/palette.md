## 2024-05-24 - VoiceOver Pronunciation for Abbreviations
**Learning:** Screen readers like VoiceOver often struggle with reading short, all-caps abbreviations like "AD" correctly, sometimes reading them letter-by-letter ("A-D") or confusing them with words depending on context.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") for abbreviated UI elements or badges to ensure correct and clear pronunciation for users relying on screen readers. Wrap these full-word replacements in `NSLocalizedString` for proper i18n support.
