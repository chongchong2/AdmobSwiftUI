## 2024-05-18 - Improved Ad Badge Accessibility
**Learning:** Short or abbreviated labels like "AD" on badges are often mispronounced or lack context when read by VoiceOver. They must be explicitly marked as accessibility elements and given expanded full-word labels, even when used on custom tags.
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") wrapped in `NSLocalizedString` and set `isAccessibilityElement = true` for non-interactive `UILabel` badges.
