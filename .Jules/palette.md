## 2024-05-20 - VoiceOver Pronunciation for Badges
**Learning:** Abbreviated UI elements like "AD" badges are often mispronounced or spelled out by VoiceOver (e.g. "A D").
**Action:** Always add `isAccessibilityElement = true` and a full-word `accessibilityLabel` (e.g. "Advertisement") for abbreviated badges, and ensure they are localized.
