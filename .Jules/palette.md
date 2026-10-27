## 2024-05-15 - Ad Badge Screen Reader Pronunciation
**Learning:** The "AD" abbreviation used in badge labels across native ad views is read literally or phonetically by VoiceOver, causing confusion. Non-interactive UILabel badges also require explicit isAccessibilityElement activation.
**Action:** Always set isAccessibilityElement = true and provide a full-word accessibilityLabel wrapped in NSLocalizedString (e.g., "Advertisement") for abbreviated badges to ensure clear screen reader pronunciation.
