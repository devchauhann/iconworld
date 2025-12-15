# ✨ IconWorld

<div align="center">
  <img src="https://img.shields.io/badge/Icons-1500+-blue" alt="Icon Count" />
  <img src="https://img.shields.io/badge/License-MIT-green" alt="License" />
  <img src="https://img.shields.io/badge/- **Use our [issue template](https://github.com/devchauhann/iconworld/issues/new)
- Include browser version and reproduction steps
- Add screenshots for UI issues

### 💡 **Feature Requests**
- Check [existing requests](https://github.com/devchauhann/iconworld/issues) first0with-❤️-red" alt="Made with Love" />
  <img src="https://img.shields.io/badge/Mobile-Responsive-brightgreen" alt="Mobile Responsive" />
</div>

<br />

<p align="center">
  <strong>🎨 A beautiful, modern icon library with over 1500+ carefully crafted SVG icons</strong>
</p>

<p align="center">
  Beautifully designed, production-ready icons with real-time customization, favorites, and seamless search experience.
</p>

<div align="center">
  
[🚀 View Demo](https://your-demo-link.com) • [📖 Documentation](#features) • [🐛 Report Bug](https://github.com/devchauhann/iconworld/issues) • [💡 Request Feature](https://github.com/devchauhann/iconworld/issues)

</div>

---

## ✨ Features

### 🎯 **Core Features**
- **1500+ Premium Icons** - Carefully crafted SVG icons across multiple categories
- **⚡ Lightning Fast Search** - Instant icon discovery with smart suggestions
- **📱 Fully Responsive** - Perfect on desktop, tablet, and mobile devices
- **🎨 Real-time Customization** - Adjust color, size, stroke width on the fly
- **❤️ Favorites System** - Save your most-used icons for quick access
- **🌙 Dark/Light Theme** - Seamless theme switching with system preference detection

### 🛠️ **Advanced Customization**
- **Color Picker** - Custom colors with live preview
- **Size Control** - 16px to 96px with smooth scaling
- **Stroke Width** - Adjustable from 0.5px to 3px
- **Absolute Stroke** - Toggle for consistent stroke rendering
- **JSX Export** - One-click copy for React development

### 🏗️ **Developer Experience**
- **Clean JSX Output** - Ready-to-use React components
- **Copy to Clipboard** - Instant code copying with toast notifications
- **Category Organization** - Icons organized by Interface, Media, Business, etc.
- **Batch Operations** - Download entire collections

---

## 🚀 Quick Start

### Option 1: Clone & Run Locally

```bash
# Clone the repository
git clone https://github.com/devchauhann/iconworld.git

# Navigate to project directory
cd iconworld

# Open in your browser
open index.html
```

### Option 2: Use with Live Server (Recommended)

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

---

## 📁 Project Structure

```
iconworld/
├── 📄 index.html          # Main application file
├── 📊 data.json           # Icon database (1500+ icons)
├── 📋 LICENSE             # MIT License
└── 📖 README.md           # You are here!
```

### 🗂️ Data Structure

The `data.json` file contains all icon data:

```json
{
  "icons": [
    {
      "name": "activity",
      "category": "interface", 
      "svg": "<svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'><polyline points='22 12 18 12 15 21 9 3 6 12 2 12'></polyline></svg>"
    }
  ]
}
```

---

## 🎨 Categories

| Category | Description | Count |
|----------|-------------|-------|
| **Interface** | UI elements, buttons, navigation | 400+ |
| **Media** | Audio, video, image controls | 250+ |
| **Business** | Charts, analytics, office tools | 300+ |
| **Communication** | Mail, chat, social icons | 200+ |
| **Files** | Documents, folders, storage | 180+ |
| **Arrows** | Directional, navigation arrows | 170+ |

---

## 🛠️ Customization Guide

### Using the Modal Customizer

1. **Click any icon** to open the customization modal
2. **Adjust settings** in real-time:
   - 🎨 **Color**: Click color picker for custom colors
   - 📏 **Size**: Drag slider (16px - 96px)
   - ✏️ **Stroke Width**: Adjust line thickness
   - 🔒 **Absolute Stroke**: Toggle for consistent rendering
3. **Copy JSX** with your customizations applied

### Example Output

```jsx
<svg xmlns="http://www.w3.org/2000/svg" 
     width="32" height="32" 
     viewBox="0 0 24 24" 
     fill="none" 
     stroke="#3b82f6" 
     stroke-width="2.5" 
     stroke-linecap="round" 
     stroke-linejoin="round">
  <polyline points="22 12 18 12 15 21 9 3 6 12 2 12"></polyline>
</svg>
```

---

## 📱 Mobile Experience

IconWorld is built **mobile-first** with:

- **Touch-optimized** interface with proper tap targets
- **Responsive grid** that adapts to any screen size  
- **Mobile search** with fullscreen experience
- **Gesture-friendly** sidebar navigation
- **Performance optimized** for slower connections

---

## ⚡ Performance Features

- **Lazy Loading** - Icons load as you scroll
- **Virtual Scrolling** - Smooth performance with 1500+ icons
- **Optimized Search** - Debounced search with instant results
- **Local Storage** - Remembers theme and favorites
- **Zero Dependencies** - Pure HTML/CSS/JS for maximum speed

---

## 🎯 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 60+ | ✅ Full |
| Firefox | 55+ | ✅ Full |
| Safari | 12+ | ✅ Full |
| Edge | 79+ | ✅ Full |
| Mobile Safari | iOS 12+ | ✅ Full |
| Chrome Mobile | 60+ | ✅ Full |

---

## 🔧 Development

### Adding New Icons

1. **Add to data.json**:
```json
{
  "name": "new-icon",
  "category": "interface",
  "svg": "<svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='none' stroke='currentColor' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'><!-- your paths --></svg>"
}
```

2. **Follow SVG Guidelines**:
   - 24x24 viewBox
   - 2px stroke-width
   - `currentColor` for stroke
   - Round line caps and joins

### Customizing Themes

Edit CSS variables in the `:root` selector:

```css
:root {
  --primary: #18181b;
  --bg-app: #ffffff;
  --text-main: #09090b;
  /* Add your custom colors */
}
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 🎨 **Icon Contributions**
- Submit new icon designs following our style guide
- Ensure 24x24 viewBox and consistent stroke-width
- Include appropriate category classification

### 🐛 **Bug Reports**
- Use our [issue template](https://github.com/devchauhann/svgify/issues/new)
- Include browser version and reproduction steps
- Add screenshots for UI issues

### 💡 **Feature Requests**
- Check [existing requests](https://github.com/devchauhann/svgify/issues) first
- Provide clear use case and implementation ideas
- Consider backward compatibility

### 🚀 **Code Contributions**

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b amazing-feature`
3. **Commit** changes: `git commit -m 'Add amazing feature'`
4. **Push** to branch: `git push origin amazing-feature`
5. **Open** a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### 📋 **What this means:**
- ✅ Commercial use allowed
- ✅ Modification allowed  
- ✅ Distribution allowed
- ✅ Private use allowed
- ❗ License and copyright notice required

---

## 🙏 Acknowledgments

- **Icon Design**: Inspired by modern design systems
- **Color Palette**: Based on Tailwind CSS Zinc palette
- **Typography**: Inter and JetBrains Mono fonts
- **Community**: Thanks to all contributors and users

---

## 📊 Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/devchauhann/iconworld?style=social)
![GitHub forks](https://img.shields.io/github/forks/devchauhann/iconworld?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/devchauhann/iconworld?style=social)

</div>

---

## 🔗 Links

- **🌐 Website**: [iconworld.dev](https://iconworld.vercel.app)
- **📱 Mobile Demo**: [m.iconworld.dev](https://iconworld.vercel.app)  
- **📧 Contact**: [hello@iconworld.dev](mailto:devgurjar9897@gmail.com)

---

<div align="center">

**Made with ❤️ by [Dev Chauhan](https://github.com/devchauhann)**

⭐ **Star this repo** if you found it helpful!

</div>
