## 2024-05-15 - Add full-word accessibility label to Ad Tags
**Learning:** Badges that use abbreviations like "AD" for Advertisement are often mispronounced by VoiceOver (e.g. read as the word "add") or lack clarity for visually impaired users. Providing a full-word `accessibilityLabel` (like "Advertisement") wrapped in `NSLocalizedString` improves screen reader comprehension.
**Action:** Always add an explicit, fully spelled-out `accessibilityLabel` using `NSLocalizedString` for abbreviated UI tags/badges in iOS components to ensure VoiceOver pronounces them correctly.
