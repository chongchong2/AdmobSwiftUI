## 2026-05-11 - Screen Readers and Abbreviated Ad Badges
**Learning:** For iOS VoiceOver users, abbreviated UI elements like "AD" badges are often mispronounced as single letters ("A D") or unrelated words ("add"). Providing full-word fallback text is crucial for accessibility comprehension.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") for abbreviated badges or UI elements, and use `NSLocalizedString` for proper localization.
