# Assets Folder

This folder contains all the assets for your portfolio website.

## 📁 Structure

```
assets/
├── images/          # Project screenshots, profile photo, etc.
├── resume.pdf       # Your resume (optional)
└── favicon.ico      # Website favicon (optional)
```

## 🖼️ Images

Add your project screenshots and personal photos here. 

### Recommended Image Sizes:
- **Project Screenshots**: 800x600px or 1200x900px
- **Profile Photo**: 300x300px (square)
- **Favicon**: 32x32px or 64x64px

### Image Optimization Tips:
1. Use JPG for photos and screenshots
2. Use PNG for logos and graphics with transparency
3. Compress images using tools like:
   - [TinyPNG](https://tinypng.com/)
   - [Squoosh](https://squoosh.app/)
   - [ImageOptim](https://imageoptim.com/)

## 📄 Resume

Add your resume as a PDF file here and link it in your portfolio:

```html
<a href="assets/resume.pdf" download class="btn btn-primary">Download Resume</a>
```

## 🎯 Favicon

To add a favicon to your site:

1. Create or generate a favicon (32x32px or 64x64px)
2. Save it as `favicon.ico` in this folder
3. Add this line to the `<head>` section of `index.html`:
   ```html
   <link rel="icon" type="image/x-icon" href="assets/favicon.ico">
   ```

## 🎨 Free Image Resources

If you need placeholder images or stock photos:

- [Unsplash](https://unsplash.com/) - Free high-quality photos
- [Pexels](https://www.pexels.com/) - Free stock photos
- [Undraw](https://undraw.co/) - Free illustrations
- [Hero Icons](https://heroicons.com/) - Free SVG icons
