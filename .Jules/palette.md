## 2024-05-24 - Accessible "AD" Badges

**Learning:** When using abbreviated badges like "AD" to denote advertisements, screen readers may read them out literally (e.g., "A D") or incorrectly. It's important to provide a full-word `accessibilityLabel` (e.g., "Advertisement") and ensure this full word is also localized using `NSLocalizedString` for non-English users.
**Action:** Always verify if visual abbreviations need full-word accessibility labels for clarity, and remember to localize those accessibility labels independently of the visual text.
