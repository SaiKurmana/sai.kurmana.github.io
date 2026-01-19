# Sai Kurmana - Personal Website

Professional portfolio website showcasing expertise in healthcare data analytics, AI/ML, and health informatics.

## 🚀 Quick Start - Deploying to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: If your username is `saikurmana`, name it `saikurmana.github.io`
4. Make it **Public**
5. **Do NOT** initialize with README (we'll upload our own files)
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. On your new repository page, click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Navigate to the folder containing index.html
cd /path/to/your/website/folder

# Initialize git repository
git init

# Add your files
git add index.html

# Commit your changes
git commit -m "Initial commit: Personal website"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select `main` and `/ (root)`
6. Click "Save"

### Step 4: View Your Website

Your website will be live at: `https://yourusername.github.io`

⏱️ **Note:** It may take 1-5 minutes for your site to be published the first time.

---

## 📝 Customization Guide

### Update Contact Information

Open `index.html` and search for these sections to update:

**Email:**
```html
<a href="mailto:Sai.Kurmana@gmail.com" class="contact-link">
```

**Phone:**
```html
<a href="tel:913-207-9628" class="contact-link">
```

**LinkedIn:**
```html
<a href="https://linkedin.com/in/SaiKurmana" target="_blank" class="contact-link">
```

### Add GitHub Link

Add this to the contact links section:
```html
<a href="https://github.com/yourusername" target="_blank" class="contact-link">
    <span>💻</span> GitHub
</a>
```

### Customize Colors

Find the `:root` section at the top of the `<style>` tag and modify these CSS variables:

```css
:root {
    --primary: #0A4D68;      /* Main brand color */
    --primary-light: #088395; /* Lighter brand color */
    --accent: #05BFDB;        /* Accent color */
    --accent-warm: #E67E22;   /* Warm accent */
}
```

### Update Content

All content is in the HTML. Search for these sections:

- **Hero Section:** Update your name, title, description
- **Stats:** Modify the numbers and labels
- **Expertise Cards:** Add/remove/edit your skills
- **Timeline:** Update your work experience
- **Achievements:** Showcase your projects
- **Contact:** Update your information

---

## 🎨 Design Features

This website includes:

- **Animated Background Grid** - Subtle moving grid pattern
- **Smooth Scroll Animations** - Elements fade in as you scroll
- **Responsive Design** - Works on desktop, tablet, and mobile
- **Professional Typography** - Using Playfair Display, DM Sans, and Fira Code
- **Interactive Cards** - Hover effects on expertise and achievement cards
- **Timeline Visualization** - Clean experience timeline
- **Modern Color Scheme** - Professional healthcare + tech aesthetic

---

## 📱 Mobile Responsive

The website automatically adapts to different screen sizes:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

---

## 🔧 Advanced Customization

### Adding a Blog Section

1. Create a new `blog` folder in your repository
2. Add individual blog post HTML files
3. Create a blog index page listing all posts
4. Add a "Blog" link to navigation

### Adding Google Analytics

Add this before the closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

### Adding a Resume Download Button

Add this to your CTA buttons section:

```html
<a href="./resume.pdf" download class="btn btn-secondary">
    Download Resume
</a>
```

Then upload your resume PDF to the repository.

---

## 🐛 Troubleshooting

**Site not showing up?**
- Wait 5-10 minutes after first deployment
- Check Settings → Pages to ensure it's enabled
- Verify your repository is named correctly: `username.github.io`
- Make sure the file is named exactly `index.html` (lowercase)

**Images not loading?**
- Use relative paths: `./images/photo.jpg`
- Or use absolute URLs from image hosting services

**Fonts not displaying?**
- The fonts load from Google Fonts - ensure you have internet connection
- Fonts are cached after first load

---

## 📚 Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML/CSS Tutorial](https://www.w3schools.com/)
- [Markdown Guide](https://www.markdownguide.org/)
- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

---

## 📄 License

This website template is free to use and modify for personal use.

---

## 🎯 Next Steps

1. ✅ Deploy to GitHub Pages
2. 📝 Customize content with your information
3. 🎨 Adjust colors to match your personal brand
4. 📸 Add professional headshot (optional)
5. 📊 Add Google Analytics to track visitors
6. 🔗 Share your website URL on LinkedIn, resume, email signature
7. 📱 Test on multiple devices
8. 🚀 Keep content updated as you achieve new milestones

---

**Built with:** HTML5, CSS3, Vanilla JavaScript
**Fonts:** Playfair Display, DM Sans, Fira Code (Google Fonts)
**Deployment:** GitHub Pages

---

For questions or issues, feel free to reach out!
