## 2024-10-24 - Provide full words for abbreviated badges in iOS
**Learning:** Screen readers like VoiceOver will spell out abbreviations (e.g., reading "A-D" for "AD").
**Action:** Use full words in `accessibilityLabel` (e.g., "Advertisement" instead of "AD") to ensure proper pronunciation, and make sure these new strings are properly localized in String Catalogs to match the rest of the app.
