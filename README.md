# 🌱 Organic Foods Shop - Advanced CSS Project

<div align="center">

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

**A modern, responsive organic food e-commerce website built with advanced CSS techniques and SASS architecture**

[🚀 Live Demo](#) • [📖 Documentation](#documentation) • [🐛 Report Bug](https://github.com/BT-maker/advanced-css/issues) • [✨ Request Feature](https://github.com/BT-maker/advanced-css/issues)

</div>

---

## 📋 Table of Contents

- [🌟 Overview](#-overview)
- [✨ Features](#-features)
- [🛠️ Technologies](#️-technologies)
- [📁 Project Structure](#-project-structure)
- [🚀 Quick Start](#-quick-start)
- [💻 Development](#-development)
- [🎨 Components](#-components)
- [📱 Responsive Design](#-responsive-design)
- [🎯 Methodology](#-methodology)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📞 Contact](#-contact)

## 🌟 Overview

This project showcases a **modern organic food e-commerce website** designed with cutting-edge CSS techniques, SASS architecture, and responsive design principles. Built following industry best practices, it demonstrates advanced front-end development skills including modular CSS organization, BEM methodology, and smooth animations.

### 🎯 Project Goals

- Demonstrate advanced CSS and SASS capabilities
- Implement responsive design across all device types
- Showcase modern web development best practices
- Create a scalable and maintainable codebase
- Provide an excellent user experience

## ✨ Features

### 🎨 Design & UI
- **Fully Responsive Design** - Optimized for mobile, tablet, and desktop
- **Modern Interface** - Clean, intuitive user experience
- **Smooth Animations** - CSS-powered transitions and effects
- **Video Backgrounds** - Engaging multimedia content
- **Custom Icons** - SVG-based scalable graphics

### 🔧 Technical Features
- **SASS Architecture** - Modular and organized stylesheet structure
- **BEM Methodology** - Consistent naming conventions
- **Bootstrap Integration** - Responsive grid system
- **Form Validation** - Interactive user input handling
- **Cross-browser Compatibility** - Works across modern browsers
- **Performance Optimized** - Efficient CSS compilation and minification

## 🛠️ Technologies

| Technology | Version | Purpose |
|------------|---------|---------|
| **HTML5** | Latest | Semantic markup structure |
| **SASS/SCSS** | Latest | Advanced CSS preprocessing |
| **Bootstrap** | 5.3.3 | Responsive grid system |
| **CSS3** | Latest | Modern styling and animations |
| **Google Fonts** | - | Typography (Inter, Lato, Rubik) |

## 📁 Project Structure

```
advanced-css/
├── 📁 css/                    # Compiled CSS files
│   ├── style.css             # Main compiled stylesheet
│   └── style.css.map         # Source map for debugging
├── 📁 sass/                   # SASS source files
│   ├── 📁 abstracts/         # Variables, functions, mixins
│   │   ├── _variables.scss   # Global variables
│   │   ├── _mixins.scss      # Reusable mixins
│   │   └── _functions.scss   # Custom functions
│   ├── 📁 base/              # Base styles and resets
│   │   ├── _base.scss        # Base HTML element styles
│   │   ├── _typography.scss  # Font and text styles
│   │   ├── _utilities.scss   # Utility classes
│   │   └── _animations.scss  # Keyframe animations
│   ├── 📁 components/        # Reusable UI components
│   │   ├── _button.scss      # Button styles
│   │   ├── _card.scss        # Card component
│   │   ├── _form.scss        # Form elements
│   │   ├── _testimonial.scss # Testimonial cards
│   │   ├── _composition.scss # Image compositions
│   │   ├── _feature-box.scss # Feature boxes
│   │   └── _bg-video.scss    # Background video
│   ├── 📁 layout/            # Layout-related styles
│   │   ├── _header.scss      # Header section
│   │   └── _grid.scss        # Grid system
│   ├── 📁 pages/             # Page-specific styles
│   │   └── _home.scss        # Homepage styles
│   └── main.scss             # Main SASS entry point
├── 📁 images/                # Image assets
├── 📁 icons/                 # SVG icon files
├── 📄 index.html             # Main HTML file
├── 📄 package.json           # Node.js dependencies
└── 📄 README.md              # Project documentation
```

## 🚀 Quick Start

### Prerequisites

- **Node.js** (v14 or higher)
- **npm** or **yarn**
- **SASS** compiler

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/BT-maker/advanced-css.git
   cd advanced-css
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install SASS globally** (if not already installed)
   ```bash
   npm install -g sass
   ```

4. **Compile SASS to CSS**
   ```bash
   # One-time compilation
   sass sass/main.scss css/style.css
   
   # Watch for changes (recommended for development)
   sass sass/main.scss css/style.css --watch
   ```

5. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server like Live Server in VS Code
   ```

## 💻 Development

### Development Workflow

1. **Start SASS watcher**
   ```bash
   npm run sass:watch
   ```

2. **Make changes** to SASS files in the `sass/` directory

3. **View changes** by refreshing your browser

### Available Scripts

```bash
# Compile SASS (production)
npm run sass:build

# Watch SASS files for changes
npm run sass:watch

# Minify CSS for production
npm run css:minify
```

## 🎨 Components

### 🏠 Layout Components
- **Header** - Navigation and branding
- **Hero Section** - Main banner with call-to-action
- **Grid System** - Responsive layout structure

### 🧩 UI Components
- **Buttons** - Various button styles and states
- **Cards** - Product and content cards
- **Forms** - Contact and registration forms
- **Testimonials** - Customer review cards
- **Feature Boxes** - Service highlight boxes
- **Image Compositions** - Photo galleries and layouts

### 🎬 Interactive Elements
- **Background Videos** - Engaging video content
- **Animations** - Smooth CSS transitions
- **Hover Effects** - Interactive user feedback

## 📱 Responsive Design

### Breakpoint Strategy

| Device | Screen Size | Approach |
|--------|-------------|----------|
| **Mobile** | < 600px | Mobile-first design |
| **Tablet** | 600px - 900px | Optimized layouts |
| **Desktop** | > 900px | Full-featured experience |

### Responsive Features
- Flexible grid layouts
- Scalable typography
- Adaptive images
- Touch-friendly interactions
- Optimized navigation

## 🎯 Methodology

### BEM (Block Element Modifier)

This project follows BEM methodology for consistent and maintainable CSS:

```scss
// Block
.product-card {
  // Block styles
  
  // Element
  &__title {
    // Element styles
  }
  
  &__image {
    // Element styles
  }
  
  // Modifier
  &--featured {
    // Modifier styles
  }
  
  &--large {
    // Modifier styles
  }
}
```

### SASS Architecture (7-1 Pattern)

- **abstracts/** - Variables, functions, mixins
- **base/** - Reset, typography, base styles
- **components/** - Buttons, cards, forms
- **layout/** - Header, footer, grid
- **pages/** - Page-specific styles
- **themes/** - Theme variations (if applicable)
- **vendors/** - Third-party CSS (if applicable)

## 🤝 Contributing

We welcome contributions! Please follow these steps:

### How to Contribute

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit** your changes
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push** to the branch
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open** a Pull Request

### Contribution Guidelines

- Follow existing code style and conventions
- Write clear, descriptive commit messages
- Test your changes across different browsers
- Update documentation if necessary
- Ensure SASS compiles without errors

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

### Project Maintainer

**BT-maker**
- GitHub: [@BT-maker](https://github.com/BT-maker)
- Project Link: [https://github.com/BT-maker/advanced-css](https://github.com/BT-maker/advanced-css)

### Support

- 🐛 **Bug Reports**: [Create an issue](https://github.com/BT-maker/advanced-css/issues)
- 💡 **Feature Requests**: [Create an issue](https://github.com/BT-maker/advanced-css/issues)
- 💬 **Questions**: [Start a discussion](https://github.com/BT-maker/advanced-css/discussions)

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ by [BT-maker](https://github.com/BT-maker)

</div>
