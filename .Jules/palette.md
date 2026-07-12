## 2024-05-15 - VoiceOver Improvements for UI Badges
**Learning:** VoiceOver screen readers struggle with abbreviated UI badges (like 'AD'). Even with a localized visual badge, VoiceOver may mispronounce it.
**Action:** For all small UI badges that contain abbreviations, assign a full-word `accessibilityLabel` wrapped in `NSLocalizedString` (e.g., `accessibilityLabel = NSLocalizedString("Advertisement", bundle: .module, comment: "")`) to ensure correct screen reader pronunciation and proper localization.
