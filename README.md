# 🚀 Professional Portfolio Website - Nurfazlin Mat Tamidi

A modern, responsive single-page application (SPA) portfolio showcasing software engineering expertise in AI and full-stack development.

## ✨ Features

### Design
- **Dark Mode Theme**: Sleek black/grey background with electric blue accent color
- **Modern Minimalist UI**: Clean sans-serif typography (Inter font)
- **Fully Responsive**: Mobile-first approach with Flexbox/Grid layouts
- **Micro-animations**: Fade-in on scroll, hover effects, and smooth transitions

### Sections
1. **Hero Section**: Eye-catching introduction with name, title, and call-to-action
2. **About Me**: Timeline-based education and work experience display
3. **Skills**: Interactive grid of technical skills with hover effects
4. **Projects**: Responsive card grid showcasing 4 major projects
5. **Contact**: Interactive modal with contact form and direct links

### Interactivity
- Sticky navigation with smooth scrolling
- Hamburger menu for mobile devices
- Modal contact form with backdrop and ESC key support
- Scroll-triggered animations
- Project card 3D tilt effects
- Active navigation highlighting

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Custom Properties, Animations
- **Vanilla JavaScript**: No frameworks, pure JS for optimal performance
- **Font Awesome 6.4.0**: Icons
- **Google Fonts**: Inter font family

## 📁 Project Structure

```
eportfolio/
│
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
└── README.md           # Documentation
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required!

### Installation

1. Clone or download the repository
2. Open `index.html` in your web browser
3. That's it! The portfolio is ready to view.

### Deployment

This is a static website that can be deployed to:
- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Drag and drop deployment
- **Vercel**: Zero-config deployment
- **Any web hosting service**: Upload files via FTP

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above (multi-column layouts)
- **Tablet**: 768px - 1199px (adjusted layouts)
- **Mobile**: Below 768px (single-column, hamburger menu)
- **Small Mobile**: Below 480px (optimized for small screens)

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --bg-primary: #0a0a0a;
    --bg-secondary: #1a1a1a;
    --accent-color: #00d9ff;
    /* ... */
}
```

### Content
Update content directly in `index.html`:
- Personal information in the Hero section
- Education and experience in the About section
- Skills in the Skills section
- Project details in the Projects section

### Adding Projects
Copy the `.project-card` structure in `index.html` and customize:
```html
<div class="project-card fade-in-scroll">
    <!-- Your project content -->
</div>
```

## 📧 Contact Form Integration

The contact form currently shows an alert on submission. To integrate with a backend:

### Option 1: FormSubmit (No backend required)
```html
<form action="https://formsubmit.co/your@email.com" method="POST">
```

### Option 2: Netlify Forms
Add `netlify` attribute to form:
```html
<form name="contact" netlify>
```

### Option 3: Custom Backend
Modify the form submission handler in `script.js` to send data to your API.

## 🔧 Advanced Features (Optional)

The `script.js` file includes commented-out optional enhancements:
- **Typing Effect**: Animated typing for hero title
- **Cursor Trail**: Custom cursor trail effect

Uncomment the relevant sections to enable these features.

## 📝 To-Do

- [x] ~~**Add profile picture**~~ ✅ **COMPLETED** - Profile picture (image.jpg) added to About section
- [ ] Add actual project screenshots/images
- [x] ~~Upload CV PDF and link to download button~~ ✅ **COMPLETED** - CV linked to Google Drive
- [x] ~~Add live demo links for projects~~ ✅ **COMPLETED** - All projects linked (YouTube demos & live site)
- [ ] Add Google Analytics (optional)
- [ ] Add meta tags for SEO
- [ ] Create favicon

## 🖼️ Adding Your Profile Picture

1. Save your profile picture (PNG format recommended) in the same folder as `index.html`
2. Name it something like `profile.png`
3. In `index.html`, find the profile section (around line 56-58)
4. Replace this line:
   ```html
   <i class="fas fa-user"></i>
   ```
   With:
   ```html
   <img src="profile.png" alt="Nurfazlin Mat Tamidi" style="width: 100%; height: 100%; object-fit: cover;">
   ```

The circular frame with the accent border will automatically style your image!

## 🎯 Performance

- **Lightweight**: No heavy frameworks or libraries
- **Fast Loading**: Minimal external dependencies
- **Optimized**: Debounced scroll events for better performance
- **Accessible**: Keyboard navigation support

## 📄 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📜 License

This project is open source and available for personal use.

## 👤 Author

**Nurfazlin Binti Mat Tamidi**
- Email: fazlinMat Tamidi@gmail.com
- LinkedIn: [linkedin.com/in/nur-fazlin-156885224](https://www.linkedin.com/in/nur-fazlin-156885224)
- Phone: +6011-61219048

---

**Built with ❤️ and ☕**

*Last Updated: October 2025*
