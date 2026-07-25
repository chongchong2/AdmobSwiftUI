## 2024-07-25 - Accessibility for Abbreviated UI Elements
**Learning:** The UI contains small badge labels for ads ("AD"). Screen readers might pronounce abbreviated text awkwardly.
**Action:** Always provide full-word `accessibilityLabel` strings (e.g., "Advertisement" instead of "AD") and ensure they are localized using `NSLocalizedString` with `bundle: .module` for Swift packages.
