<div align="center">

# 🚀 Hassan Dawood - Portfolio Website

### Agentic AI Engineer | Machine Learning Specialist

[![Live Demo](https://img.shields.io/badge/demo-live-success?style=for-the-badge)](https://your-username.github.io/portfolio)
[![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)

<img src="hassanagentic_ai.png" alt="Portfolio Preview" width="800px">

[View Demo](https://your-username.github.io/portfolio) · [Report Bug](https://github.com/your-username/portfolio/issues) · [Request Feature](https://github.com/your-username/portfolio/issues)

</div>

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Demo](#demo)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 About

A modern, responsive portfolio website designed to showcase my expertise in Agentic AI Engineering, machine learning projects, and technical capabilities. Built with clean code and professional design principles.

### Key Highlights

- 🎨 Modern UI/UX with smooth animations
- 📱 Fully responsive across all devices
- ⚡ Fast loading and optimized performance
- 🎭 Interactive elements and hover effects
- 📧 Integrated contact form
- 🔗 Social media integration

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **Responsive Design** | Seamless experience on mobile, tablet, and desktop |
| **Dark Theme** | Professional dark color scheme optimized for readability |
| **Smooth Animations** | Floating elements and scroll-triggered animations |
| **Skills Showcase** | Visual representation of technical expertise |
| **Project Portfolio** | Highlighted AI/ML projects with descriptions |
| **Contact Section** | Easy-to-use contact form for inquiries |
| **Social Links** | Direct links to LinkedIn, GitHub, and Email |
| **SEO Optimized** | Meta tags and semantic HTML for better discoverability |

---

## 🎥 Demo

<div align="center">

### [🌐 Live Demo](https://your-username.github.io/portfolio)

</div>

### Screenshots

<details>
<summary>View Screenshots</summary>

#### Desktop View
![Desktop View](screenshots/desktop.png)

#### Mobile View
![Mobile View](screenshots/mobile.png)

</details>

---

## 🛠️ Tech Stack

```text
Frontend:
├── HTML5          - Structure and semantic markup
├── CSS3           - Styling, animations, and responsive design
└── JavaScript     - Interactive features (optional)

Design:
├── Google Fonts   - Poppins typeface
├── Custom CSS     - Animations and transitions
└── Flexbox/Grid   - Responsive layouts

Tools:
├── Git            - Version control
├── GitHub Pages   - Hosting
└── VS Code        - Development environment
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Git (optional, for cloning)
- Code editor (VS Code recommended)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/portfolio.git
cd portfolio
```

2. **Open the project**

```bash
# Simply open the HTML file
open portfolio.html  # macOS
start portfolio.html # Windows
xdg-open portfolio.html # Linux
```

Or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

3. **View in browser**

Navigate to `http://localhost:8000` or simply double-click `portfolio.html`

---

## 🎨 Customization

### Personal Information

1. Open `portfolio.html` in your code editor
2. Search and replace the following:

| Element | Search For | Replace With |
|---------|-----------|--------------|
| Name | Hassan Dawood | Your Name |
| Title | Agentic AI Engineer | Your Title |
| Email | hassanagentic@gmail.com | your.email@example.com |
| LinkedIn | linkedin.com/in/hassan-dawood | Your LinkedIn URL |
| GitHub | github.com/hassan-dawood | Your GitHub URL |

### Color Scheme

Modify the CSS variables in the `:root` selector (around line 15):

```css
:root {
    --primary-color: #6366f1;      /* Indigo - Main accent */
    --secondary-color: #8b5cf6;    /* Purple - Secondary accent */
    --dark-bg: #0f172a;            /* Slate 900 - Dark background */
    --light-bg: #1e293b;           /* Slate 800 - Light background */
    --text-color: #e2e8f0;         /* Slate 200 - Text */
    --text-muted: #94a3b8;         /* Slate 400 - Muted text */
}
```

### Profile Image

Replace `hassanagentic_ai.png` with your image:

```bash
# Option 1: Keep the same filename
cp /path/to/your/image.png hassanagentic_ai.png

# Option 2: Use a different filename and update HTML (line 609)
<img src="your-image.png" alt="Your Name">
```

### Adding Projects

Locate the projects section (around line 644) and duplicate this template:

```html
<div class="project-card">
    <h3>🎯 Project Title</h3>
    <p>Brief description of your project and its impact...</p>
    <div class="tech-tags">
        <span>Technology 1</span>
        <span>Technology 2</span>
        <span>Technology 3</span>
    </div>
</div>
```

---

## 🌐 Deployment

### GitHub Pages (Recommended)

1. **Rename the main file**
```bash
mv portfolio.html index.html
git add .
git commit -m "Rename for GitHub Pages"
git push origin main
```

2. **Enable GitHub Pages**
   - Go to repository **Settings**
   - Navigate to **Pages** section
   - Source: Select `main` branch
   - Folder: `/ (root)`
   - Click **Save**

3. **Access your site**
   - URL: `https://your-username.github.io/portfolio/`
   - Usually live within 2-3 minutes

### Alternative Hosting Platforms

| Platform | Difficulty | Cost | Deploy Time |
|----------|-----------|------|-------------|
| [Netlify](https://netlify.com) | Easy | Free | < 1 min |
| [Vercel](https://vercel.com) | Easy | Free | < 1 min |
| [Render](https://render.com) | Easy | Free | < 2 min |
| [Firebase Hosting](https://firebase.google.com) | Medium | Free | 2-5 min |

#### Quick Deploy to Netlify

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Guidelines

- Follow existing code style and formatting
- Write clear, descriptive commit messages
- Test on multiple browsers before submitting
- Update documentation for any new features

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```text
MIT License - Copyright (c) 2024 Hassan Dawood
```

---

## 📬 Contact

<div align="center">

### Hassan Dawood

**Agentic AI Engineer**

[![Email](https://img.shields.io/badge/Email-hassanagentic%40gmail.com-red?style=for-the-badge&logo=gmail)](mailto:hassanagentic@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/hassan-dawood)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/hassan-dawood)

</div>

---

## 🙏 Acknowledgments

- **Font**: [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)
- **Icons**: Unicode Emojis
- **Inspiration**: Modern portfolio design trends
- **Color Palette**: Tailwind CSS color system

---

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/your-username/portfolio?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/your-username/portfolio?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/your-username/portfolio?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/your-username/portfolio?style=for-the-badge)

---

<div align="center">

### ⭐ Star this repo if you find it helpful!

**Made with ❤️ by Hassan Dawood**

[↑ Back to Top](#-hassan-dawood---portfolio-website)

</div>
