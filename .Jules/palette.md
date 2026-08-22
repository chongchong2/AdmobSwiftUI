## 2026-08-22 - Proper Accessibility Labels for Ad Badges
**Learning:** The "AD" badge is used across native ads, but without a full-word accessibility label, VoiceOver may spell it out or pronounce it poorly, confusing users.
**Action:** Always provide full-word `accessibilityLabel` strings wrapped in `NSLocalizedString` (e.g., "Advertisement") for abbreviated UI elements or badges to ensure proper screen reader pronunciation.
