## 2024-05-24 - Accessibility labels for Native Ad Tags
**Learning:** VoiceOver pronounces abbreviated badges like "AD" poorly (e.g., as "add" or "A.D."), leading to poor screen reader experiences. In iOS, even simple `UILabel` badges used as tags need `isAccessibilityElement = true` and full-word `accessibilityLabel` attributes (properly wrapped in `NSLocalizedString` for VoiceOver) to read them correctly.
**Action:** Always provide full-word accessibility labels (like "Advertisement") for abbreviated UI tags and explicitly set them as accessibility elements if they are standalone tags.
