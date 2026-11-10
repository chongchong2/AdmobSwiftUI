## 2023-10-25 - VoiceOver Pronunciation for Ad Badges
**Learning:** Short abbreviation badges like "AD" are often mispronounced by VoiceOver or lack context.
**Action:** Always set `isAccessibilityElement = true` and provide a full-word, localized `accessibilityLabel` (e.g., "Advertisement") for such badges to ensure clear screen reader announcements.
