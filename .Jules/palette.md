## 2024-05-18 - Missing Accessibility Labels for "AD" Badges
**Learning:** Native ad badges that say "AD" are read as a short sound or acronym by VoiceOver, which isn't clear to users relying on screen readers. This is a common pattern in iOS AdMob integrations where the visual badge is required, but the screen reader experience is overlooked.
**Action:** Always provide a full-word `accessibilityLabel` (e.g., "Advertisement") for shortened visual badges. Even these must be localized using `NSLocalizedString` in Swift packages.
