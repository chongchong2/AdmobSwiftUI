## 2023-10-27 - Ensure clear VoiceOver pronunciation for abbreviated labels
**Learning:** Abbreviated visual badges (like "AD" for advertisement) are often mispronounced or spelled out by VoiceOver, causing confusion for screen reader users. The `accessibilityLabel` must provide the full, expanded word.
**Action:** When creating abbreviated labels or tags, always explicitly set the `accessibilityLabel` to the full word (e.g., "Advertisement" instead of "AD") using `NSLocalizedString` for proper localization and clear pronunciation.
