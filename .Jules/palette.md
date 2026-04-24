## 2026-04-24 - [iOS System Colors in Light/Dark Mode]
**Learning:** Using `.label` on a button with a solid background color like `.systemBlue` causes severe contrast issues in light mode because `.label` resolves to black, resulting in black text on a blue background.
**Action:** When designing colored call-to-action buttons in UIKit/SwiftUI, always use `.white` (or a specific contrasting color token) instead of adaptive colors like `.label` for text to ensure consistent readability across appearance modes.
