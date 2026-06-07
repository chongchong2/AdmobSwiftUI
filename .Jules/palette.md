## 2024-05-18 - [VoiceOver Pronunciation for Badges]
**Learning:** Abbreviated UI elements like "AD" badges are pronounced literally (e.g., "A-D") or confusingly by VoiceOver if left without a dedicated accessibility label.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated UI elements or badges to ensure proper screen reader pronunciation and localization.
