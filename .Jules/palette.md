## 2024-05-24 - Fix VoiceOver pronunciation for AD badges
**Learning:** VoiceOver mispronounces abbreviated UI elements like the "AD" badge. Providing a full-word accessibility label improves screen reader comprehension.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") for abbreviated badges, and wrap them in `NSLocalizedString` for proper localization.
