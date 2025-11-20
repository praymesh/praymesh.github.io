# Instructions for Adding Your Files

## Required Files to Add

### 1. Profile Photo (`profile-photo.jpg`)

**Recommended Specifications:**
- **Format**: JPG or PNG
- **Dimensions**: 800x800 pixels (square format)
- **File Size**: Under 500KB (optimize for web)
- **Style**: Professional headshot with good lighting
- **Background**: Clean, neutral background works best

**Where to Place:**
Place the file in the same directory as `index.html`:
```
site/profile-photo.jpg
```

**How to Take a Great Profile Photo:**
- Use natural lighting or a well-lit space
- Wear professional attire
- Smile naturally and look approachable
- Keep the background simple
- Make eye contact with the camera
- Consider hiring a professional photographer

**If You Don't Have a Photo Yet:**
You can use a temporary placeholder from:
- [This Person Does Not Exist](https://thispersondoesnotexist.com/) (AI-generated faces)
- [UI Faces](https://uifaces.co/) (stock photos)
- Or create a stylized avatar using tools like [Bitmoji](https://www.bitmoji.com/) or [Cartoonify](https://cartoonify.de/)

---

### 2. CV/Resume PDF (`cv.pdf`)

**Recommended Specifications:**
- **Format**: PDF
- **File Size**: Under 2MB
- **Naming**: Keep it as `cv.pdf` or update the link in HTML files
- **Content**: Include education, experience, publications, skills

**Where to Place:**
Place the file in the same directory as `index.html`:
```
site/cv.pdf
```

**CV Tips:**
- Keep it to 2-3 pages for academic CVs
- Include all publications with full citations
- List grants, awards, and honors
- Include teaching experience
- Add relevant skills and certifications
- Proofread carefully

**Creating Your CV:**
- Use LaTeX templates (Overleaf has great academic CV templates)
- Microsoft Word with academic CV template
- Google Docs with professional template
- Online CV builders like [Europass](https://europa.eu/europass)

---

## Updating File References

If you use different filenames, update the references in the HTML files:

### For Profile Photo:
Find this line in `index.html` (around line 49):
```html
<img src="profile-photo.jpg" alt="[Your Name]" class="profile-photo">
```

Change `profile-photo.jpg` to your filename.

### For CV:
Find this line in all HTML files (in the navigation menu):
```html
<li><a href="cv.pdf" class="nav-link" target="_blank">CV</a></li>
```

Change `cv.pdf` to your filename.

---

## Quick Start Checklist

- [ ] Add profile photo as `profile-photo.jpg`
- [ ] Add CV as `cv.pdf`
- [ ] Replace [Your Name] throughout all HTML files
- [ ] Update email address in footer
- [ ] Update social media links in footer
- [ ] Replace placeholder research areas with your actual interests
- [ ] Add your actual publications to `publications.html`
- [ ] Add your actual projects to `projects.html`
- [ ] Customize YouTube section in `beyond-academia.html`
- [ ] Update statistics in the "About Me" section
- [ ] Test the website in a browser
- [ ] Check responsive design on mobile
- [ ] Verify all links work correctly

---

## Need Help?

If you need assistance:
1. Check the README.md file for detailed instructions
2. Ensure all files are in the correct directory
3. Open the browser's developer console (F12) to check for errors
4. Make sure file names match exactly (case-sensitive)

**Happy customizing! 🎓**
