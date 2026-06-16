## 2024-05-18 - VoiceOver for Abbreviated UI Tags
**Learning:** VoiceOver reads 'AD' as individual letters instead of 'Advertisement'. To fix this, always provide full-word accessibilityLabels for abbreviated badges.
**Action:** Add accessibilityLabel to all 'AD' ad tags, and ensure they are wrapped in NSLocalizedString with bundle: .module.
