
## 2024-05-24 - Provide full-word accessibilityLabel for Ad tags
**Learning:** Abbreviated UI labels like 'AD' for advertisement badges often get pronounced strangely by VoiceOver if not provided with a full-word accessibility label, impacting iOS native accessibility.
**Action:** Provide an explicit `accessibilityLabel` with a full word (e.g., 'Advertisement') and ensure it uses `NSLocalizedString` for proper screen reader localization on native elements.
