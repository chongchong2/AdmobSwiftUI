## 2024-09-05 - Ad Tag Accessibility Labels
**Learning:** Short abbreviated strings like "AD" on UI badges can be mispronounced or uninformative when read by VoiceOver.
**Action:** Always provide full-word, localized `accessibilityLabel` strings (like "Advertisement") wrapped in `NSLocalizedString` for abbreviated elements.
