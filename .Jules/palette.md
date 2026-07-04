## 2024-05-23 - Abbreviated Badges Accessibility
**Learning:** VoiceOver reads abbreviated "AD" badges incorrectly as the word "add" instead of "Advertisement", which can confuse users regarding the nature of the content.
**Action:** Always explicitly set an `accessibilityLabel` with the full word "Advertisement" on ad badges, wrapped in `NSLocalizedString` for proper localization.
