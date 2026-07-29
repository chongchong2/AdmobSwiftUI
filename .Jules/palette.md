## 2024-05-24 - Accessibility Labels for Abbreviated Badges
**Learning:** VoiceOver reads the common "AD" badge abbreviation incorrectly (often pronouncing it like the word "add"). This causes confusion for screen reader users trying to distinguish sponsored content.
**Action:** Always provide a full-word `accessibilityLabel` (e.g., "Advertisement") for abbreviated UI badges, ensuring it is properly localized using `NSLocalizedString`.
