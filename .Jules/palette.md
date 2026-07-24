## 2024-05-24 - Expand abbreviated AD tags for VoiceOver
**Learning:** Abbreviated UI elements like "AD" badges are pronounced literally (e.g., "A D") by VoiceOver, which creates a disjointed accessibility experience.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated badges to ensure correct and localized screen reader pronunciation.
