## 2024-05-24 - Accessible Ad Tags
**Learning:** Screen readers (like VoiceOver) read abbreviations like "AD" literally (e.g. "A D"), which is confusing contextually when used as a badge. Non-interactive UILabels acting as badges are also sometimes skipped by VoiceOver unless explicitly marked as accessibility elements.
**Action:** Always add full-word `accessibilityLabel` strings (like "Advertisement") and set `isAccessibilityElement = true` with `.staticText` traits for UI badges like "AD", "PRO", etc., ensuring proper screen reader pronunciation.
