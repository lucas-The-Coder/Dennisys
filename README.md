# Dennisys - Software That Works

A modern, high-performance portfolio website for **Dennisys**, a South African software engineering studio. Built with vanilla HTML, CSS, and JavaScript, deployed via GitHub Pages.

**Live Site:** [dennisys.co.za](https://dennisys.co.za)

---

## 📋 Project Overview

Dennisys is a boutique software development studio that specializes in three core services:

1. **Website Development** - Custom-built, fast, responsive web applications
2. **Mobile App Development** - Cross-platform apps for iOS and Android
3. **Automations** - Workflow automation and AI-driven systems integration

The website showcases the studio's capabilities, completed projects, development process, and provides contact methods for potential clients.

---

## 🗂️ File Structure

```
dennisys/
├── README.md           # Project documentation (this file)
├── CNAME              # GitHub Pages custom domain configuration
└── index.html         # Main website file (single-page application)
```

### File Descriptions

#### **CNAME**

- Contains: `lukedennis.co.za`
- Purpose: Configures GitHub Pages to use the custom domain `lukedennis.co.za`
- When GitHub Pages builds this repository, it automatically redirects traffic to the domain specified here

#### **index.html**

- **Type:** Single-page HTML application
- **Size:** ~40KB (includes all CSS and JavaScript)
- **Structure:** Complete website with sections for:
  - Navigation bar
  - Hero section with call-to-action
  - Services showcase
  - Project portfolio
  - Development process
  - Contact section
  - Footer

---

## 🎨 Website Sections

### 1. **Navigation & Hero**

- Fixed navigation bar with logo and menu links
- Responsive hamburger menu for mobile devices
- Hero banner with headline, tagline, and dual CTAs
- Animated elements with fade-up transitions

### 2. **Tech Stack Marquee**

- Horizontally scrolling display of technologies used
- Includes: Flutter, React, Python, Node.js, MongoDB, PostgreSQL, Firebase, Docker, AWS, etc.
- Interactive: pauses on hover

### 3. **Services Section**

Three service cards with detailed descriptions and technology tags:

| Service                     | Description                                    | Tech Stack                     |
| --------------------------- | ---------------------------------------------- | ------------------------------ |
| **Website Development**     | Fast, modern, SEO-ready web applications       | React, Vue.js, Next.js         |
| **Application Development** | Cross-platform mobile apps with AI integration | Flutter, Android, iOS, Flask   |
| **Automations**             | Workflow automation and API integrations       | Python, Webhooks, AI Pipelines |

### 4. **Work / Portfolio Section**

Showcases completed projects:

#### **LedgerMind** (Featured, Live)

- **Type:** Personal finance mobile app
- **Description:** Full-stack South African finance app with biometric auth, AI financial advisor (Ledger AI), budgets, savings goals
- **Tech:** Flutter, Flask, OpenAI GPT-4o, Android
- **Compliance:** FAIS, POPIA, SARS compliant

#### **TaskFlow** (Beta)

- **Type:** SaaS team task management
- **Description:** Workspaces, role-based access, real-time updates
- **Tech:** Flutter, Flask, MongoDB Atlas

#### **The Nitty Gritty Handyman** (Live)

- **Type:** Business website
- **Description:** Clean frontend for handyman services
- **Tech:** React 18, Vite, GitHub Pages

#### **Freshdesk Automation Pipeline** (Live)

- **Type:** Automation system
- **Description:** Automated ticket processing with API data fetching and Telegram notifications
- **Tech:** Python, Freshdesk API, SQL, Telegram Bot

### 5. **Process Section**

Four-step transparent development process:

1. **Discovery** - Understand requirements and constraints
2. **Architecture** - Design tech stack and data models
3. **Build & Iterate** - Development in working increments
4. **Ship & Support** - Production deployment and handover

### 6. **Contact Section**

Multiple contact methods:

- Email form with validation: `denniswluke@outlook.com`
- WhatsApp integration: `+27 84 419 1945`
- 24-hour response guarantee

### 7. **Footer**

- Copyright notice: © 2026 Dennisys (Pty) Ltd
- Navigation links
- Contact links
- GitHub profile link

---

## 🎯 Design & Features

### Design System

**Color Palette:**

```
Primary:      #00D4AA (Teal/Green)
Primary Dark: #00A884
Info:         #4D9EFF (Blue)
Warning:      #FFB547 (Amber)
Danger:       #FF4D6A (Red)
Background:   #080C14 (Dark Navy)
Elevated:     #161E2E
Surface:      #1C2638
Text Primary: #F0F4FF
Text Secondary: #8B9BB4
Text Tertiary: #4A5568
```

**Typography:**

- Headings: `Syne` (bold, 800 weight)
- Body: `DM Sans` (primary font)
- Code/Monospace: `DM Mono` (technical elements)

**Visual Effects:**

- Noise texture overlay on background
- Grid pattern underlay
- Animated gradient orbs in hero section
- Smooth scroll behavior
- Intersection Observer for fade-up animations
- Hover transitions and transformations

### Responsive Design

**Breakpoints:**

- **Desktop:** 1024px and up
- **Tablet:** 768px - 1023px
  - Services grid: 2 columns → 1 column
  - Projects grid: Single column
  - Process grid: 2 columns → 1 column
- **Mobile:** 768px and below
  - Hamburger menu replaces nav links
  - All grids adapt to single column
  - Reduced padding and font sizes
  - Fullwidth buttons and forms
- **Small Mobile:** 420px and below
  - Further optimized spacing and typography

### Interactive Features

1. **Mobile Menu Toggle**
   - Hamburger icon appears on screens ≤768px
   - Smooth open/close animation
   - Auto-close on link click or outside click

2. **Navigation Scroll Effect**
   - Padding adjusts on scroll
   - Border styling changes dynamically

3. **Contact Form**
   - Email validation
   - Redirect to email client on submit
   - Visual feedback (border color change on invalid input)

4. **Scroll Animations**
   - Elements fade in and slide up as they enter viewport
   - Uses Intersection Observer API
   - 600ms animation duration
   - Staggered delays for sequential elements

5. **Tech Marquee**
   - Infinite scrolling animation
   - Pauses on hover
   - Seamless loop with duplicated items

---

## 🛠️ Technical Stack

### Frontend

- **Language:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **No Build Tool Required:** Single HTML file, zero dependencies
- **Fonts:** Google Fonts (Syne, DM Sans, DM Mono)

### Build & Deployment

- **Hosting:** GitHub Pages
- **Domain:** Custom domain via CNAME file
- **Deployment Method:** Direct file push to `gh-pages` branch
- **CDN:** GitHub Pages automatic CDN

### JavaScript Libraries/APIs Used

- **Intersection Observer API** - For scroll-triggered animations
- **Click Event Handling** - For mobile menu toggle
- **Window Scroll Events** - For navigation effects

### Features Demonstrated

- Responsive CSS Grid layouts
- CSS custom properties (CSS variables)
- CSS animations and keyframes
- Linear gradients and blur effects
- SVG icons (embedded)
- Mobile-first responsive design
- Semantic HTML5 structure

---

## 📋 HTML Structure

```html
<body>
  ├──
  <nav>
    <!-- Fixed Navigation -->
    ├──
    <div.hero>
      <!-- Hero Banner Section -->
      ├──
      <div.tech-marquee>
        <!-- Scrolling Tech Stack -->
        ├──
        <section#services>
          <!-- Services Showcase -->
          ├──
          <div.work-section>
            <!-- Project Portfolio -->
            ├──
            <section#process>
              <!-- Development Process -->
              ├──
              <div.cta-section>
                <!-- Contact/CTA Section -->
                └──
                <footer><!-- Footer with Links --></footer></div.cta-section
              ></section#process
            ></div.work-section
          ></section#services
        ></div.tech-marquee
      ></div.hero
    >
  </nav>
</body>
```

---

## 🚀 Getting Started

### Local Development

1. **Clone the repository:**

   ```bash
   git clone https://github.com/lucas-The-Coder/Dennisys.git
   cd Dennisys
   ```

2. **Open in browser:**

   ```bash
   # Option 1: Direct file open
   open index.html

   # Option 2: Local server (Python 3)
   python -m http.server 8000
   # Then visit: http://localhost:8000

   # Option 3: Local server (Node.js)
   npx http-server
   ```

3. **Edit the file:**
   - Open `index.html` in your code editor
   - Make changes to HTML, CSS, or JavaScript
   - Save and refresh browser to see changes
   - No build step required!

### Customization

The website uses CSS custom properties (variables) defined in the `:root` selector, making it easy to customize:

```css
:root {
  --bg: #080c14; /* Background color */
  --primary: #00d4aa; /* Primary accent color */
  --primary-dark: #00a884;
  --info: #4d9eff; /* Secondary color */
  --warning: #ffb547; /* Warning color */
  --danger: #ff4d6a; /* Error color */
  --text1: #f0f4ff; /* Primary text */
  --text2: #8b9bb4; /* Secondary text */
  --text3: #4a5568; /* Tertiary text */
  --border: rgba(255, 255, 255, 0.06); /* Border color */
}
```

To change colors globally, modify these CSS variables.

---

## 📞 Contact & Links

**Email:** denniswluke@outlook.com

**WhatsApp:** +27 84 419 1945

**GitHub:** [lucas-The-Coder](https://github.com/lucas-The-Coder)

**Website:** [lukedennis.co.za](https://lukedennis.co.za)

---

## 📊 Project Statistics

- **Single HTML file:** True (no build process)
- **Lines of HTML:** ~1200
- **Lines of CSS:** ~900
- **Lines of JavaScript:** ~90
- **External Dependencies:** 0 (except Google Fonts CDN)
- **Responsive Breakpoints:** 3 (Desktop, Tablet, Mobile)
- **Animations:** 8+ (keframes-based and transition-based)
- **Services:** 3
- **Portfolio Projects:** 4
- **Process Steps:** 4

---

## 🔧 Browser Compatibility

- **Chrome:** ✅ Full support
- **Firefox:** ✅ Full support
- **Safari:** ✅ Full support
- **Edge:** ✅ Full support
- **Mobile Browsers:** ✅ Fully responsive (iOS Safari, Chrome Mobile, etc.)

**CSS Features Used:**

- CSS Grid ✅
- CSS Flexbox ✅
- CSS Variables ✅
- CSS Transforms ✅
- CSS Gradients ✅
- Intersection Observer API ✅

---

## 🎓 Learning Points

This project demonstrates best practices for:

1. **Semantic HTML5** - Proper document structure and accessibility
2. **Responsive Design** - Mobile-first approach with multiple breakpoints
3. **CSS Best Practices** - Variables, grid, flexbox, animations
4. **Performance** - Single file, no external JS libraries
5. **Accessibility** - Color contrast, semantic structure, interactive elements
6. **Modern JavaScript** - Arrow functions, event listeners, DOM manipulation
7. **UX/UI** - Smooth animations, intuitive navigation, clear information hierarchy

---

## 📄 License

This project is the property of **Dennisys (Pty) Ltd**. All rights reserved.

© 2026 Dennisys (Pty) Ltd

---

## 🚦 Deployment

### To Deploy Changes:

1. **Edit `index.html`** in your local repository
2. **Commit your changes:**
   ```bash
   git add index.html
   git commit -m "Update: [description of changes]"
   ```
3. **Push to GitHub:**
   ```bash
   git push origin main
   ```
4. **GitHub Pages automatically deploys** to `lukedennis.co.za`
   - Deployment typically takes 1-2 minutes
   - No build step required
   - Changes visible at the live URL after deployment

### Domain Configuration

The `CNAME` file is already configured with `lukedennis.co.za`. To use a different domain:

1. Update the `CNAME` file content to your domain
2. Configure DNS records at your domain provider to point to GitHub Pages
3. GitHub Pages will automatically recognize the domain

---

## 📝 Last Updated

**Date:** March 22, 2026

**Status:** Active and maintained

---

## ❓ FAQ

**Q: Can I use this as a template for my own website?**
A: This is a custom project for Dennisys. For a new project, fork or create a new repository with your own branding.

**Q: How do I change the text/content?**
A: Edit the HTML directly in `index.html`. Search for the section you want to modify and update the text.

**Q: How do I add/remove projects?**
A: Locate the "projects-grid" section in `index.html`, duplicate or remove a "project-card" element, and update the content.

**Q: Is there a backend?**
A: No backend is required. The contact form redirects users to their email client. For email automation, you'd need to integrate a service like Formspree or EmailJS.

**Q: How do I add animations?**
A: Use CSS keyframes or transitions. Modify the `<style>` section in the HTML file.

---

## 🤝 Contributing

For internal changes or improvements, please follow the commit message format:

```
git commit -m "type: description"

Types:
- feat: New feature
- fix: Bug fix
- update: Content or styling update
- docs: Documentation changes
- refactor: Code restructuring
```

---

## 📞 Support & Contact

For questions or issues related to this project, contact:

- **Email:** denniswluke@outlook.com
- **Response Time:** Within 24 hours
