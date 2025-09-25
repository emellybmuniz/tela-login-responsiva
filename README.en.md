# Modern Login Screen
[🇺🇸 English](./README.en.md) | [🇧🇷 Português](./README.md)

![GitHub License](https://img.shields.io/github/license/emellybmuniz/tela-login-responsiva)
![GitHub language count](https://img.shields.io/github/languages/count/emellybmuniz/tela-login-responsiva)
![GitHub last commit](https://img.shields.io/github/last-commit/emellybmuniz/tela-login-responsiva)
![GitHub repo size](https://img.shields.io/github/repo-size/emellybmuniz/tela-login-responsiva)
![Project Status](https://img.shields.io/badge/Status%20-%20in%20development%20-%20%23EB3731)

A modern and responsive login screen with an elegant design, built with pure HTML5 and CSS3. It features smooth gradients, fluid animations, and an intuitive interface for a pleasant user experience.

---

### 📋 Index
- [Project Overview](#-project-overview)
- [Directory Structure](#-directory-structure)
- [Highlights & Features](#-highlights--features)
- [Technologies Used](#-technologies-used)
- [Prerequisites](#-prerequisites)
- [Installation](#-installation)
- [How to Use](#-how-to-use)
- [Configuration](#-configuration)
- [Responsiveness](#-responsiveness)
- [Validation and Error Handling](#-validation-and-error-handling)
- [Contribution](#-contribution)
- [Future Improvements](#-future-improvements)
- [License](#-license)
- [Author](#-author)

---

## 🚀 Project Overview

[![Project Demonstration](imagens/project-demo.gif)](https://emellybmuniz.github.io/tela-login-responsiva/)

A modern login interface that combines minimalist design with robust functionality. The project demonstrates advanced CSS3 techniques, including complex gradients, elaborate box-shadows, and adaptive responsive design, creating an engaging and professional visual experience.

**Context and Motivation:** Developed to demonstrate skills in modern interface design, focusing on creating reusable components and optimized user experiences.

**Key Benefits:**
- Clean and intuitive interface that reduces friction in the login process
- Responsive design that works perfectly on all devices
- Implementation of good accessibility and UX practices
- Clean and well-structured code, easy to maintain and expand

**Target Audience:** Front-end developers, UI/UX designers, and students interested in modern and responsive interfaces.

**Technical Concepts Demonstrated:** CSS Grid/Flexbox, CSS Custom Properties (variables), responsive design, Material Design Icons, advanced styling techniques, and performance optimization.

## 📂 Directory Structure

```bash
📦 tela-login-responsiva/
├── favicon/
│   └── favicon.ico            # Site icon
├── imagens/
│   ├── undraw_male_avatar_g98d.svg    # Main male avatar
│   └── undraw_profile_pic_re_iwgo.svg # Alternative avatar (profile)
├── styles/
│   └── style.css              # Main stylesheet with custom CSS
├── .gitattributes             # Git configurations for text normalization
├── index.html                 # Main application page
├── README.en.md               # Documentation in English
├── README.md                  # This documentation file
└── LICENSE                    # Project license
```

## ✨ Highlights & Features

### 🎨 **Modern Visual Design**
- Dynamic linear gradient from `#30cfd0` to `#330867` creating visual depth
- Harmonious color palette with accent color `#e32ac1` for interactive elements
- Multi-layered box-shadows for depth and elevation effect
- Optimized typography with clear visual hierarchy

### 📱 **Intelligent Responsive Interface**
- Adaptive layout that reorganizes in landscape orientation on small screens
- Strategic breakpoints for mobile devices (480px) and low screens
- SVG vector images that maintain quality at any resolution
- Mobile-first design with progressive enhancement

### 🎯 **Optimized User Experience**
- Input fields with integrated Material Design icons
- Smooth hover and focus animations with CSS transitions
- Clear visual states for user interactions
- Immediate visual feedback on all interactions

### ✅ **Structured and Accessible Form**
- Native HTML5 validation for email and required fields
- Semantic labels with descriptive icons
- Autocomplete configured for email and password
- Form structure optimized for screen readers

### 🔧 **Clean and Maintainable Code**
- CSS Custom Properties (CSS variables) for easy customization
- BEM-like architecture for class naming
- Semantic code with appropriate HTML5 elements
- Performance optimization with efficient resource loading

## 🛠️ Technologies Used

This project was built using the following technologies:

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-%234285F4.svg?style=for-the-badge&logo=google&logoColor=white)

### Technical Details:
- **HTML5**: Semantic structure with modern elements, accessible forms, and optimized meta tags
- **CSS3**: Flexbox, CSS Grid, Custom Properties, advanced gradients, animations, and media queries
- **Material Design Icons**: Google's icon system for a consistent interface
- **SVG Graphics**: Responsive and web-optimized vector illustrations

## ⚙️ Prerequisites

**Development Environment:**
- Modern web browser (Chrome 70+, Firefox 65+, Safari 12+, Edge 79+)
- Code editor (recommended: VS Code, Sublime Text, or similar)
- Optional local server (Live Server, Python HTTP Server, or similar)

## 📦 Installation

```bash
# 1. Clone this repository
$ git clone https://github.com/emellybmuniz/tela-login-responsiva.git

# 2. Navigate to the project directory
$ cd tela-login-responsiva

# 3. Open the index.html file in your browser
# Or use a local server for a better experience:
$ python -m http.server 3000
# Or if you have Live Server in VS Code, right-click -> "Open with Live Server"
```

**Alternative:** [Access the online version](https://emellybmuniz.github.io/tela-login-responsiva/)

## 💡 How to Use

1. **Application Access** - Open the `index.html` file in a modern web browser or access the online version
2. **Email Input** - Enter a valid email address in the field with the person icon
3. **Password Input** - Enter your password in the field with the padlock icon
4. **Login** - Click the "Enter" button to process the form (currently without backend)
5. **Additional Features** - Explore the links for "Forgot your password?" and "Create your account"

### Usage Examples:
```html
<!-- Basic form structure -->
<form action="#" class="login-form" autocomplete="on">
  <div class="form-field">
    <label for="email">
      <span class="material-symbols-outlined">person</span>
    </label>
    <input type="email" name="email" id="email" 
           placeholder="Enter your email" 
           autocomplete="email" required />
  </div>
</form>
```

## ⚙️ Configuration

### Color Settings (CSS Custom Properties):
- **--grad-start**: `#30cfd0` (Gradient start color)
- **--grad-end**: `#330867` (Gradient end color)
- **--primary-accent**: `#e32ac1` (Main accent color)
- **--card-bg**: `#ffffff` (Card background color)
- **--text-primary**: `#3d3d3d` (Main text color)

### Layout Settings:
```css
:root {
  --grad-start: #30cfd0;
  --grad-end: #330867;
  --primary-accent: #e32ac1;
  --card-bg: #ffffff;
  --font-family: Arial, Helvetica, sans-serif;
}
```

## 📱 Responsiveness

### Desktop (> 480px)
- Centralized card with a maximum width of 500px
- Vertical layout with generous spacing
- 180x180px avatar with shadow effects
- Expanded form fields

### Mobile (≤ 480px)
- Reduced card padding for maximum screen utilization
- Avatar resized to 120x120px
- Title reduced to 1.8rem
- Optimized spacing for touch

### Landscape on Small Screens (height ≤ 500px)
- Layout reorganized horizontally
- Avatar hidden to save space
- Card expanded to 700px wide
- Content distributed in columns

## 🛡️ Validation and Error Handling

### Implemented Validations:
- **Email Field**: Native HTML5 validation with `type="email"` and `required`
- **Password Field**: Required field validation with `required`
- **Autocomplete**: Configured for `email` and `current-password` following web standards

### Visual Handling:
- Clear focus states with custom outline
- Descriptive placeholders to guide the user
- Visual icons that reinforce the purpose of each field

## 🤝 Contribution

Contributions are always welcome and **highly appreciated!** Feel free to open an _issue_ or submit a _pull request_.

### How to contribute:
1. **Fork** this repository
2. **Clone** your fork: `git clone https://github.com/your-username/tela-login-responsiva.git`
3. **Create a branch** for your feature: `git checkout -b feature/new-feature`
4. **Make your changes** and test thoroughly
5. **Commit** your changes: `git commit -m 'Adds new feature'`
6. **Push** to the branch: `git push origin feature/new-feature`
7. **Open a Pull Request** with a detailed description of the changes

### Contribution Guidelines:
- Keep the code clean and well-commented
- Respect the existing naming structure
- Test responsiveness on different devices

## 🚀 Future Improvements

### Upcoming Features:
- [ ] **Backend Integration** - Implement real authentication with API
- [ ] **Advanced Validation** - Password strength verification and visual feedback
- [ ] **Dark Mode** - Toggle between light and dark themes
- [ ] **Micro-interaction Animations** - Loading states and advanced transitions
- [ ] **Password Recovery** - Functional modal for password reset
- [ ] **User Registration** - Integrated registration page
- [ ] **Social Login** - Authentication via Google, Facebook, GitHub
- [ ] **Remember Credentials** - Functional "Remember me" option

## 🔑 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for more details.

The MIT License allows commercial use, modification, distribution, and private use, requiring only the maintenance of the copyright notice.

## ✍️ Author

Crafted with ❤️ by **Emelly Beatriz**

📬 Get in touch:

📧 emellybmuniz@gmail.com |
💼 [Linkedin](https://www.linkedin.com/in/emellybmuniz) |
🐙 [Github](https://github.com/emellybmuniz)

---

⭐ **Liked the project?** Leave a star on the repository to support development!
