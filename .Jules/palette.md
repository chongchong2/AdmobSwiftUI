## 2026-08-21 - VoiceOver Pronunciation of Abbreviated UI Elements
**Learning:** Abbreviated UI badges like "AD" are often mispronounced by VoiceOver (e.g., as the word "add") or lack clear context for screen reader users.
**Action:** Always provide a full-word `accessibilityLabel` (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated badges to ensure clear screen reader pronunciation and context.
