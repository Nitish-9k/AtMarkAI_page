# 🎯 AtMarkAI Page

> A modern, responsive web application for AtMarkAI - Your AI-powered marking and assessment platform.

## 📚 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [File Organization](#file-organization)
- [Browser Support](#browser-support)
- [Performance](#performance)
- [Accessibility](#accessibility)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## 📖 About

AtMarkAI Page is a frontend web application designed to provide an intuitive and seamless user experience for the AtMarkAI platform. Built with modern web standards, this project focuses on responsive design, fast performance, and excellent user experience across all devices.

Whether you're here to evaluate papers, manage assessments, or track student progress, AtMarkAI delivers a clean and efficient interface.

## ✨ Features

### User Interface
- 🎨 **Modern & Clean Design** - Minimalist interface with intuitive navigation
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- ⚡ **Fast Performance** - Optimized for quick load times and smooth interactions
- 🌙 **Professional Styling** - Consistent color scheme and typography

### Functionality
- 🔐 **User Authentication** - Secure login and registration
- 📊 **Dashboard** - Real-time analytics and insights
- 📄 **Document Management** - Upload and manage assessment documents
- ✏️ **Interactive Forms** - Dynamic form validation and submission
- 🔍 **Search & Filter** - Find assessments quickly and efficiently
- 📈 **Progress Tracking** - Monitor evaluation progress in real-time

### Development
- 🔄 **Modular Code Structure** - Easy to maintain and extend
- 🎯 **SEO Optimized** - Structured markup for search engines
- ♿ **Accessible** - WCAG 2.1 compliance for inclusive design
- 🚀 **Production Ready** - Fully tested and optimized

## 🛠️ Tech Stack

| Technology | Usage | Percentage |
|-----------|-------|-----------|
| **HTML5** | Semantic markup & structure | 55.2% |
| **CSS3** | Styling, layouts & animations | 39.3% |
| **JavaScript** | Interactivity & dynamic features | 4.7% |
| **Python** | Backend utilities & processing | 0.8% |

### Additional Technologies
- CSS Grid & Flexbox for responsive layouts
- Vanilla JavaScript (no external frameworks)
- Python for backend API integration
- HTML5 APIs for enhanced functionality

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Git** - Version control system
  ```bash
  git --version  # Check if installed
  ```

- **Modern Web Browser** - One of the following:
  - Google Chrome (version 90+)
  - Mozilla Firefox (version 88+)
  - Safari (version 14+)
  - Microsoft Edge (version 90+)

- **Code Editor** (Optional but recommended):
  - Visual Studio Code
  - Sublime Text
  - Atom
  - WebStorm

- **Local Server** (Optional):
  - Python 3.x (built-in HTTP server)
  - Node.js with http-server
  - Live Server (VS Code extension)

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/Nitish-9k/AtMarkAI_page.git
cd AtMarkAI_page
```

#### 2. Open in Browser (Simple Method)

Double-click `index.html` or right-click and select "Open with" your preferred browser.

#### 3. Using Local Server (Recommended)

**Option A: Using Python**
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

**Option B: Using Node.js**
```bash
npx http-server
```

**Option C: Using VS Code Live Server**
- Install Live Server extension
- Right-click on `index.html`
- Select "Open with Live Server"

#### 4. Access the Application

Open your browser and navigate to:
- `http://localhost:8000` (if using Python)
- `http://localhost:8080` (if using Node.js)
- Your local server URL (if using Live Server)

## 📂 Project Structure

```
AtMarkAI_page/
│
├── index.html              # Main landing page
├── README.md               # Project documentation (this file)
├── LICENSE                 # License file
│
├── css/                    # Stylesheets directory
│   ├── style.css           # Main stylesheet
│   ├── responsive.css      # Mobile-responsive styles
│   ├── animations.css      # Animation and transition effects
│   └── fonts.css           # Font definitions
│
├── js/                     # JavaScript directory
│   ├── main.js             # Main application logic
│   ├── utils.js            # Utility functions
│   ├── api.js              # API integration
│   └── components.js       # Reusable component logic
│
├── assets/                 # Static assets directory
│   ├── images/             # Image files (PNG, JPG, SVG)
│   │   ├── logo.svg
│   │   ├── icons/
│   │   └── screenshots/
│   ├── fonts/              # Custom font files
│   └── videos/             # Video files (optional)
│
├── pages/                  # Additional pages (if applicable)
│   ├── about.html
│   ├── features.html
│   ├── pricing.html
│   └── contact.html
│
├── backend/                # Python backend utilities
│   ├── main.py
│   ├── config.py
│   └── requirements.txt
│
└── .gitignore              # Git ignore file
```

## 💻 Usage

### For Users

1. **Navigate to the Application**
   - Open the application in your web browser

2. **Create an Account** (if applicable)
   - Click "Sign Up" and fill in the required information
   - Verify your email address

3. **Login**
   - Enter your credentials on the login page
   - Access your dashboard

4. **Upload Documents**
   - Navigate to the upload section
   - Select files to evaluate
   - Submit for processing

5. **View Results**
   - Check the dashboard for assessment results
   - Download reports and feedback

### For Developers

#### Making Changes to Styles
1. Edit files in the `css/` directory
2. Changes reflect immediately in the browser (with auto-refresh)
3. Test across different devices using browser DevTools

#### Adding JavaScript Functionality
1. Create new functions in `js/` directory
2. Link the script in your HTML file
3. Test using browser console (F12)

#### Adding New Pages
1. Create `.html` file in the `pages/` directory
2. Include common header/footer components
3. Link from navigation menu

#### Working with Backend
1. Navigate to `backend/` directory
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python main.py`
4. API endpoints will be available at `http://localhost:5000`

## 📁 File Organization

### CSS Files
- **style.css** - Core styling and component styles
- **responsive.css** - Media queries for different screen sizes
- **animations.css** - Keyframe animations and transitions
- **fonts.css** - Font imports and definitions

### JavaScript Files
- **main.js** - Application initialization and main logic
- **utils.js** - Reusable utility functions (date formatting, validation, etc.)
- **api.js** - API calls and data fetching
- **components.js** - Interactive component handlers

### Image Assets
- **Logo files** - SVG and PNG formats
- **Icons** - UI icons and graphics
- **Screenshots** - Documentation images
- **Hero images** - Landing page visuals

## 🌐 Browser Support

| Browser | Minimum Version | Status |
|---------|-----------------|--------|
| Chrome | 90+ | ✅ Fully Supported |
| Firefox | 88+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Edge | 90+ | ✅ Fully Supported |
| IE 11 | N/A | ❌ Not Supported |

## ⚡ Performance

### Optimization Tips
- Images are optimized for web (compressed and appropriately sized)
- CSS is minified for production
- JavaScript is lazy-loaded where possible
- Caching strategies implemented for faster repeat visits

### Performance Metrics
- **First Contentful Paint (FCP)** - < 1.5 seconds
- **Largest Contentful Paint (LCP)** - < 2.5 seconds
- **Cumulative Layout Shift (CLS)** - < 0.1
- **Time to Interactive (TTI)** - < 3.5 seconds

Check performance using:
- Chrome DevTools Lighthouse
- WebPageTest
- Google PageSpeed Insights

## ♿ Accessibility

This project follows **WCAG 2.1 Level AA** guidelines:

- ✅ Semantic HTML structure
- ✅ Proper heading hierarchy (H1 → H6)
- ✅ Alternative text for images
- ✅ Color contrast ratios (4.5:1 for text)
- ✅ Keyboard navigation support
- ✅ ARIA labels and roles
- ✅ Focus indicators
- ✅ Screen reader compatibility

Test accessibility using:
- Chrome DevTools Accessibility Inspector
- Axe DevTools
- WAVE Browser Extension
- Lighthouse Audit

## 🤝 Contributing

We welcome contributions! Follow these steps:

### 1. Fork the Repository
```bash
# Click the "Fork" button on GitHub
```

### 2. Clone Your Fork
```bash
git clone https://github.com/YOUR_USERNAME/AtMarkAI_page.git
cd AtMarkAI_page
```

### 3. Create a Feature Branch
```bash
git checkout -b feature/your-feature-name
# Example: feature/add-dark-mode
```

### 4. Make Your Changes
- Edit files as needed
- Test thoroughly in multiple browsers
- Follow the existing code style

### 5. Commit Your Changes
```bash
git add .
git commit -m "Add: Brief description of your changes"
# Examples:
# "Add: Dark mode toggle functionality"
# "Fix: Mobile menu alignment issue"
# "Update: Documentation for new features"
```

### 6. Push to Your Branch
```bash
git push origin feature/your-feature-name
```

### 7. Create a Pull Request
- Go to the original repository
- Click "New Pull Request"
- Select your branch and write a clear description
- Submit for review

### Code Style Guidelines
- Use clear, descriptive variable names
- Comment complex logic
- Follow existing code patterns
- Test across browsers before submitting

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

**MIT License Summary:**
- ✅ Free to use, modify, and distribute
- ✅ Must include license notice
- ✅ No warranty provided
- ❌ Cannot hold creator liable

## 📞 Support

### Getting Help

- **Documentation** - Check this README first
- **Issues** - Search existing [GitHub Issues](https://github.com/Nitish-9k/AtMarkAI_page/issues)
- **Discussions** - Join community discussions
- **Email** - Contact the maintainer

### Reporting Bugs

Found a bug? Please report it:

1. Check if issue already exists
2. Create a new issue with:
   - Clear title describing the bug
   - Steps to reproduce
   - Expected vs actual behavior
   - Browser and OS information
   - Screenshots if applicable

### Feature Requests

Have an idea? We'd love to hear it:

1. Create a GitHub Issue
2. Label it as "enhancement"
3. Describe the feature and why it would be useful
4. Include mockups or examples if possible

### Security Vulnerabilities

Found a security issue? Please email the maintainer privately instead of creating a public issue.

## 🎓 Learning Resources

### Web Development
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)

### Tools & Testing
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
- [Can I Use](https://caniuse.com/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)

### Design & UX
- [Material Design](https://material.io/)
- [Figma](https://www.figma.com/)
- [Color Palette Generator](https://coolors.co/)

## 🎉 Acknowledgments

- Built with ❤️ by the AtMarkAI team
- Thanks to all contributors
- Inspired by modern web design practices

## 📊 Project Stats

- **Language Composition**: HTML (55.2%), CSS (39.3%), JavaScript (4.7%), Python (0.8%)
- **Repository**: Nitish-9k/AtMarkAI_page
- **Status**: Active Development

---

### Quick Links

- [Repository](https://github.com/Nitish-9k/AtMarkAI_page)
- [Issues](https://github.com/Nitish-9k/AtMarkAI_page/issues)
- [Discussions](https://github.com/Nitish-9k/AtMarkAI_page/discussions)

**Last Updated**: June 2026

---

<div align="center">

Made with ❤️ for the AtMarkAI community

⭐ If you find this project helpful, please star it on GitHub!

</div>
