## 2024-05-18 - Full-word Accessibility Labels for Badges
**Learning:** VoiceOver screen reader relies on standard language pronunciation. Abbreviated UI components, like an "AD" badge, can be mispronounced or confusing. VoiceOver requires full-word accessibility labels, such as "Advertisement", to ensure clarity for visually impaired users.
**Action:** When adding accessibility to abbreviated UI elements or badges, always apply a full-word `accessibilityLabel` wrapped in `NSLocalizedString` for proper localization.
