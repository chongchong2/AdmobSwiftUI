## 2024-05-19 - Expanded Accessibility Labels for Abbreviations on iOS
**Learning:** iOS VoiceOver will literally read out abbreviations like "AD" instead of pronouncing them as "Ad" or "Advertisement", causing screen readers to spell out "A-D".
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") for abbreviated UI elements or badges to ensure proper screen reader pronunciation on iOS.
