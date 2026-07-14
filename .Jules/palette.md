## 2024-05-24 - Full-word Accessibility Labels for Badges
**Learning:** Abbreviated UI elements (like "AD" for Advertisement) can be confusing when read by VoiceOver, as they might be spelled out ("A D").
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") wrapped in `NSLocalizedString` for abbreviated UI elements or badges to ensure clear pronunciation.
