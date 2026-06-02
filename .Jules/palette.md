## 2024-06-02 - iOS Accessibility for Abbreviations
**Learning:** For iOS VoiceOver accessibility, standard abbreviations in UI elements (like "AD" for advertisement badges) can be pronounced incorrectly (e.g., spelled out or spoken as a weird word). They require full-word `accessibilityLabel` strings (like "Advertisement") wrapped in `NSLocalizedString` for proper screen reader support and localization.
**Action:** Always provide full-word localized accessibility labels for abbreviated UI elements or badges to ensure VoiceOver pronounces them correctly.
