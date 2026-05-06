## $(date +%Y-%m-%d) - Accessibility Label for Abbreviated Badges
**Learning:** Abbreviated UI badges (like 'AD') are often mispronounced by VoiceOver (e.g., 'A D'). They require full-word accessibility labels to ensure proper screen reader pronunciation in this app's native components.
**Action:** Always verify if a visual tag has a shortened label. If it does, set `isAccessibilityElement = true` and provide a fully expanded `accessibilityLabel` like "Advertisement".
