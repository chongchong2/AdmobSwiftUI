## 2024-05-24 - Screen Reader Labels for Abbreviated Ad Tags
**Learning:** Screen readers like VoiceOver pronounce "AD" (Ad tag) as individual letters ("A-D") or poorly out of context, rather than "Advertisement", which is confusing for users. In iOS, abbreviated badges must have full-word accessibility labels (e.g. `isAccessibilityElement = true`, `accessibilityLabel = NSLocalizedString("Advertisement", ...)`).
**Action:** When adding or checking "AD" badges or similar abbreviations in custom UI components, explicitly set the `accessibilityLabel` to the full localized word.
