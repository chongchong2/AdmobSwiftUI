## 2024-05-24 - Accessibility Improvement for Ad Tags
**Learning:** Hardcoded "AD" tags in native ad views are not accessible to VoiceOver users because they are abbreviated and not marked as accessibility elements.
**Action:** Always mark these non-interactive informational UI elements as `isAccessibilityElement = true` and provide a localized, unabbreviated `accessibilityLabel` (e.g., "Advertisement") so that screen readers pronounce them correctly.
