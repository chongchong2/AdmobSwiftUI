## 2024-11-04 - VoiceOver Pronunciation for Ad Badges
**Learning:** Abbreviated UI elements like "AD" badges are often mispronounced by screen readers (e.g., VoiceOver may read "add") and lack interactivity by default in UIKit.
**Action:** Always set `isAccessibilityElement = true` on non-interactive UI elements used as badges, and provide a full-word `accessibilityLabel` (e.g., "Advertisement" instead of "AD") wrapped in `NSLocalizedString` for proper screen reader pronunciation and localization.
