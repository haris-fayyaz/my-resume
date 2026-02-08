# Personal CV Website

A modern, fully responsive Personal CV / Portfolio Website built using **HTML and CSS only**.  
This project is deployed on **Vercel** and created for academic submission and professional portfolio use.

---

## Project Overview

This website represents my online **Curriculum Vitae (CV)**.  
It highlights my academic background, technical skills, experience, and projects in a clean, professional, and user-friendly layout.

The design focuses on:
-  **Readability** – Clean typography and well-organized sections
-  **Professional UI** – Modern design with smooth animations
-  **Responsiveness** – Works perfectly on all devices (mobile, tablet, desktop)
-  **Clean Code** – Well-structured, commented, and maintainable

---

## Features

### Core Features
- 🌐 **Fully Responsive Layout** – Optimized for mobile, tablet, and desktop devices
- 🎨 **Modern UI Design** – Clean, professional interface with gradient accents
- 🌓 **CSS-Only Dark Mode** – Toggle between light and dark themes (no JavaScript!)
- 📄 **Structured CV Sections** – About, Education, Skills, Experience, Projects, Contact
- 📥 **Download CV Option** – Downloadable PDF version of CV
- 📧 **Working Contact Form** – Form submission forwards to email automatically
- 🎯 **Icon Enhancements** – Bootstrap Icons for visual appeal
- ⚡ **Smooth Animations** – CSS animations for better user experience

### Technical Highlights
- **Pure HTML & CSS** – No JavaScript frameworks or external libraries
- **Mobile-First Design** – Responsive breakpoints for all screen sizes
- **CSS Variables** – Easy theme customization
- **Semantic HTML5** – Proper document structure for SEO
- **Cross-Browser Compatible** – Works on Chrome, Firefox, Safari, Edge

---

## Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Structure and content |
| **CSS3** | Styling, animations, and layout |
| **Google Fonts** | Typography (Poppins, Fira Code) |
| **Bootstrap Icons** | Modern icon library |
| **Formspree** | Contact form email integration |
| **Vercel** | Deployment and hosting |

**Note:** No JavaScript frameworks, libraries, or external CSS frameworks were used. This is a pure HTML/CSS project.


---

## 🌐 Live Deployment

### 🔗 **Live Website:**
**https://html-css-resume-hazel.vercel.app/**

### 📍 **Deployment Platform:** Vercel
- **Auto-deployment** from GitHub repository
- **Custom domain** support available
- **HTTPS** enabled by default
- **Global CDN** for fast loading

---

## 👤 Student Information

| Detail | Information |
|--------|------------|
| **Name** | Haris Fayyaz |
| **Batch** | 23 |
| **Degree** | BS Computer Science |
| **Semester** | 3rd Semester |
| **University** | FAST National University of Computer & Emerging Sciences, Lahore |
| **Email** | haris.binfayyaz@gmail.com |

---

## Project Sections

### 1. **Hero Section**
- Professional introduction with name and title
- Animated profile card with photo
- Call-to-action buttons
- Social media links

### 2. **About Me**
- Brief professional summary
- Key highlights and interests
- Quick facts (Education, Location, Availability)

### 3. **Education**
- Timeline-based layout
- Animated timeline dots
- Academic qualifications with dates
- Institution details

### 4. **Skills**
- Categorized skill sections
- Interactive hover effects
- Categories: Programming Languages, Frameworks, Databases, Tools

### 5. **Experience**
- Professional internship details
- Responsibilities and achievements
- Company information
- Duration badges

### 6. **Projects**
- Grid layout of 6 major projects
- Project descriptions and technologies
- Hover animations
- Technology tags

### 7. **Contact**
- Working contact form (Formspree integration)
- Contact information cards
- Email, phone, location details
- Form validation

---

## 🎨 Design Highlights

