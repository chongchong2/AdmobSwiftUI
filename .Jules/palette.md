## 2024-08-26 - Accessibility for Abbreviated UI Elements
**Learning:** VoiceOver reads "AD" literally or phonetically instead of "Advertisement", reducing context for screen reader users.
**Action:** Always provide full-word `accessibilityLabel` strings (wrapped in `NSLocalizedString`) for abbreviated UI elements or badges (e.g., use 'Advertisement' for 'AD' badges).
