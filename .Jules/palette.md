## 2024-08-24 - Accessible Ad Tags in Native SwiftUI/UIKit components
**Learning:** Native ad tags frequently use truncated labels like 'AD' for space, which screen readers pronounce poorly or skip. We must add full-word localized `accessibilityLabel`s (e.g., "Advertisement") alongside visual tags.
**Action:** Always provide explicitly localized `accessibilityLabel` for short visual indicator badges in native ad components.
