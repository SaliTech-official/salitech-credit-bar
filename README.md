# 🚀 SaliTech Credit Bar Component

A zero-dependency, self-contained React component for rendering a sleek, responsive, and animated agency/developer credit bar at the bottom of any website.

## ✨ Features
- 💎 **Zero Dependencies**: Pure React with dynamically injected CSS. No Tailwind or external CSS files required.
- 🎨 **Fully Customizable**: Props for brand name, URL, text, and accent color.
- ⚡ **RTL & Responsive**: Perfectly supports Persian/Arabic texts and all screen sizes.
- 🎆 **Sleek Animations**: Includes shimmer text effects, sweep lines, and glow effects on hover.

---

## 📦 Files Available
- `CreditBar.tsx`: TypeScript version (with interface definitions)
- `CreditBar.jsx`: JavaScript / JSX version

---

## 💻 Quick Usage

```jsx
import { CreditBar } from './CreditBar';

export default function App() {
  return (
    <div>
      {/* Your main content */}
      <CreditBar />
    </div>
  );
}
