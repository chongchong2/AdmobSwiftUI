## 2024-05-18 - VoiceOver for Abbreviated UI Badges
**Learning:** Abbreviated visual badges (like "AD") used in UI are often mispronounced or skipped by VoiceOver. Providing a full-word `accessibilityLabel` is necessary for comprehension.
**Action:** Always provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges (e.g., use "Advertisement" for "AD" badges), and wrap them in `NSLocalizedString` for proper localization.
