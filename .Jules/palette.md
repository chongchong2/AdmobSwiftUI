## 2026-10-23 - Native Ad Badges Accessibility
**Learning:** Found that the 'AD' badges in NativeAdBannerView and NativeAdCardView lack proper VoiceOver accessibility labels. VoiceOver should read full words like 'Advertisement' for abbreviations to be properly understood. Additionally, as non-interactive UILabels used as decorative badges, they need isAccessibilityElement = true and an explicit accessibilityLabel.
**Action:** Adding full-word accessibility labels 'Advertisement' wrapped in NSLocalizedString and setting isAccessibilityElement to true for 'adTag' UI elements.
