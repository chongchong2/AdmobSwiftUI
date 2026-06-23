## 2026-06-23 - Accessibility Label for Abbreviated Badges
**Learning:** For iOS accessibility on VoiceOver, it's critical to provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges (e.g., using "Advertisement" for "AD" badges) to ensure proper screen reader pronunciation. Even these full-word accessibility labels must be wrapped in `NSLocalizedString` for proper localization.
**Action:** When creating or modifying badges with abbreviations, always define an expanded `accessibilityLabel` and ensure it is localized.
