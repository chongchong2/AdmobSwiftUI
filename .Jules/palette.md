## 2024-03-21 - Screen readers struggle with abbreviated ad tags
**Learning:** Screen readers, like iOS VoiceOver, often struggle to pronounce abbreviated labels like "AD". This can lead to a confusing accessibility experience for visually impaired users.
**Action:** When adding small badges or tags with abbreviated text (like "AD"), always provide a full-word `accessibilityLabel` string (e.g., "Advertisement") using `NSLocalizedString` for correct pronunciation and internationalization support.
