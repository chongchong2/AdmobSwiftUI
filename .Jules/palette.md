## 2024-05-18 - VoiceOver Pronunciation of Abbreviations
**Learning:** Screen readers like VoiceOver often struggle with abbreviations (like "AD" for Advertisement), sometimes pronouncing them as individual letters ("A-D") or confusing them with other words.
**Action:** When creating badges or labels with abbreviations, always provide a full-word `accessibilityLabel` (e.g., "Advertisement") and ensure it is properly localized using `NSLocalizedString`.
