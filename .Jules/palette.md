## 2024-05-18 - VoiceOver Ad Tag Accessibility
**Learning:** Found that "AD" badges in UIKit wrappers for Google Mobile Ads are read out as a single word or spelled awkwardly by VoiceOver. They are lacking `accessibilityLabel`.
**Action:** Need to set `accessibilityLabel = NSLocalizedString("Advertisement", bundle: .module, comment: "Accessibility label for ad tag")` on `adTag` elements to ensure screen readers announce them properly as "Advertisement", while keeping the localized "AD" visual text.
