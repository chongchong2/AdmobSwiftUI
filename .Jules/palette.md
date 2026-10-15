## 2024-10-24 - Accessible Labels for Abbreviated UI Elements
**Learning:** Short abbreviation tags like "AD" for advertisements can be confusing or mispronounced by VoiceOver screen readers. Standard visual badges need descriptive, full-word auditory equivalents for proper accessibility.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") and enable `isAccessibilityElement = true` for abbreviated visual badges or icon-only elements, and ensure these labels are wrapped in `NSLocalizedString` for proper localization support.
