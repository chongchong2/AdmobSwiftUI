## 2024-05-18 - Missing Accessibility on non-interactive Badges
**Learning:** UIKit labels used as "AD" badges need `isAccessibilityElement = true` and `accessibilityLabel` set to a full word (e.g., "Advertisement") for VoiceOver to recognize and pronounce them correctly.
**Action:** Always check non-interactive visual badges for `isAccessibilityElement = true` and provide a descriptive `accessibilityLabel`.
