## 2024-05-15 - VoiceOver Acronym Mispronunciation
**Learning:** Short uppercase acronyms used as badges (like "AD" for Advertisement) are often mispronounced by VoiceOver as words (e.g., "add") instead of individual letters or their full meaning, leading to a confusing accessibility experience.
**Action:** Always provide a full-word `accessibilityLabel` (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated UI elements or badges to ensure proper screen reader pronunciation.
