## 2024-05-15 - Abbreviated Badges VoiceOver
**Learning:** Screen readers like VoiceOver struggle with abbreviated UI elements or badges (like "AD" for advertisement) causing confusing pronunciation.
**Action:** Always provide full-word `accessibilityLabel` strings for abbreviated UI elements (e.g., use 'Advertisement' for 'AD' badges) and wrap them in `NSLocalizedString` for proper localization.
