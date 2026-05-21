## 2024-05-21 - VoiceOver Accessibility for Ad Tags
**Learning:** Short abbreviations like "AD" are often spelled out letter-by-letter or mispronounced by VoiceOver, which creates a confusing experience for screen reader users trying to identify sponsored content.
**Action:** Use `accessibilityLabel = "Advertisement"` on UI elements that display brief "AD" labels so that screen readers pronounce the full word.
