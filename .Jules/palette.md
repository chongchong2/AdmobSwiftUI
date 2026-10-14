## 2024-05-24 - VoiceOver Pronunciation for Ad Badges
**Learning:** Screen readers like VoiceOver pronounce abbreviated labels like "AD" poorly (e.g. "A D"). Non-interactive UI elements used as visual badges also get ignored by default unless explicitly made accessible.
**Action:** Always set `isAccessibilityElement = true` and provide a full-word `accessibilityLabel` (e.g. "Advertisement") for abbreviated non-interactive badges, ensuring it's wrapped in `NSLocalizedString` for proper localization.
