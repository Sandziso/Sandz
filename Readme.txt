====================================================================
              SANDZISO MAMBA - PORTFOLIO WEBSITE
====================================================================

📁 PROJECT OVERVIEW
-------------------
A modern, responsive portfolio website showcasing my skills, projects, 
and experience as a Computer Science student and Full-Stack Developer.

🌐 LIVE DEMO: [Your Portfolio URL]
📧 EMAIL: mlungisimamba01@gmail.com
📱 PHONE: (+268) 7854 5189 | (+27) 78 143 0934

====================================================================

🚀 FEATURES
-----------
✅ Fully Responsive Design
✅ Advanced CSS Animations & Transitions
✅ Smooth Scrolling Navigation
✅ Interactive Portfolio Filtering
✅ Dynamic Typing Effect (Hero Section)
✅ Scroll-Triggered Animations
✅ Working Contact Form with PHP
✅ Mobile-First Design
✅ SEO Optimized
✅ Fast Loading Performance

====================================================================

🛠 TECHNICAL STACK
------------------
Frontend:
• HTML5, CSS3, JavaScript (ES6+)
• CSS Grid & Flexbox
• CSS Custom Properties (Variables)
• AOS (Animate On Scroll) Library
• Bootstrap Icons

Backend:
• PHP (Contact Form)
• SMTP Email Configuration

====================================================================

📁 PROJECT STRUCTURE
--------------------
portfolio-website/
│
├── 📄 index.html                 # Main website file
├── 📄 contact.php                # PHP contact form handler
├── 📄 README.txt                 # This file
│
└── 📁 assets/
    ├── 📁 css/                   # Stylesheets (if any external)
    ├── 📁 js/                    # JavaScript files (if any external)
    └── 📁 images/
        ├── profile.jpg           # Your professional photo
        └── 📁 projects/          # Project screenshots
            ├── homewareontap.jpg
            ├── mambarentals.jpg
            ├── cfci-church.jpg
            ├── hardware-api.jpg
            ├── timochi-takho.jpg
            └── edsa-website.jpg

====================================================================

⚙️ INSTALLATION & SETUP
-----------------------

1. LOCAL DEVELOPMENT SETUP
   -----------------------
   a. Download all files to your local machine
   b. Place all files in your web server directory (htdocs, www, etc.)
   c. Ensure your local server supports PHP (XAMPP, WAMP, MAMP, etc.)
   d. Open your browser and navigate to: http://localhost/portfolio

2. WEB HOSTING DEPLOYMENT
   ----------------------
   a. Upload all files to your web hosting server via FTP/cPanel
   b. Ensure the hosting supports PHP
   c. Update email configuration in contact.php if needed
   d. Test the contact form functionality

3. GITHUB PAGES (Static Version)
   ------------------------------
   a. Remove PHP contact form or replace with formspree/service
   b. Upload to GitHub repository
   c. Enable GitHub Pages in repository settings

====================================================================

📧 CONTACT FORM SETUP
---------------------

The contact form uses PHP mail() function. For better deliverability:

OPTION 1: BASIC PHP MAIL (Current Setup)
-----------------------------------------
• Works with most hosting providers
• Edit recipient email in contact.php (line ~15):
  $recipient = "mlungisimamba01@gmail.com";

OPTION 2: SMTP CONFIGURATION (Recommended)
------------------------------------------
Use PHPMailer for better email delivery:

1. Download PHPMailer: https://github.com/PHPMailer/PHPMailer
2. Replace contact.php with SMTP version
3. Configure your email provider settings

Example SMTP Configuration (Gmail):
• Host: smtp.gmail.com
• Port: 587
• Username: your-email@gmail.com
• Password: your-app-password

OPTION 3: FORM SUBMISSION SERVICE
---------------------------------
Use services like:
• Formspree.io
• Getform.io
• Netlify Forms

====================================================================

🎨 CUSTOMIZATION GUIDE
----------------------

1. PERSONAL INFORMATION
   --------------------
   Update the following sections in index.html:

   • Hero Section: Name, title, description
   • About Section: Personal info, bio
   • Contact Section: Contact details
   • Social Links: LinkedIn, GitHub, etc.

