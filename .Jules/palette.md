
## 2026-09-19 - Ad Badge VoiceOver Improvement
**Learning:** Abbreviated UI elements like "AD" badges are often mispronounced by VoiceOver (e.g., as "add"), confusing screen reader users.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated badges to ensure proper pronunciation.
