## 2024-05-24 - Full-word Accessibility Labels for Badges
**Learning:** Screen readers like VoiceOver might read abbreviated UI badges (e.g., "AD") literally (A-D) instead of their intended meaning (Advertisement), confusing users.
**Action:** Always provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges (e.g., use 'Advertisement' for 'AD' badges) to ensure proper screen reader pronunciation. Even these full-word accessibility labels must be localized using `NSLocalizedString` for proper multilingual support.
