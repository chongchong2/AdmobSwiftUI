## 2024-05-24 - Accessible "AD" Labels
**Learning:** VoiceOver often mispronounces short abbreviated labels like "AD" (reading it as "add" or "A D" depending on context). This is a common pattern in ad-supported iOS apps where visual space is limited but screen reader context shouldn't be.
**Action:** Always add an `isAccessibilityElement = true` and a full-word `accessibilityLabel` wrapped in `NSLocalizedString` (e.g., `NSLocalizedString("Advertisement", bundle: .module, comment: "...")`) for abbreviated UI elements or badges to ensure correct pronunciation.
