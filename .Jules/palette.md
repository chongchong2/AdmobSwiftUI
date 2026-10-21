## 2024-11-21 - Accessible Labels for UI Badges
**Learning:** Abbreviated badges like "AD" are not pronounced clearly by VoiceOver.
**Action:** Always provide full-word accessibility labels (e.g., "Advertisement") and ensure `isAccessibilityElement = true` for non-interactive `UILabel`s so VoiceOver can recognize and read them accurately.
