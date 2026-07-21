## 2024-05-24 - Screen Reader Pronunciation for Abbreviated Badges
**Learning:** VoiceOver often mispronounces abbreviated badges like "AD" or fails to convey the full context to visually impaired users.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") for abbreviated UI elements or badges, and ensure they are wrapped in `NSLocalizedString` for proper localization.
