
## 2024-05-24 - VoiceOver pronunciation for abbreviated labels
**Learning:** Small labels like "AD" are read literally by screen readers (e.g., "A-D"), causing confusion.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement") for abbreviated badges, and ensure they are localized using `NSLocalizedString`.
