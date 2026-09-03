## 2024-05-24 - Provide full-word VoiceOver labels for acronyms
**Learning:** Screen readers often mispronounce abbreviations (like "AD" for advertisement), confusing visually impaired users.
**Action:** Always add `isAccessibilityElement = true` and provide a full-word `accessibilityLabel` (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated UI badges.
