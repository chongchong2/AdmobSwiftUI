## 2024-05-24 - Accessibility Labels for Abbreviated Badges
**Learning:** Abbreviated UI elements like "AD" badges are often mispronounced or unclear on screen readers (e.g., VoiceOver).
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") for abbreviated badges, and ensure these accessibility strings are wrapped in `NSLocalizedString` for proper localization.
