## 2026-05-18 - VoiceOver Pronunciation for Ad Abbreviations
**Learning:** VoiceOver reads the common UI abbreviation "AD" as the individual letters "A-D" rather than "Ad" or "Advertisement". For accessibility, abbreviated UI badges need full-word pronunciations.
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") for abbreviated UI badges using `NSLocalizedString` when configuring UIKit accessibility elements.
