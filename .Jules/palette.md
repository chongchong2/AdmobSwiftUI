## 2024-05-24 - Clear Accessibility Labels for Abbreviated Badges
**Learning:** VoiceOver reads short, capitalized labels like "AD" acronyms letter-by-letter ("A-D") or unclear, leading to poor screen reader context for critical UI elements like advertisements.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., 'Advertisement') for abbreviated badges and ensure they are wrapped in `NSLocalizedString` for proper localization across supported languages.
