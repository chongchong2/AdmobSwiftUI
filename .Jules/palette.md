## 2024-05-24 - Screen Reader Pronunciation for Abbreviated Badges
**Learning:** For abbreviated badges like "AD", VoiceOver might read out the letters literally or inaccurately. Wrapping them in full-word accessibility labels ensures correct screen reader pronunciation. Even these hidden labels must be localized using NSLocalizedString.
**Action:** Always provide a full-word `accessibilityLabel` localized string for short or abbreviated UI elements.
