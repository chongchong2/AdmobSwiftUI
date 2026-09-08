## 2024-10-25 - Accessibility labels for abbreviated Ad Badges
**Learning:** VoiceOver pronounces abbreviated UI elements like "AD" badges literally, which can be confusing. Using a full-word `accessibilityLabel` (e.g., "Advertisement") wrapped in `NSLocalizedString` ensures proper screen reader pronunciation and accurate localization for all users.
**Action:** Always provide full-word, localized `accessibilityLabel` strings for abbreviated UI elements or badges to ensure proper screen reader pronunciation.
