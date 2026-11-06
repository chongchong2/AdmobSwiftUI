
## 2024-05-23 - Screen Reader Pronunciation of Abbreviations
**Learning:** Abbreviated UI elements like "AD" badges can be pronounced incorrectly (e.g., "add") by screen readers.
**Action:** Always provide full-word accessibilityLabel strings wrapped in NSLocalizedString (e.g., "Advertisement") for abbreviated UI elements to ensure proper VoiceOver pronunciation, while making sure the UILabel is flagged as an accessibility element.
