## 2024-05-24 - Accessibility Labels for Abbreviated Badges
**Learning:** Abbreviated UI elements like 'AD' badges are read literally by screen readers (e.g., 'A D'), which can be confusing.
**Action:** Always provide full-word accessibilityLabel strings wrapped in NSLocalizedString for abbreviated UI elements to ensure proper VoiceOver pronunciation and localization.
