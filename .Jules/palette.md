
## 2024-05-24 - VoiceOver Pronunciation for UI Badges
**Learning:** Screen readers like VoiceOver will spell out or mispronounce abbreviated UI badges (e.g., "AD"). Also, standard `UILabel` elements used as badges are not interactive and by default might be skipped or improperly grouped.
**Action:** Always add `isAccessibilityElement = true` to `UILabel` badges and provide a full-word `accessibilityLabel` (e.g., "Advertisement"), wrapped in `NSLocalizedString`, to ensure proper screen reader pronunciation.
