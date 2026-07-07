## 2024-05-15 - VoiceOver labels for App badges
**Learning:** iOS VoiceOver does not correctly read short acronyms like "AD" on small badges; providing a full-word `accessibilityLabel` ("Advertisement") ensures correct pronunciation. Additionally, even for these accessibility labels, wrapping them in `NSLocalizedString` is essential for localized experiences.
**Action:** Always add explicit, fully expanded `accessibilityLabel`s localized with `NSLocalizedString` for any abbreviation or badge in UI elements.
