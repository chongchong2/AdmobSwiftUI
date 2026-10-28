## 2024-05-24 - Accessibility Labels for Abbreviated Badges
**Learning:** The native ad components in this app frequently use brief "AD" text badges to identify advertisements. Without explicit accessibility labels, screen readers might mispronounce this or read it as individual letters without sufficient context.
**Action:** Always provide full-word `accessibilityLabel` strings (like "Advertisement") for abbreviated UI elements or badges, wrap them in `NSLocalizedString`, and set `isAccessibilityElement = true` when they are applied to non-interactive views like `UILabel`.
