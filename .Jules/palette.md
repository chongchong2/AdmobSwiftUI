## 2024-05-18 - VoiceOver mispronunciation of UI abbreviations
**Learning:** VoiceOver screen readers often mispronounce all-caps abbreviations like "AD" (reading it as the word "ad" rather than spelling it out or identifying it as an advertisement), causing confusion for visually impaired users.
**Action:** Always apply an `accessibilityLabel` using the full word (e.g., "Advertisement") and ensure it is wrapped in `NSLocalizedString` for proper localization. Elements like small ad badges must set `isAccessibilityElement = true` and `accessibilityLabel` explicitly.
