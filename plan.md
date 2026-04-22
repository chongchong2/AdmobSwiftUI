1. **Analyze UX/A11y Opportunities**: I have identified that the `starRatingView` in the AdMob native ad is an image representing the app's star rating, but as a `UIImageView`, it lacks an accessibility label. VoiceOver users cannot hear the rating value.
2. **Implement Enhancement**: In `Sources/AdmobSwiftUI/Native/NativeAdView.swift`, I will:
   - Make the `starRatingView` an accessibility element.
   - Assign it an `accessibilityLabel` based on the actual rating value (e.g., "4.5 out of 5 stars").
   - Fix a small typo in the code comments (`ratting` -> `rating`).
3. **Pre-commit**: Run pre-commit instructions to ensure standard checks are completed.
4. **Submit PR**: Provide a descriptive commit and request PR approval.
