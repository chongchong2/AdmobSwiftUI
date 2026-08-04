## 2024-08-04 - VoiceOver Accessibility for Abbreviated UI Tags
**Learning:** Screen readers like VoiceOver pronounce short abbreviations (like "AD") poorly. Relying on visual labels is insufficient for accessibility.
**Action:** Always provide full-word `accessibilityLabel` attributes for abbreviated UI badges (e.g., set to "Advertisement" instead of "AD"), ensuring to wrap them in localization strings.
