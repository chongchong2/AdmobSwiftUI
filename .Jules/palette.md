## 2024-05-24 - Full-word VoiceOver Labels for Ad Tags
**Learning:** The application uses "AD" as a text label in various native ad views (`NativeAdBannerView`, `NativeAdCardView`, `NativeLargeAdBannerView`). Abbreviations like "AD" can be mispronounced or misinterpreted by screen readers (e.g., VoiceOver).
**Action:** Always set `isAccessibilityElement = true` and provide a full-word, localized `accessibilityLabel` (e.g., `NSLocalizedString("Advertisement", ...)`).
