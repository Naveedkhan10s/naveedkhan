# Naveed Khan - Professional Services Website

A modern, high-converting website featuring striking 3D animations and professional design for LinkedIn optimization and digital marketing services.

## 🌟 Features

### Design & Visuals
- **3D Canvas Animations**: Interactive 3D shapes (spheres, cubes, pyramids, torus, network visualizations)
- **Modern Gradient Design**: Professional blue and purple color scheme
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations and parallax effects
- **Professional Typography**: Clean, readable Inter font family

### Conversion-Focused Elements
- **Dual CTAs**: Prominent "Schedule Consultation" and "Download Template" buttons
- **Lead Capture Forms**: Contact form and email capture for template downloads
- **WhatsApp Integration**: Direct messaging link for instant communication
- **LinkedIn Connection**: Professional networking link
- **Success Stories**: Portfolio section with impressive metrics and case studies

### Sections Included
1. **Hero Section** - Engaging intro with 3D network animation
2. **Services** - 5 detailed service cards with unique 3D icons
3. **About** - Professional biography with 3D sphere animation
4. **Portfolio** - 3 case studies with results and metrics
5. **Download** - Lead magnet section with 3D torus animation
6. **Contact** - Comprehensive contact options with form

## 🚀 Quick Start

### Option 1: Open Directly (Simplest)
1. Download all three files: `index.html`, `styles.css`, `script.js`
2. Keep them in the same folder
3. Double-click `index.html` to open in your browser
4. That's it! The website works locally.

### Option 2: Deploy to Web Hosting

#### Using Netlify (Free & Recommended)
1. Go to [netlify.com](https://www.netlify.com/) and sign up
2. Drag and drop the folder containing all files
3. Your site is live! Netlify provides a free subdomain
4. Optional: Connect your custom domain in settings

#### Using Vercel (Free)
1. Go to [vercel.com](https://vercel.com/) and sign up
2. Click "New Project" → "Import" → upload your files
3. Deploy! Your site goes live in seconds
4. Optional: Add custom domain

#### Using GitHub Pages (Free)
1. Create a GitHub account at [github.com](https://github.com/)
2. Create a new repository named `your-username.github.io`
3. Upload `index.html`, `styles.css`, and `script.js`
4. Your site will be live at `https://your-username.github.io`

## ✏️ Customization Guide

### 1. Update Personal Information

#### Contact Details (in `index.html`)
Find line 436 and replace:
```html
<a href="https://wa.me/1234567890">  <!-- Replace 1234567890 with your number -->
<a href="https://linkedin.com/in/naveedkhan">  <!-- Replace with your LinkedIn URL -->
```

#### About Section
Find line 267 and update your biography

#### Stats & Metrics
Find lines 82-94 and update:
```html
<div class="stat-number">150+</div>  <!-- Your number -->
<div class="stat-number">85%</div>   <!-- Your percentage -->
<div class="stat-number">50+</div>   <!-- Your number -->
```

### 2. Change Colors

In `styles.css` lines 9-15:
```css
:root {
    --primary-blue: #2563eb;        /* Main brand color */
    --secondary-purple: #8b5cf6;    /* Accent color */
    --secondary-pink: #ec4899;      /* Secondary accent */
}
```

### 3. Modify Services

Each service card is around lines 114-240 in `index.html`
Available 3D shapes: `sphere`, `cube`, `pyramid`, `torus`, `octahedron`

## 📧 Email Collection Setup

To capture emails, integrate one of these services:

### EmailJS (Recommended - Free)
1. Sign up at emailjs.com
2. Get your service ID
3. Update downloadForm handler in script.js

### Formspree (Simple)
1. Sign up at formspree.io
2. Get your form endpoint
3. Update form action in HTML

### Mailchimp (Best for Lists)
Embed Mailchimp form in download section

## 🎨 3D Animation Customization

In `script.js` around line 334:

```javascript
// Change animation speed
rotationSpeed: 0.003,  // Lower = slower

// Change animation type
type: 'sphere',  // Options: sphere, cube, pyramid, torus, octahedron, network
```

## 📱 Testing

- Desktop browsers: Chrome, Firefox, Safari, Edge
- Mobile devices: iOS Safari, Android Chrome
- Use Chrome DevTools for responsive testing (F12)

## 🔧 SEO & Analytics

### Add Google Analytics
Add before `</head>`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🐛 Troubleshooting

**3D Animations Not Showing**
- Check browser console (F12)
- Ensure script.js is loading
- Try Chrome browser

**Forms Not Working**
- Verify form IDs in HTML match JavaScript
- Check backend integration
- Review console for errors

**Mobile Menu Issues**
- Clear cache
- Ensure JavaScript enabled
- Verify script.js loads

## 📄 File Structure

```
naveed-khan-website/
├── index.html      (Main HTML file)
├── styles.css      (All styling and design)
├── script.js       (3D animations and interactions)
└── README.md       (This file)
```

## 🎯 Next Steps

1. ✅ Customize with your information
2. ✅ Update WhatsApp and LinkedIn links
3. ✅ Set up email collection
4. ✅ Deploy to hosting
5. ✅ Add analytics
6. ✅ Test on mobile
7. ✅ Launch!

---

**Tech Stack**: HTML5, CSS3, Vanilla JavaScript, Canvas API
**Performance**: Optimized for speed and SEO
**Design**: Conversion-focused with professional aesthetics

Good luck with your digital marketing business! 🚀
