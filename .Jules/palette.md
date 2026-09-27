## 2026-09-27 - Native Ad Badges Accessibility
**Learning:** Native ad badges (like "AD") on iOS read as "A D" (letters) if not properly tagged, or the user won't know what it stands for, missing a critical context for accessibility. Full-word accessibility labels wrapped in `NSLocalizedString` should be added to abbreviated UI elements.
**Action:** Always provide full-word `accessibilityLabel` strings for abbreviated UI elements or badges (e.g., use 'Advertisement' for 'AD' badges) to ensure proper screen reader pronunciation. Wrap them in `NSLocalizedString` with `bundle: .module`.
