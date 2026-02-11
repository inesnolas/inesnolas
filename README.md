# Academic Personal Webpage

A clean, professional academic personal webpage designed for GitHub Pages.

## Features

- Responsive design that works on all devices
- Smooth navigation and scrolling
- Sections for:
  - About/Bio
  - Research interests
  - Publications
  - Teaching
  - Contact information
- Social media integration
- Modern, accessible design

## Setup for GitHub Pages

### Option 1: User/Organization Site

1. Create a repository named `<username>.github.io`
2. Push these files to the repository
3. Your site will be available at `https://<username>.github.io`

### Option 2: Project Site

1. Create a repository with any name
2. Push these files to the repository
3. Go to Settings > Pages
4. Select the branch (usually `main`) and root folder
5. Your site will be available at `https://<username>.github.io/<repository-name>`

## Customization

Edit [index.html](index.html) to replace placeholders:

- `[Your Name]` - Your full name
- `[Position]` - Your academic position
- `[Institution]` - Your institution name
- Research interests, publications, teaching, and contact information

### Adding Your Profile Photo

1. Add your photo as `profile.jpg` in the root directory
2. Recommended size: 500x500px or larger (square)
3. The image will be automatically cropped to a circle

### Customizing Colors

Edit [styles.css](styles.css) CSS variables in the `:root` section:

```css
:root {
    --primary-color: #2c3e50;    /* Main dark color */
    --secondary-color: #3498db;  /* Accent/link color */
    --accent-color: #e74c3c;     /* Highlight color */
}
```

### Adding a Custom Domain

1. Add a file named `CNAME` with your domain:
   ```
   www.yourdomain.com
   ```
2. Configure DNS settings with your domain provider
3. See [GitHub's custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## Local Development

To preview locally, you can:

1. Open `index.html` directly in a browser, or
2. Use a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## File Structure

```
.
├── index.html       # Main HTML file
├── styles.css       # Stylesheet
├── profile.jpg      # Your profile photo (add this)
├── cv.pdf          # Your CV (add this)
└── README.md       # This file
```

## License

Feel free to use and modify this template for your own academic webpage.
