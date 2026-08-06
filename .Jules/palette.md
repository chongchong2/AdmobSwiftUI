## 2024-05-24 - Full-word VoiceOver Labels for Badges
**Learning:** Abbreviated UI elements or badges (like "AD") are often mispronounced or unclear when read by iOS VoiceOver. Providing full-word `accessibilityLabel` strings (like "Advertisement") ensures screen readers communicate the exact meaning.
**Action:** Always assign a full-word `accessibilityLabel` wrapped in `NSLocalizedString` for abbreviated tags or badges in native iOS components.
