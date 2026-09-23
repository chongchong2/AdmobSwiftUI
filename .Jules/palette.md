## 2024-05-18 - Full-word VoiceOver labels for badges
**Learning:** For abbreviated UI elements or badges (like "AD" for advertisement), VoiceOver often spells them out or mispronounces them (e.g. "A D"), which is confusing. Providing a full-word accessibilityLabel (e.g., "Advertisement") wrapped in NSLocalizedString significantly improves the screen reader experience.
**Action:** Always provide full-word `accessibilityLabel` strings with proper localization for UI elements that contain acronyms or abbreviations.
