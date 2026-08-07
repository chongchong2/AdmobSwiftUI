## 2024-08-07 - Add Full-Word Accessibility Labels for Abbreviated UI Elements
**Learning:** Screen readers like VoiceOver pronounce abbreviations such as "AD" literally, which can be confusing for visually impaired users. Providing a full-word `accessibilityLabel` (e.g., "Advertisement") ensures proper pronunciation and context.
**Action:** Always provide full-word `accessibilityLabel` strings wrapped in `NSLocalizedString` for abbreviated UI elements or badges to ensure proper screen reader pronunciation and localization.
