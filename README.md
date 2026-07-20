# 🔷 Nexus Business Solutions - Modern Landing Page

A fully responsive, modern, and feature-rich business landing page built with **HTML5**, **CSS3**, and **Bootstrap 5**. Designed for digital agencies, startups, and businesses looking to showcase their services professionally.

![Nexus Landing Page](https://images.unsplash.com/photo-1553877522-43269d4ea984?w=1200&h=630&fit=crop)

---

## ✨ Live Preview

https://ubaidullahzafar789-cyber.github.io/nexus-business-landing-page/

## 📁 Project Structure

```
nexus-business-landing-page/
│
├── index.html          # Main HTML file (includes inline JavaScript)
├── styles.css          # All custom styles + dark/light mode variables
├── images/             # Image assets folder (images loaded from Unsplash CDN)
└── README.md           # This file
```

---

## 🚀 Features

### Core Sections
| Section | Description |
|---------|-------------|
| **Hero** | Full-screen gradient hero with floating animated cards |
| **Services** | 6 service cards with gradient icons (Web, Mobile, Marketing, UI/UX, Cloud, Security) |
| **About** | Company story with feature highlights |
| **Stats** | Animated statistics counter section |
| **Testimonials** | Client reviews with star ratings |
| **Pricing** | 3-tier pricing cards (Starter, Professional, Enterprise) |
| **FAQ** | Accordion-style frequently asked questions |
| **Contact** | Contact form + contact information card |
| **Footer** | Newsletter signup, quick links, social media |

### Enhanced Features
| Feature | Details |
|---------|---------|
| 🌙 **Dark/Light Mode** | Toggle button with `localStorage` persistence |
| ⏳ **Loading Screen** | CSS-animated spinner with fade-out transition |
| 📊 **Scroll Progress Bar** | Gradient progress indicator at the top |
| ⬆️ **Back to Top Button** | Appears on scroll, smooth scroll to top |
| ♿ **Accessibility** | Skip links, ARIA labels, keyboard navigation, focus indicators |
| 🚀 **SEO Optimized** | Meta tags, Open Graph, Twitter Cards, semantic HTML |
| 📱 **Fully Responsive** | Mobile-first design, works on all screen sizes |
| 🎨 **Smooth Animations** | Fade-in on scroll, hover effects, floating cards |

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, animations, flexbox, grid
- **Bootstrap 5.3.2** - Grid system, components, utilities
- **Bootstrap Icons 1.11.1** - Icon library
- **Google Fonts (Inter)** - Typography
- **Vanilla JavaScript** - All interactions (no external JS file)

---

## 📸 Image Credits

All images are sourced from [Unsplash](https://unsplash.com) and loaded via CDN:

| Image | URL | Usage |
|-------|-----|-------|
| Hero | `https://images.unsplash.com/photo-1553877522-43269d4ea984?w=600&h=500&fit=crop` | Business team collaboration |
| About | `https://images.unsplash.com/photo-1522071820081-009f0129c71c?w=600&h=400&fit=crop` | Creative team working |
| Testimonial 1 | `https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=100&h=100&fit=crop&crop=face` | Sarah Johnson portrait |
| Testimonial 2 | `https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=100&h=100&fit=crop&crop=face` | Michael Chen portrait |
| Testimonial 3 | `https://images.unsplash.com/photo-1438761681033-6461ffad8d80?w=100&h=100&fit=crop&crop=face` | Emily Davis portrait |

---

## 🚀 How to Use

### 1. Clone or Download
```bash
 https://ubaidullahzafar789-cyber.github.io/nexus-business-landing-page/
```

### 2. Open in Browser
### 🌐 Live Website

Visit the live website here:

https://ubaidullahzafar789-cyber.github.io/nexus-business-landing-page/

### 3. Deploy to GitHub Pages
1. Push this repository to GitHub
2. Go to **Settings** → **Pages**
3. Select source: **Deploy from a branch** → **main** → **/(root)**
4. Your site will be live at `https://yourusername.github.io/nexus-business-landing-page/`

---

## 🎨 Customization

### Changing Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #0d6efd;
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* ... more variables */
}
```

### Adding New Services
Duplicate a service card in `index.html`:
```html
<div class="col-md-6 col-lg-4 fade-in-up delay-1">
    <div class="service-card">
        <div class="service-icon service-icon-7"><i class="bi bi-new-icon"></i></div>
        <h3 class="h4 mb-3">New Service</h3>
        <p class="text-muted">Description here...</p>
    </div>
</div>
```

### Changing Images
Replace Unsplash URLs in `index.html` with your own images:
```html
<img src="images/your-image.jpg" alt="Your description" loading="lazy">
```

---

## ♿ Accessibility Features

- **Skip to content** link for keyboard users
- Proper heading hierarchy (`h1` → `h2` → `h3`)
- `aria-label` on all interactive elements
- `role` attributes for semantic regions
- `focus-visible` outlines on all focusable elements
- `prefers-reduced-motion` media query support
- `prefers-contrast` media query support
- Screen-reader friendly star ratings

---

## 📱 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |
| Opera | 76+ |

---

## 📄 License

This project is open source and available under the **MIT License**.

Feel free to use, modify, and distribute for personal or commercial projects.

---

## 🙏 Credits

- **Bootstrap** - [getbootstrap.com](https://getbootstrap.com)
- **Bootstrap Icons** - [icons.getbootstrap.com](https://icons.getbootstrap.com)
- **Google Fonts** - [fonts.google.com](https://fonts.google.com)
- **Unsplash** - [unsplash.com](https://unsplash.com) (images)

---

## 📬 Contact

For questions or suggestions, feel free to reach out!

- **Website:** [nexus.com](https://nexus.com)
- **Email:** hello@nexus.com
- **Twitter:** [@nexus](https://twitter.com/nexus)

---

<p align="center">Made with ❤️ by Nexus Business Solutions</p>
