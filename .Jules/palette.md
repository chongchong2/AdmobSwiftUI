## 2024-05-24 - Provide full-word accessibility labels for abbreviated badges
**Learning:** Screen readers (like VoiceOver) mispronounce abbreviated badges like "AD" (reading it as the word "ad" rather than expanding it contextually, or conversely reading "A-D"). A full-word accessibility label is needed.
**Action:** Always provide an explicit `accessibilityLabel` with a full, localized word (e.g., "Advertisement") for abbreviated UI elements or badges to ensure correct VoiceOver pronunciation.
