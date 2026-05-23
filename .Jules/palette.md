## 2024-05-19 - Improve VoiceOver pronunciation for ad badges
**Learning:** Abbreviated UI elements like "AD" badges might be mispronounced by VoiceOver or other screen readers. They need full-word `accessibilityLabel` strings (like "Advertisement") for proper pronunciation.
**Action:** When adding abbreviated badges, always provide a descriptive, full-word `accessibilityLabel` to ensure correct and accessible screen reader output.
