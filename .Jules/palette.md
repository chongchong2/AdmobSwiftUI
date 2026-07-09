## 2026-07-09 - VoiceOver abbreviation context
**Learning:** VoiceOver needs full-word accessibility labels for abbreviated UI elements or badges (like 'AD' -> 'Advertisement') to ensure proper pronunciation. Even these full-word accessibility labels must be wrapped in NSLocalizedString for proper localization.
**Action:** Always provide expanded, localized accessibilityLabel strings for short badges or abbreviations.
