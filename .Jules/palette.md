## 2024-05-24 - Full-word VoiceOver Labels for Abbreviations
**Learning:** VoiceOver reads "AD" as "add" or "a d", which can confuse users. Short abbreviations or acronyms used as badges need full-word accessibility labels for clear pronunciation.
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") wrapped in `NSLocalizedString` for shortened UI elements or badges to ensure proper screen reader pronunciation.
