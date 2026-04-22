## 2024-05-24 - Accessibility Labels for Native Ads
**Learning:** UIImageViews used for ratings (like `starRatingView` in AdMob) do not have intrinsic accessibility labels. VoiceOver users cannot interpret them without manual configuration.
**Action:** Always assign `isAccessibilityElement = true` and an informative `accessibilityLabel` (e.g., "Rating: 4.5 out of 5 stars") to visual rating indicators.
