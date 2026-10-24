## 2024-05-13 - Accessible Ad Badges
**Learning:** Native ad badges (often labeled simply "AD") are critical for compliance, but they can be poorly pronounced by VoiceOver (e.g., as the word "add") or completely missed if they aren't marked as accessibility elements.
**Action:** When creating non-interactive badges like "AD", explicitly set `isAccessibilityElement = true` and provide a clear `accessibilityLabel` using `NSLocalizedString` for "Advertisement" so screen readers read it clearly to users.
