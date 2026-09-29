## 2024-05-18 - Missing localized and accessible ad tag in NativeAdBannerView
**Learning:** Found that `NativeAdBannerView` has an "AD" label without localized text using `NSLocalizedString` and doesn't have an expanded `accessibilityLabel` like "Advertisement" for VoiceOver users, though other views like `NativeAdCardView` and `NativeLargeAdBannerView` do include localization for their "AD" text.
**Action:** Always provide full-word accessibilityLabel (e.g. "Advertisement") for abbreviated badges like "AD", properly localized using `NSLocalizedString`.
