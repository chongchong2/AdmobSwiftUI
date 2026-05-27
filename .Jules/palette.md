
## 2026-05-27 - [VoiceOver Accessibility for Ad Badges]
**Learning:** Abbreviated UI labels like "AD" are commonly read out letter-by-letter or mispronounced by VoiceOver. Providing a full-word equivalent via `accessibilityLabel` significantly improves the screen reader experience.
**Action:** Always provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges (e.g., use 'Advertisement' for 'AD' badges) to ensure proper screen reader pronunciation.
