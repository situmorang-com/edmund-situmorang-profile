# Edmund Situmorang - Resume Website

A beautiful, responsive single-page resume website showcasing the professional profile of Edmund Situmorang, Chief Technology Officer and AI Expert.

## 📋 About This Project

This is a static HTML resume website built with modern CSS gradients and animations. The information has been extracted from the LinkedIn profile at [linkedin.com/in/situmorang](https://www.linkedin.com/in/situmorang).

## 🎨 Features

- **Single-page design** with smooth scrolling navigation
- **Modern gradient backgrounds** (blue/purple theme)
- **Responsive layout** that works on all devices
- **Card-based sections** for clean presentation
- **Fade-in animations** on scroll
- **Professional typography** using system fonts
- **Clean, modern aesthetics**

## 📁 File Structure

```
resume-cv-edmund/
├── index.html       # Main HTML file
├── styles.css       # All styling and animations
└── README.md        # This file
```

## 🚀 Getting Started

1. **Open the website:**
   - Simply open `index.html` in any modern web browser
   - No server or build process required

2. **View locally:**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Or using Node.js
   npx serve
   ```

3. **Open in browser:**
   - Navigate to `http://localhost:8000`

## ✏️ Manual Editing Instructions

### Personal Information

Look for these comments in `index.html` and replace with your information:

```html
<!-- CURRENT POSITION -->
<div class="experience-period">Apr 2025 - Present (7 mos)</div>
```

### Experience Details

Many experience entries contain placeholder comments:

```html
<!-- ADD DETAILS HERE -->
```

Fill these in with your complete work history from LinkedIn.

### Adding Missing Experience

To add additional work experience, copy this template:

```html
<div class="experience-item">
    <div class="experience-period">START - END (DURATION)</div>
    <div class="experience-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <p class="location">📍 Location</p>
        <ul>
            <li>Your first responsibility</li>
            <li>Your second responsibility</li>
            <li>Your achievements</li>
        </ul>
    </div>
</div>
```

### Skills

Edit the skills section by modifying the skill badges:

```html
<span class="skill-badge">Your Skill</span>
```

### Certifications

Add more certifications using this format:

```html
<div class="cert-item">
    <h3>Certification Name</h3>
    <p class="cert-org">Organization</p>
    <p class="cert-date">Issued MONTH YEAR</p>
    <p class="cert-id">Credential ID XXXXX</p>
</div>
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}
```

### Adding Your Photo

To add a profile photo, insert in the hero section:

```html
<img src="your-photo.jpg" alt="Edmund Situmorang" class="profile-photo">
```

And add CSS:

```css
.profile-photo {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 5px solid white;
    margin: 0 auto 2rem;
}
```

## 📝 Extracted Information

From your LinkedIn profile, the following information was included:

- **Current Positions:** Director at MD Now, Group CTO at MD CORP
- **Recent Roles:** Various leadership positions at BUMI Resources, Sinarmas Mining
- **Education:** BS Computer Science, MBA
- **Skills:** AI, Machine Learning, Digital Transformation, and more
- **Projects:** NLP system, Credit Scoring, and other notable projects
- **Certifications:** Multiple professional certifications
- **Awards:** Digital Leader of the Year, CIO 100, and others
- **Languages:** English (Native), Indonesian (Native), and more

## 🔗 Links Included

- **Website:** [situmorang.com](https://www.situmorang.com)
- **LinkedIn:** [linkedin.com/in/situmorang](https://www.linkedin.com/in/situmorang)
- All links open in new tabs for easy reference

## 📱 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📧 Contact

For updates or corrections:
- Visit the LinkedIn profile: https://www.linkedin.com/in/situmorang
- Check the website: https://www.situmorang.com

## 📄 License

This is a personal resume website. Feel free to use this template for your own resume, but remember to update all content with your own information.

## 🤝 Credits

Information extracted from publicly available LinkedIn profile data. All content should be verified and updated as needed.

