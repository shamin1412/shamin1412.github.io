# Shamin Shaikh - Portfolio Website

A modern, dark-themed personal portfolio website showcasing my experience in business analytics, data operations, and process automation.

## 🌐 Live Demo
Visit the live site: `https://[your-github-username].github.io`

## ✨ Features

- **Modern Dark Theme**: Professional dark mode with blue accent colors
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle scroll animations and transitions
- **Single Page Application**: Easy navigation with smooth scrolling
- **Interactive Elements**: Hover effects and dynamic highlighting

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles with dark theme
├── script.js           # JavaScript for interactions
├── profile.jpg         # Your profile photo
├── ShaminShaikh_Resume.pdf  # Your resume (add this file)
└── README.md           # This file
```

## 🚀 Deployment Instructions

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub Repository**
   - Go to GitHub and create a new repository
   - Name it: `[your-username].github.io` (e.g., `shamin1412.github.io`)
   - Make it public

2. **Upload Your Files**
   - Clone the repository to your local machine:
     ```bash
     git clone https://github.com/[your-username]/[your-username].github.io.git
     cd [your-username].github.io
     ```
   - Copy all the website files to this directory
   - Add your resume PDF file and rename it to `ShaminShaikh_Resume.pdf`

3. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be live at `https://[your-username].github.io` in a few minutes

### Option 2: Custom Domain (Optional)

If you have a custom domain:
1. Add a `CNAME` file to your repository with your domain name
2. Configure your domain's DNS settings to point to GitHub Pages
3. Enable "Enforce HTTPS" in repository settings

## 🔧 Customization Guide

### Updating Content

1. **Profile Photo**: Replace `profile.jpg` with your photo (recommended: 400x400px)
2. **Resume**: Add your resume PDF as `ShaminShaikh_Resume.pdf`
3. **Contact Info**: Update email, phone, and LinkedIn in `index.html`
4. **Projects**: Edit the projects section in `index.html` to add GitHub links
5. **Experience**: Modify the experience timeline as needed

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --accent-primary: #3b82f6;  /* Primary blue */
    --accent-secondary: #60a5fa; /* Lighter blue */
    /* Change these to your preferred colors */
}
```

### Adding New Sections

1. Add the HTML section in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu with new link

## 📝 Adding More Projects

To add more projects to the Projects section:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Your Project Name</h3>
        <span class="project-tag">Category</span>
    </div>
    <p class="project-description">Project description here...</p>
    <div class="project-tech">
        <span class="tech-tag">Python</span>
        <span class="tech-tag">SQL</span>
    </div>
    <a href="https://github.com/yourusername/project" class="project-link" target="_blank">View Project →</a>
</div>
```

## 🎨 Design Features

- **Color Scheme**: Dark background with blue gradient accents
- **Typography**: Inter font family for modern, clean look
- **Animations**: Fade-in effects on scroll
- **Responsive**: Mobile-first approach with breakpoints at 768px and 480px

## 📱 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)

## 📧 Contact

- Email: shaikh8@illinois.edu
- LinkedIn: [linkedin.com/in/shamin-shaikh](http://linkedin.com/in/shamin-shaikh)
- Phone: +1 (447) 902-7000

## 📄 License

This project is open source and available for personal use.

---

**Note**: Remember to add your actual resume PDF file before deploying. The download button links to `ShaminShaikh_Resume.pdf`.

## 🎯 Next Steps

1. Review all content in `index.html` for accuracy
2. Add your resume PDF file
3. Test locally by opening `index.html` in a browser
4. Deploy to GitHub Pages
5. Share your new portfolio website!

## 💡 Tips

- Keep your GitHub projects updated and public
- Regularly update your experience and projects
- Add Google Analytics to track visitors (optional)
- Consider adding a blog section for thought leadership

Good luck with your portfolio! 🚀
