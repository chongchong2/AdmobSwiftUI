## 2024-08-15 - Abbreviated Badges VoiceOver
**Learning:** The "AD" badge label on native ad views causes VoiceOver to read "A D" or "Ad" which can be confusing to users relying on screen readers.
**Action:** Always provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges (e.g., use 'Advertisement' for 'AD' badges) to ensure proper screen reader pronunciation. Even these full-word accessibility labels must be wrapped in `NSLocalizedString`.