### Color Scheme
**Light Mode:**
- Primary: Purple (#6366F1)
- Accent: Cyan (#06B6D4)
- Background: White (#FFFFFF)
- Text: Dark Gray (#111827)

**Dark Mode:**
- Primary: Light Purple (#818CF8)
- Accent: Bright Cyan (#22D3EE)
- Background: Deep Navy (#0F172A)
- Text: Light Gray (#F1F5F9)

### Typography
- **Headings:** Poppins (Google Fonts)
- **Body:** Poppins (Google Fonts)
- **Code:** Fira Code (Google Fonts)

### Responsive Breakpoints
- **Desktop:** > 968px
- **Tablet:** 768px - 968px
- **Mobile:** < 768px

---

## 🚀 How to Run Locally

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.) - for editing

### Steps

1. **Clone the repository:**
```bash
git clone https://github.com/haris-fayyaz/my-resume.git
cd personal-cv-website
```

2. **Open in browser:**
- Simply double-click `index.html`
- OR right-click → Open with → Browser

3. **For development:**
- Use VS Code with Live Server extension
- OR use any local server

---

## 📥 Creating Downloadable PDF

The website includes a "Download CV" button. To make it work:

### Method 1: Print to PDF (Recommended)
1. Open `haris-cv.html` in browser
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Select "Save as PDF"
4. Save as `Haris_Fayyaz_CV.pdf` in the same folder

### Method 2: Online Converter
1. Visit https://www.web2pdfconvert.com/
2. Upload `haris-cv.html`
3. Download as `Haris_Fayyaz_CV.pdf`

### Method 3: Create in Word/Docs
1. Create CV in Microsoft Word or Google Docs
2. Export as PDF
3. Save as `Haris_Fayyaz_CV.pdf`

---

## 📧 Contact Form Setup

The contact form uses **Formspree** (free service):

### Features
-  Automatic email forwarding to: **haris.binfayyaz@gmail.com**
-  Spam protection included
-  Thank-you page redirect
-  No backend code required

### Configuration
Already configured in the HTML:
```html
<form action="https://formspree.io/f/xovaqavn" method="POST">
```

No additional setup needed – the form works out of the box!

---

## 🎯 Key Learning Outcomes

Through this project, I demonstrated:

1. **HTML5 Mastery**
   - Semantic elements
   - Form validation
   - Proper document structure

2. **CSS3 Expertise**
   - Flexbox and Grid layouts
   - CSS Variables for theming
   - Animations and transitions
   - Responsive design
   - CSS-only dark mode toggle

3. **Web Design Principles**
   - Mobile-first approach
   - User experience (UX)
   - Visual hierarchy
   - Accessibility

4. **Deployment**
   - Version control (Git/GitHub)
   - Continuous deployment (Vercel)
   - Domain management

---

## 📱 Responsive Design

### Desktop View (> 968px)
- Full navigation bar
- Two-column layouts
- Large hero section
- Grid-based project cards

### Tablet View (768px - 968px)
- Adjusted layouts
- Single column in some sections
- Optimized spacing

### Mobile View (< 768px)
- Single column layout
- Stacked elements
- Hidden navigation links
- Simplified UI
- Touch-friendly buttons

---

## 🌟 Unique Features

### 1. CSS-Only Dark Mode
No JavaScript needed! Uses CSS `:checked` selector:
```css
#theme-toggle:checked ~ body {
    --bg-main: #0F172A;
    --text-primary: #F1F5F9;
}
```

### 2. Animated Profile Card
- Rotating dashed border
- Hover lift effect
- Stats display
- Social links

### 3. Interactive Timeline
- Pulsing animated dots
- Gradient connectors
- Hover effects

### 4. Professional Forms
- Custom styling
- Icon-enhanced labels
- Focus states
- Validation

---

## 🔧 Customization Guide

### Change Colors
Edit CSS variables in `haris-styles.css`:
```css
:root {
    --primary: #6366F1;    /* Change primary color */
    --accent: #06B6D4;     /* Change accent color */
}
```

### Update Content
Edit `haris-cv.html`:
- Personal information (lines 50-100)
- Education (lines 177-204)
- Skills (lines 216-264)
- Projects (lines 309-430)
- Contact info (lines 456-478)

### Add New Sections
Follow the existing pattern:
```html
<section id="new-section" class="section">
    <h2 class="section-title">
        <i class="bi bi-icon-name"></i> Section Title
        <span class="title-line"></span>
    </h2>
    <!-- Content here -->
</section>
```

---

##  Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | Latest |  Fully Supported |
| Firefox | Latest |  Fully Supported |
| Safari | Latest |  Fully Supported |
| Edge | Latest |  Fully Supported |
| Mobile Browsers | All |  Fully Supported |

---

## 📝 Future Enhancements

Potential improvements for future versions:
- [ ] Add blog section
- [ ] Integrate testimonials
- [ ] Add certifications section
- [ ] Implement custom domain
- [ ] Add more projects
- [ ] Create multiple theme options
- [ ] Add print-optimized stylesheet

---

## 📄 License

This project is created for **academic purposes** as part of coursework at FAST-NUCES.  
Free to use for educational purposes with proper attribution.

---

## 🙏 Acknowledgments

- **FAST-NUCES** for the academic opportunity
- **Google Fonts** for beautiful typography
- **Bootstrap Icons** for modern iconography
- **Formspree** for free form handling
- **Vercel** for free hosting and deployment

---

## 📞 Contact

**Haris Fayyaz**  
📧 Email: haris.binfayyaz@gmail.com  
🎓 Student at FAST-NUCES, Lahore  
💼 Aspiring AI Engineer

---

## 📊 Project Statistics

- **Total Lines of HTML:** ~500
- **Total Lines of CSS:** ~1200
- **Files:** 5 HTML/CSS files
- **Icons Used:** 50+
- **Sections:** 7 main sections
- **Responsive Breakpoints:** 3


---

**Built with ❤️ using pure HTML & CSS**  
**No frameworks • No JavaScript • Just clean code**

---

*Last Updated: February 2026*  
*Version: 1.0.0*
