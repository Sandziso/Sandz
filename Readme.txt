# Sandziso Mamba - Portfolio Website

![Portfolio Screenshot](assets/images/projects/portfolio-homepage.jpg)

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen?style=for-the-badge)](https://sandziso.github.io/Sandz)
[![GitHub](https://img.shields.io/badge/github-profile-blue?style=for-the-badge&logo=github)](https://github.com/Sandziso)
[![LinkedIn](https://img.shields.io/badge/linkedin-connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mlungisimamba)
[![Portfolio](https://img.shields.io/badge/portfolio-sandziso.github.io-purple?style=for-the-badge)](https://sandziso.github.io/Sandz)

---

## 📋 Overview

A modern, responsive portfolio website showcasing my journey as a final-year Computer Science student at Eduvos and aspiring Full-Stack Developer. This portfolio serves as a central hub for my professional presence, featuring my projects, technical skills, academic achievements, and contact information.

**Live Demo:** [https://sandziso.github.io/Sandz](https://sandziso.github.io/Sandz)

**Status:** 🟢 Live & Active

---

## ✨ Features

### 🎨 Design & User Experience
- **Clean, Modern Interface** – Professional design with smooth animations
- **Fully Responsive** – Optimized for mobile, tablet, and desktop devices
- **Smooth Scrolling** – Enhanced navigation experience
- **Typing Animation** – Dynamic role display in hero section
- **AOS Animations** – Scroll-triggered animations for engaging presentation

### 📱 Core Sections
- **Hero Section** – Professional introduction with social links
- **About Me** – Personal background and contact information
- **Skills Showcase** – Visual skill bars with animated progress
- **Resume Section** – Education and project experience timeline
- **Portfolio Grid** – Project showcase with filtering by category
- **Contact Area** – Multiple contact methods and CV download

### 🔧 Technical Features
- **Filterable Portfolio** – Categorized project display (All, Web Apps, APIs, Full-Stack)
- **Interactive Skills** – Animated progress bars that trigger on scroll
- **Tabbed Resume** – Switch between education and project views
- **Mobile Navigation** – Responsive hamburger menu for smaller screens
- **Scroll-to-Top** – Convenient navigation button
- **Header Scroll Effect** – Dynamic header styling on scroll

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Custom styling, animations, and responsive design |
| **JavaScript (ES6+)** | Interactive features and dynamic content |
| **Bootstrap Icons** | Professional icon set |
| **Google Fonts** | Poppins & Roboto typography |
| **AOS Library** | Scroll animations |
| **CSS Variables** | Consistent theming and easy maintenance |
| **Flexbox/Grid** | Modern layout techniques |

---

## 📁 Project Structure

```
portfolio-website/
│
├── 📄 index.html                 # Main portfolio homepage
├── 📄 README.md                  # Project documentation
│
├── 📁 projects/                  # Individual project pages
│   ├── 📄 homewareontap.html     # E-commerce platform
│   ├── 📄 mambarentals.html      # Rental property platform
│   ├── 📄 cfci-church.html       # Church management system
│   ├── 📄 hardware-api.html      # Java REST API
│   ├── 📄 timochi-takho.html     # Local services marketplace
│   └── 📄 edsa-website.html      # Non-profit organization platform
│
└── 📁 assets/
    ├── 📁 images/
    │   ├── 📄 profile.jpg        # Profile photo
    │   └── 📁 projects/           # Project screenshots
    │       ├── 📄 homewareontap-home.jpg
    │       ├── 📄 mambarentals-home.jpg
    │       ├── 📄 cfci-homepage.jpg
    │       ├── 📄 hardware-api-postman.jpg
    │       ├── 📄 timochi-takho-home.jpg
    │       └── 📄 edsa-homepage.jpg
    │
    └── 📁 files/
        └── 📄 Sandziso_Mamba_CV.pdf  # Downloadable resume
```

---

## 🎯 Project Pages

### Main Portfolio (`index.html`)
The central hub featuring:
- Professional introduction with typing animation
- Complete skills breakdown with visual progress bars
- Education timeline and project highlights
- Filterable project gallery (All, Web Apps, APIs, Full-Stack)
- Contact information and CV download

### Individual Project Pages (6 Detailed Pages)
Each project page includes:
- **Project Overview** – Detailed description and context
- **My Role** – Specific contributions and responsibilities
- **Technologies Used** – Complete tech stack breakdown
- **Key Features** – Comprehensive feature lists
- **Technical Implementation** – Database design, security, architecture
- **Development Process** – Step-by-step methodology
- **Screenshots Gallery** – Visual walkthrough
- **Live Demo Links** – Direct access to deployed projects

---

## 🚀 Featured Projects

| Project | Category | Description | Live Demo |
|---------|----------|-------------|-----------|
| [**HomewareOnTap**](projects/homewareontap.html) | Full-Stack E-commerce | Complete e-commerce platform with admin dashboard, payment integration, and inventory management | [🔗 Live](https://homewareontap.wuaze.com) |
| [**Mamba Rentals**](projects/mambarentals.html) | Full-Stack Rental Platform | Property rental platform with booking system, user authentication, and mobile money | [🔗 Live](https://mambarentals.wuaze.com) |
| [**CFCI Church Website**](projects/cfci-church.html) | Church Management System | Multi-role platform with member portal, event management, and donation system | [🔗 Live](https://cfci.wuaze.com) |
| [**Hardware Shop API**](projects/hardware-api.html) | Java REST API | Robust backend service for inventory management with JWT authentication | [🔗 GitHub](https://github.com/Sandziso/hardware-shop-api) |
| [**Timochi Takho**](projects/timochi-takho.html) | MERN Stack Marketplace | Local services marketplace with real-time messaging and mobile money | Coming Soon |
| [**EDSA Website**](projects/edsa-website.html) | Non-Profit Platform | NGO website with donation system, blog, and resource library | [🔗 Live](https://edsa.wuaze.com) |

---

## 💻 Local Development

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)
- Git (for version control)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sandziso/Sandz.git
   cd Sandz
   ```

2. **Open locally**
   - Simply open `index.html` in your browser
   - Or use a local server (Live Server extension for VS Code recommended)

3. **Customize**
   - Update personal information in `index.html`
   - Replace placeholder images in `assets/images/`
   - Modify colors in the `:root` CSS variables section
   - Update project links and descriptions

### File Structure Notes
- All project pages are linked from the main portfolio
- Ensure all image paths are correct when deploying
- The CV file should be placed in `assets/files/` with the correct filename

---

## 🎨 Customization Guide

### Colors
The portfolio uses CSS variables for easy theming. Modify in `index.html`:

```css
:root {
  --primary: #6366f1;        /* Main brand color */
  --primary-dark: #4f46e5;   /* Darker variant for hover */
  --secondary: #64748b;      /* Secondary text */
  --light: #f8fafc;          /* Background light */
  --dark: #0f172a;           /* Text dark */
  --accent: #f59e0b;         /* Accent color */
}
```

### Content Updates
- **Personal Info**: Update in the About section and contact details
- **Skills**: Modify skill percentages in the skill items
- **Projects**: Add/remove portfolio items in the portfolio grid
- **Resume**: Update timeline items in the resume section

---

## 🚀 Deployment

### GitHub Pages (Recommended)
1. Push code to a GitHub repository
2. Go to repository Settings → Pages
3. Select branch (usually `main` or `master`)
4. Your site will be published at `https://[username].github.io/[repository]`

### Custom Domain
1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update `BASE_URL` in any configuration if needed

### Free Hosting Alternatives
- **InfinityFree** – Free PHP/MySQL hosting
- **000webhost** – Free with minimal ads
- **Netlify** – Drag-and-drop deployment
- **Vercel** – Excellent for static sites

---

## 📱 Responsive Design

The portfolio is fully optimized for:
- **Mobile Devices** – 320px and up (hamburger menu, stacked layout)
- **Tablets** – 768px and up (adjusted spacing, two-column layouts)
- **Desktops** – 992px and up (full experience)
- **Large Screens** – 1200px and up (max-width container)

---

## 🔧 Performance Optimizations

- **Lazy Loading** – Images load as needed
- **Minimal Dependencies** – Only essential libraries
- **Optimized Images** – Compressed for web
- **CSS Variables** – Efficient styling updates
- **Semantic HTML** – Better SEO and accessibility
- **Mobile-First Approach** – Faster on mobile devices

---

## 📄 License

This project is open-source and available under the **MIT License**. Feel free to use it as inspiration for your own portfolio.

See the [LICENSE](LICENSE) file for more details.

---

## 🙏 Acknowledgements

- **Bootstrap Icons** – Beautiful, open-source icons
- **Google Fonts** – Poppins and Roboto typefaces
- **AOS Library** – Scroll animations
- **Unsplash** – Placeholder imagery (to be replaced)
- **Eduvos** – Academic foundation and support
- **Mentors & Peers** – Continuous inspiration and feedback

---

## 📞 Contact & Connect

I'm actively seeking graduate developer roles, freelance opportunities, and collaborations on impactful projects.

| Method | Details |
|--------|---------|
| **Email** | [mlungisimamba01@gmail.com](mailto:mlungisimamba01@gmail.com) |
| **LinkedIn** | [linkedin.com/in/mlungisimamba](https://www.linkedin.com/in/mlungisimamba) |
| **GitHub** | [github.com/Sandziso](https://github.com/Sandziso) |
| **Portfolio** | [sandziso.github.io/Sandz](https://sandziso.github.io/Sandz) |
| **Location** | Eswatini |
| **Phone** | (+268) 7854 5189 |

---

## 🎓 About Me

I'm a final-year BSc Computer Science student at Eduvos with an **85.4% average** and a passion for building full-stack web applications that solve real problems. I've led development teams, deployed live projects, and I'm obsessed with clean code, security, and user experience.

**Currently focused on:**
- Full-stack development with modern technologies
- Cloud architecture (AWS certification in progress)
- Building solutions for African communities
- Open-source contributions

---

## 🔄 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | 2025 | Initial release with core features |
| 1.1.0 | 2025 | Added individual project pages |
| 1.2.0 | 2025 | Implemented filtering and animations |
| 1.3.0 | 2026 | Updated with new projects and content |

---

## 🤝 Contributing

While this is a personal portfolio, I welcome feedback and suggestions!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -m 'Add improvement'`)
4. Push to branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## ⭐ Support

If you find this portfolio helpful or inspiring:
- Star the repository on GitHub
- Share it with others
- Connect with me on LinkedIn
- Reach out for collaboration

---

**Built with ❤️ by Sandziso Mlungisi Mamba**  
*Final-Year Computer Science Student @ Eduvos*  
*Eswatini*

---

*"Every expert was once a beginner. Every masterpiece was once a work in progress."*
