# Sharon BK - Professional Portfolio Website

A modern, dark-themed portfolio website with a minimalist design. Three main sections with an elegant layout matching professional standards.

## 📄 Website Structure

**Section 1: Hero/Home Page**
- Full-screen background image of a home office desk setup
- Large title "SHARON BK" with subtitle "Python Full Stack Developer"
- Two call-to-action buttons: Resume & Portfolio
- Social media links (Instagram, LinkedIn, GitHub, Facebook)
- Scroll indicator at the bottom

**Section 2: About Section**
- Two-column layout
- Left: Professional portrait photo
- Right: About heading, email, and professional bio
- Clean, minimal typography

**Section 3: Skills & Contact Section**
- Three-column layout:
  - **Column 1 (Skills):** Skill list with animated progress bars
  - **Column 2 (Get in Touch):** Email subscription field, contact icons, Resume download button
  - **Column 3 (Services):** What Can I Do section, Design Skills, Hobbies & Interests with icons
- Decorative sparkle icon in the bottom right
- Fixed navigation bar at the top

## 🖼️ Required Images

Place these images in the `images/` folder:

### 1. **desk-workspace.jpg** (Hero Background)
- Size: 1920×1080px minimum (HD recommended)
- Description: Home office desk setup photo from elevated side angle
- Elements: Monitor, laptop, keyboard, mouse, desk lamp, succulent plant, notebook
- Lighting: Monitor glow and warm ambient lighting
- **Critical:** This is the main hero background, so use high-quality,professional HD photo

### 2. **profile.jpg** (About Section)
- Size: 400×500px minimum (portrait orientation)
- Description: Professional headshot/portrait
- Framing: Chest-up, professional attire
- Background: Dark/neutral to match website theme

**No other images required.** All other visual elements are CSS-based.

## 🎨 Customization

### Update Text Content in `index.html`

Replace these placeholder values:
- Name: "SHARON BK"
- Title: "Python Full Stack Developer"
- Email: "sharon.bk.official@gmail.com"
- Phone: "+91 8247623805"
- About text: "Python Full Stack Developer crafting efficient, scalable, and user-focused web applications."

### Skills Section
Update the skill list with your skills and adjust progress bar widths (0-100%):
```html
<div class="progress-fill" style="width: 95%"></div>
```

### Services & Design Skills
Edit the text in the "WHAT CAN I DO?" and "DESIGN SKILLS" sections to match your expertise.

### Social Media Links
Replace `#` with your actual profiles in the hero section:
- Instagram
- LinkedIn
- GitHub  
- Facebook

## 🚀 Getting Started

1. **Add images** to the `images/` folder:
   - `desk-workspace.jpg` - Hero background
   - `profile.jpg` - About section photo

2. **Open the website:**
   ```
   Open index.html in your web browser
   ```

3. **Update content** in `index.html`:
   - Replace name, title, email, phone
   - Update skills list
   - Update services and hobbies
   - Add social media links

4. **No dependencies:** Runs on pure HTML/CSS/JavaScript

## 📱 Responsive Design

Website works perfectly on:
- Desktop (1920px+)
- Tablet (768px - 1024px)
- Mobile (320px - 767px)

## 🔧 Features

✅ **Dark Theme** - Professional #0a0a0a background with white text
✅ **HD Ready** - Optimized for high-resolution images
✅ **Smooth Animations** - Fade-ins, hover effects, scrolling animations
✅ **Navigation** - Fixed navbar with active section highlighting
✅ **Responsive** - Works on all device sizes
✅ **Fast Loading** - Optimized CSS/JavaScript
✅ **No Build Process** - Pure HTML/CSS/JS

## 📋 File Structure

```
portfolio-website/
├── index.html          # Main website structure
├── styles.css          # All styling (exact design match)
├── script.js           # Navigation & interactions
├── images/
│   ├── desk-workspace.jpg    (REQUIRED - Hero background)
│   └── profile.jpg           (REQUIRED - About portrait)
└── README.md           # This file
```

## 🎯 Design Specifications

- **Typography:** Montserrat (Google Fonts)
- **Colors:**
  - Background: #0a0a0a (Pure black)
  - Text: #ffffff (White)
  - Accents: White with transparency effects
  - Borders: rgba(255, 255, 255, 0.1-0.3)

- **Spacing:** 
  - Navbar height: 56px
  - Sections: 100-200px padding
  - Column gaps: 60px
  - Element gaps: 12-32px

- **Typography Sizes:**
  - Hero title: 3.5rem
  - Section headings: 2.5rem
  - Column headings: 1.3rem
  - Body text: 0.95-1.1rem

## 💾 Deployment

Deploy to free hosting:

1. **GitHub Pages**
   - Push to GitHub repository
   - Enable GitHub Pages in settings
   - Access via: username.github.io/repository-name

2. **Netlify**
   - Drag & drop the folder
   - Automatic deployment
   - Custom domain support

3. **Vercel**
   - Connect GitHub repo
   - Automatic deployments
   - Zero config

4. **Any static host** - Works with any web server

## 🔗 Important Notes

- Images should be **high-quality and optimized** for web
- Ensure `desk-workspace.jpg` is a professional photo (this is prominent on your hero section)
- Update all placeholder text before deploying
- Test on mobile devices before going live
- Keep image file names exactly as specified

## ✨ Tips for Best Results

1. **Hero Image Quality:** Spend time on getting the perfect workspace photo
2. **Profile Photo:** Use professional headshot with good lighting
3. **Optimize Images:** Compress before uploading to improve load time
4. **Update Links:** Add real social media and download links
5. **Test Responsiveness:** Check on phone/tablet before deploying
6. **Keep Content Fresh:** Update skills, services, and projects regularly

## 📞 Contact Section

The "GET IN TOUCH" section includes:
- Email subscription field
- Contact icons (phone, envelope, location)
- Resume download button

Modify these to match your preferences.

---

**Ready to use!** Just add images and update text content. No coding required!

**Last Updated:** April 2026

