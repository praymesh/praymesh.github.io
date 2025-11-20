# Academic Portfolio Website

A modern, clean, and responsive academic portfolio/CV website with dark/light mode toggle.

## 🎨 Features

- **Clean & Modern Design**: Professional academic portfolio with a focus on typography and readability
- **Dark/Light Mode**: Toggle between themes with preferences saved in local storage
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Multiple Pages**:
  - **Home**: Hero section with profile photo, about section, research interests
  - **Publications**: Organized by year with filters and download links
  - **Projects**: Interactive project cards with status badges and categorization
  - **Beyond Academia**: Showcase your creative pursuits (YouTube, video editing, hobbies)
  - **CV**: Link to download your CV (PDF)
- **Social Media Integration**: Links to all your professional and social profiles
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **SEO Friendly**: Semantic HTML structure

## 📁 File Structure

```
site/
├── index.html              # Homepage
├── publications.html       # Publications page
├── projects.html          # Projects page
├── beyond-academia.html   # Personal interests page
├── styles.css             # Global styles with CSS variables
├── script.js              # Interactive functionality
├── profile-photo.jpg      # Your profile photo (add this)
└── cv.pdf                 # Your CV PDF (add this)
```

## 🚀 Getting Started

### 1. Add Your Content

Replace all placeholder text with your actual information:

- **[Your Name]** - Your full name
- **[Your Field]** - Your research field/specialization
- **[Your Institution]** - Your university/organization
- **[Your Title/Position]** - Your academic position
- **your.email@institution.edu** - Your email address
- Update research areas, publications, projects, etc.

### 2. Add Your Photo

Add your profile photo as `profile-photo.jpg` in the same directory. Recommended:
- Format: JPG or PNG
- Size: 800x800px (square)
- Professional headshot

### 3. Add Your CV

Add your CV as `cv.pdf` in the same directory.

### 4. Update Social Media Links

In all HTML files, update the footer links:
- Twitter: `https://twitter.com/yourhandle`
- LinkedIn: `https://linkedin.com/in/yourprofile`
- GitHub: `https://github.com/yourusername`
- Google Scholar: `https://scholar.google.com/citations?user=yourid`
- ORCID: `https://orcid.org/your-orcid`
- YouTube: `https://youtube.com/@yourchannel`

### 5. Open in Browser

Simply open `index.html` in your web browser to view the site locally.

## 🎨 Customization

### Colors

Edit CSS variables in `styles.css` (lines 6-18) to change the color scheme:

```css
:root {
    --accent-color: #2563eb;  /* Primary accent color */
    --accent-hover: #1d4ed8;  /* Hover state */
    /* ... other variables ... */
}
```

### Fonts

The site uses system fonts by default. To use custom fonts:

1. Add Google Fonts link to `<head>` in HTML files:
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```

2. Update font-family in `styles.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Sections

You can easily add, remove, or modify sections by editing the HTML files. Each section follows a consistent structure with semantic HTML.

## 📱 Responsive Design

The site is fully responsive with breakpoints at:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## 🌙 Dark Mode

The theme toggle is located in the top-right of the navigation bar. User preference is saved in localStorage and persists across sessions.

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript**: No frameworks needed
- **Font Awesome**: Icons (loaded via CDN)

## 📝 Content Guidelines

### Publications
- Organize by year (newest first)
- Include full citation details
- Add links to PDF, DOI, code, slides
- Highlight your name in author lists

### Projects
- Categorize by status (Ongoing, Completed, Upcoming)
- Include clear descriptions
- Add relevant tags/keywords
- Link to GitHub repos, demos, papers

### Beyond Academia
- Showcase your personality and interests
- Include your YouTube channel if applicable
- Mention hobbies and creative pursuits
- Make it personal and authentic

## 🚀 Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Upload all files
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Other Hosting Options

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your Git repository
- **Traditional Hosting**: Upload via FTP to your web host

## ✨ Tips for Best Results

1. **High-Quality Images**: Use professional photos
2. **Concise Writing**: Keep descriptions clear and focused
3. **Regular Updates**: Keep publications and projects current
4. **Proofread**: Check for typos and grammar
5. **Test Responsive**: View on different devices
6. **Optimize Images**: Compress photos for faster loading
7. **SEO**: Update page titles and meta descriptions

## 📄 License

Feel free to use this template for your academic portfolio. Attribution appreciated but not required.

## 🤝 Support

If you encounter any issues or have questions, feel free to reach out!

---

**Happy building! 🎓✨**
