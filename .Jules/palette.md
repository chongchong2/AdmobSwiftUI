## 2024-05-24 - Full-Word Accessibility Labels for Abbreviations
**Learning:** When using abbreviated UI elements like "AD" badges, always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") wrapped in `NSLocalizedString` for proper screen reader pronunciation on VoiceOver.
**Action:** Ensure `isAccessibilityElement = true` and explicitly set `accessibilityLabel = NSLocalizedString("Advertisement", bundle: .module, comment: "Accessibility label for ad tag")` on abbreviation tags.
