
## 2024-10-26 - VoiceOver Pronunciation for UI Badges
**Learning:** Screen readers like VoiceOver pronounce short textual badges like "AD" awkwardly, and non-interactive `UILabel` badges might not be explicitly announced as accessibility elements by default.
**Action:** Always set `isAccessibilityElement = true` on `UILabel` badges and provide a full-word `accessibilityLabel` (e.g., `NSLocalizedString("Advertisement", bundle: .module, comment: "...")`) to ensure clear pronunciation and context for screen reader users.
