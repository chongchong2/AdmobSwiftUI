## 2024-05-13 - Add Accessibility Labels for Ad Tags
**Learning:** Native ad views use UILabels with abbreviated text ("AD") as badges. VoiceOver might not pronounce this abbreviation correctly or interpret it clearly, leading to a poor accessibility experience.
**Action:** Adding full-word accessibility labels wrapped in `NSLocalizedString` (e.g., `NSLocalizedString("Advertisement", bundle: .module, comment: "Full word for voice over")`) and setting `isAccessibilityElement = true` ensures VoiceOver reads these abbreviated visual badges correctly as "Advertisement".
