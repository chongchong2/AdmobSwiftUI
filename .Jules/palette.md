## 2024-05-24 - Provide full-word accessibility labels for abbreviations
**Learning:** VoiceOver often mispronounces abbreviations like "AD" or reads them as literal words instead of spelling them out, which creates confusion for visually impaired users.
**Action:** Always provide full-word `accessibilityLabel` attributes (e.g., "Advertisement") for badge-like abbreviated UI elements to ensure clear screen reader pronunciation, and ensure these labels are wrapped in `NSLocalizedString`.
