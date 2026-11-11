## 2024-05-24 - Full-word Accessibility Labels for Badges
**Learning:** VoiceOver reads abbreviated UI elements like "AD" badges poorly.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") and ensure they are wrapped in `NSLocalizedString` (e.g., `NSLocalizedString("Advertisement", bundle: .module, comment: "...")`) for correct localization and screen reader pronunciation. Set `isAccessibilityElement = true` for non-interactive elements like UILabels when applying the label.
