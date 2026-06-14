## 2024-06-14 - VoiceOver Accessibility for Abbreviated Badges
**Learning:** Abbreviated UI elements like "AD" badges are mispronounced or skipped by VoiceOver, causing poor accessibility in ad components.
**Action:** Always provide full-word accessibility labels wrapped in `NSLocalizedString` (e.g., `NSLocalizedString("Advertisement", bundle: .module, ...)`) for abbreviated badges.
