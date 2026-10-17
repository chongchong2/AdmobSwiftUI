
## 2026-10-17 - VoiceOver pronunciation for abbreviated UI elements
**Learning:** Screen readers like VoiceOver may mispronounce abbreviated badges (like "AD" for Advertisement) as separate letters.
**Action:** Always provide full-word accessibilityLabel strings for abbreviated UI elements or badges and explicitly set isAccessibilityElement = true if they are non-interactive elements like UILabel.