2. PROJECTS & PORTFOLIO
   --------------------
   Add your projects in the Portfolio section:

   • Update project images in assets/images/projects/
   • Modify project titles, descriptions, and links
   • Add/remove project categories as needed

3. SKILLS SECTION
   --------------
   Update skills and proficiency levels:

   • Modify skill names and percentages
   • Add/remove skill categories
   • Update skill icons if needed

4. COLOR SCHEME
   ------------
   Change the color scheme by modifying CSS variables in :root:

   :root {
     --primary: #2563eb;        /* Main brand color */
     --primary-dark: #1d4ed8;   /* Darker shade */
     --secondary: #475569;      /* Secondary text */
     --light: #f8fafc;          /* Background light */
     --dark: #0f172a;           /* Background dark */
   }

5. ANIMATIONS
   ----------
   Customize animations:

   • AOS (Animate On Scroll) settings in JavaScript
   • CSS transitions and transforms
   • Typing effect speed and texts

====================================================================

📱 RESPONSIVE BREAKPOINTS
--------------------------
• Mobile: < 768px
• Tablet: 768px - 992px
• Desktop: > 992px

====================================================================

🌐 BROWSER COMPATIBILITY
------------------------
✅ Chrome 60+
✅ Firefox 55+
✅ Safari 12+
✅ Edge 79+
✅ Mobile browsers

====================================================================

📝 CONTENT UPDATE CHECKLIST
---------------------------

BEFORE GOING LIVE:
[ ] Update personal information
[ ] Add professional profile photo
[ ] Add actual project screenshots
[ ] Verify all links work correctly
[ ] Test contact form functionality
[ ] Update social media links
[ ] Check mobile responsiveness
[ ] Test loading speed
[ ] Verify SEO meta tags
[ ] Add Google Analytics (optional)

====================================================================

🚀 PERFORMANCE OPTIMIZATION
---------------------------

1. IMAGE OPTIMIZATION
   • Compress all images (use TinyPNG, Squoosh)
   • Use WebP format for better compression
   • Implement lazy loading for images

2. CODE OPTIMIZATION
   • Minify CSS and JavaScript
   • Use CSS sprites for icons
   • Implement caching strategies

3. HOSTING OPTIMIZATION
   • Use CDN for assets
   • Enable Gzip compression
   • Use HTTPS for security

====================================================================

🔧 TROUBLESHOOTING
-------------------

COMMON ISSUES:

1. CONTACT FORM NOT WORKING
   • Check PHP support on server
   • Verify email configuration
   • Check server error logs
   • Test with different email service

2. ANIMATIONS NOT WORKING
   • Check AOS library is loaded
   • Verify JavaScript console for errors
   • Ensure proper internet connection for CDN

3. RESPONSIVE ISSUES
   • Check viewport meta tag
   • Test on different devices
   • Verify CSS media queries

4. IMAGES NOT LOADING
   • Check file paths and names
   • Verify image file permissions
   • Ensure correct file extensions

====================================================================

📞 SUPPORT
----------

For technical support or questions:
• Email: mlungisimamba01@gmail.com
• LinkedIn: linkedin.com/in/mlungisimamba
• GitHub: github.com/Sandziso

====================================================================

📄 LICENSE
----------
This project is open source and available under the MIT License.

You are free to:
• Use, copy, modify, merge, publish, distribute
• Use for personal or commercial projects
• Sublicense, and/or sell copies

Attribution is appreciated but not required.

====================================================================

🔄 UPDATE LOG
-------------
v1.0.0 - Initial Release (2025)
• Complete portfolio website
• Responsive design
• Contact form functionality
• Advanced animations

====================================================================

💡 FUTURE ENHANCEMENTS
----------------------
• Blog integration
• Dark/Light mode toggle
• Multi-language support
• Project case studies
• Testimonials section
• Downloadable resume
• Newsletter subscription
• Admin panel for content management

====================================================================

🎯 KEY FOCUS AREAS
-------------------
As a Computer Science student, this portfolio emphasizes:
• Full-Stack Web Development
• Modern JavaScript Frameworks
• Database Design & Optimization
• REST API Development
• Responsive UI/UX Design
• Problem-Solving Skills

====================================================================

Thank you for using my portfolio template!
Feel free to customize it to match your personal brand and style.

Best regards,
Sandziso Mamba
Computer Science Student & Full-Stack Developer