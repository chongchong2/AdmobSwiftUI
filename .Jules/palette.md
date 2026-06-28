## 2024-05-29 - Proper VoiceOver pronunciation for abbreviated AD badges
**Learning:** Screen readers like VoiceOver pronounce short abbreviations like "AD" awkwardly ("A-D" or a generic word "ad"). Full words provide much better context.
**Action:** Always provide full-word `accessibilityLabel` attributes (e.g., "Advertisement") for abbreviation badges, and ensure they are wrapped in `NSLocalizedString` for proper localization.
