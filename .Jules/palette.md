## 2024-08-01 - VoiceOver Pronunciation for Ad Tags
**Learning:** Abbreviated badges like "AD" are commonly mispronounced by VoiceOver as words (e.g., "add") across ad view components, confusing users about the element's purpose.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated UI elements or badges.
