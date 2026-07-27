# Palette's UX Journal
## 2024-07-27 - Accessible Ad Badges
**Learning:** VoiceOver reads the abbreviated "AD" label literally (as "add" or "A D"), which can be confusing for screen reader users trying to distinguish ad content from regular content.
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") for abbreviated badges, and ensure they are wrapped in `NSLocalizedString` for proper localization.
