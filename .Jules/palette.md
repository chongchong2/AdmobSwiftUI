## 2024-05-18 - Expanding Abbreviated Accessibility Labels
**Learning:** Abbreviated UI elements like "AD" badges sound unnatural or confusing when read by VoiceOver in iOS. They must be expanded using full-word strings like "Advertisement". Even when expanding strings specifically for accessibility labels, they still require `NSLocalizedString` wrapping for internationalization support.
**Action:** Always provide full-word `accessibilityLabel` attributes for abbreviated badges/icons and ensure they are wrapped in `NSLocalizedString` just like visible UI text.
