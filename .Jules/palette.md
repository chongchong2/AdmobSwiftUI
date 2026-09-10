## 2024-05-18 - VoiceOver Pronunciation for Badges
**Learning:** VoiceOver often mispronounces short, capitalized badge labels like "AD", reading them as individual letters ("A D") or unintended words ("add").
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement" instead of "AD") for abbreviated UI elements or badges, and ensure they are wrapped in `NSLocalizedString` for proper localization.
