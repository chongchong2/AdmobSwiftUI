## 2024-05-18 - Full-word Accessibility Labels for Badges
**Learning:** For iOS accessibility on VoiceOver, abbreviated UI elements or badges (like "AD") are often pronounced awkwardly. Providing full-word `accessibilityLabel` strings (e.g., "Advertisement") ensures proper screen reader pronunciation. These full-word accessibility labels must also be wrapped in `NSLocalizedString` for proper localization.
**Action:** Always provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges to ensure proper screen reader pronunciation, and wrap them in `NSLocalizedString`.
