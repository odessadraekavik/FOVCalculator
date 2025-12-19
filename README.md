# 🎯 Field of View Calculator

<div align="center">

![FOV Calculator](https://img.shields.io/badge/FOV-Calculator-blue?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Material Design](https://img.shields.io/badge/Material--Design-0081CB?style=for-the-badge&logo=material-design&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)

A beautiful, modern FOV (Field of View) calculator with **bidirectional conversion** for gaming and display configuration.

[🚀 **Try it Live**](https://odessadraekavik.github.io/FOVCalculator/) • [🐛 **Report Bug**](https://github.com/Kurosar/FOVCalculator/issues)

![FOV Calculator Screenshot](https://i.imgur.com/Cqf1310.png)

</div>

---

## ✨ Features

- **Bidirectional Conversion** - Convert between horizontal and vertical FOV
- **Real-time Updates** - Instant calculation as you adjust sliders
- **Resolution Presets** - Common resolutions (FHD, QHD, 4K, Ultrawide)
- **Custom Settings** - Manual resolution and aspect ratio inputs
- **Material Design** - Clean, professional UI
- **Responsive Layout** - Works on desktop and mobile

---

## 🚀 Quick Start

### **Instant Use (No Installation)**
1. **[Open the calculator](https://odessadraekavik.github.io/FOVCalculator/)** in your browser
2. **Click** the resolution card to select your display
3. **Adjust** FOV sliders to your preference
4. **Copy** the calculated values to your game settings

### **Local Development**
```bash
# Clone the repository
git clone https://github.com/Kurosar/FOVCalculator.git
cd FOVCalculator

# Open in browser (no build required!)
open index.html
```

---

## 🔧 Technical Details

### **Conversion Formula**
```javascript
// Horizontal to Vertical FOV
VFOV = 2 × arctan(tan(HFOV/2) × height/width)

// Vertical to Horizontal FOV  
HFOV = 2 × arctan(tan(VFOV/2) × width/height)
```

### **Technology Stack**
- **Vanilla JavaScript** - No frameworks, maximum compatibility
- **Material Design** - Google's design language
- **FontAwesome** - Icon set
- **CSS Grid & Flexbox** - Modern, responsive layouts
- **HTML5** - Semantic, accessible markup

---

## 📜 License

This project is licensed under the **GPL v3 License** - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ by [Kurosar](https://github.com/Kurosar)**

[⭐ **Star this repo**](https://github.com/Kurosar/FOVCalculator) if you find it useful!

</div>
