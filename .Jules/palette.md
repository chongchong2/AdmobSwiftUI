## 2024-10-25 - [Accessibility Label for AD Badges]
**Learning:** iOS screen readers pronounce "AD" abbreviations confusingly. Full-word equivalents are required for VoiceOver accuracy, and these strings also need localization.
**Action:** Always assign a fully expanded, localized string (e.g., `NSLocalizedString("Advertisement", bundle: .module, comment: "Full word accessibility label for ad badge")`) to `accessibilityLabel` for abbreviated text badges.
