# Mussawira by Bint-e-Farrukh - Portfolio Website

A beautiful, elegant portfolio website for an artist specializing in custom portraits, original paintings, and handmade crafts. Built with HTML, CSS, and JavaScript with a baby pink theme.

## 🎨 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Baby Pink Theme**: Elegant color scheme with gradient backgrounds
- **Smooth Animations**: Fade-in effects, hover states, and transitions
- **Gallery Section**: Filter artwork by categories (Portraits, Landscapes, Acrylic, Crafts)
- **Contact Form**: Ready-to-use contact form (needs backend integration)
- **Social Media Links**: Instagram and TikTok integration
- **Mobile Menu**: Hamburger menu for mobile devices
- **Bilingual Branding**: Features "Mussawira by Bint-e-Farrukh" in both English and Urdu (مصورہ از بنت فرخ)

## 📋 Sections

1. **Navigation Bar** - Sticky navigation with logo and menu
2. **Hero Section** - Eye-catching landing section with call-to-action
3. **About Section** - Artist introduction and story
4. **Services Section** - Four service cards showcasing offerings
5. **Gallery Section** - Filterable image gallery for artworks
6. **Contact Section** - Contact information and form
7. **Footer** - Copyright and branding

## 🛠️ How to Customize

### 1. Update Contact Information

Find the contact section and replace placeholder information:

```html
<!-- Email -->
<a href="mailto:mussawira@example.com">mussawira@example.com</a>

<!-- Phone (Replace with actual number) -->
<a href="tel:+923001234567">+92 300 1234567</a>

<!-- Instagram -->
<a href="https://instagram.com/mussawira" ...>

<!-- TikTok -->
<a href="https://tiktok.com/@mussawira" ...>
```

### 2. Add Real Images to Gallery

Replace the placeholder emojis with actual images:

**Current placeholder:**
```html
<div class="gallery-placeholder">🎭</div>
```

**Replace with:**
```html
<img src="path/to/your-image.jpg" alt="Artwork description">
```

**Complete example:**
```html
<div class="gallery-item" data-category="portraits">
    <img src="images/portrait1.jpg" alt="Beautiful faceless portrait">
    <div class="gallery-overlay">
        <h3>Faceless Portrait</h3>
        <p>Custom portrait art - $150</p>
    </div>
</div>
```

### 3. Add More Gallery Items

To add new artwork to the gallery, copy this template:

```html
<div class="gallery-item" data-category="portraits">
    <img src="images/your-artwork.jpg" alt="Description">
    <div class="gallery-overlay">
        <h3>Artwork Title</h3>
        <p>Description or price</p>
    </div>
</div>
```

**Categories available:**
- `portraits` - For portrait paintings
- `landscapes` - For landscape paintings
- `acrylic` - For acrylic artwork
- `crafts` - For handmade crafts

### 4. Update About Section

Edit the text in the About section to tell your sister's story:

```html
<p>
    Welcome to Mussawira by Bint-e-Farrukh, where every brushstroke...
    [Replace this with her actual story and background]
</p>
```

### 5. Change Colors (Optional)

If you want to adjust the pink shades, modify the CSS variables at the top:

```css
:root {
    --primary-pink: #FFB6C1;    /* Main pink color */
    --soft-pink: #FFC8D3;       /* Lighter pink */
    --pale-pink: #FFE4E9;       /* Very light pink */
    --light-pink: #FFF0F3;      /* Background pink */
    --deep-pink: #FF9CB5;       /* Darker pink for hover */
}
```

### 6. Make Contact Form Functional

The contact form currently shows an alert. To make it work, you need to:

**Option A: Use a form service (Easiest)**
- Sign up for [Formspree](https://formspree.io/) (Free)
- Get your form endpoint
- Replace the form section:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- Keep all the existing form fields -->
</form>
```

**Option B: Use EmailJS**
- Sign up at [EmailJS](https://www.emailjs.com/)
- Follow their integration guide
- Add their JavaScript library

**Option C: Build your own backend**
- Use PHP, Node.js, or any backend language
- Create an endpoint to handle form submissions
- Send emails using the backend

### 7. Add About Image

Replace the emoji placeholder with a profile picture:

```html
<!-- Current -->
<div class="about-image">🎨</div>

<!-- Replace with -->
<div class="about-image">
    <img src="images/profile.jpg" alt="Bint-e-Farrukh" style="width: 100%; height: 100%; object-fit: cover;">
</div>
```

## 📁 Recommended Folder Structure

```
mussawira-website/
│
├── index.html (the main file)
├── images/
│   ├── portraits/
│   │   ├── portrait1.jpg
│   │   ├── portrait2.jpg
│   │   └── ...
│   ├── landscapes/
│   │   ├── landscape1.jpg
│   │   └── ...
│   ├── acrylic/
│   │   └── ...
│   ├── crafts/
│   │   └── ...
│   └── profile.jpg
└── README.md (this file)
```

## 🚀 How to Launch

1. **Rename the file**: Change `mussawira-portfolio.html` to `index.html`

2. **Add your images**: Create an `images` folder and add artwork photos

3. **Update all placeholder content**: Follow the customization steps above

4. **Test locally**: Open `index.html` in a web browser

5. **Deploy online**: Use one of these free hosting services:
   - **GitHub Pages** (Recommended - Free & Easy)
     - Create a GitHub account
     - Create a new repository
     - Upload your files
     - Enable GitHub Pages in settings
   
   - **Netlify** (Free with drag-and-drop)
     - Sign up at netlify.com
     - Drag your folder to deploy
   
   - **Vercel** (Free for personal projects)
     - Sign up at vercel.com
     - Connect your GitHub repo or upload files

## 📱 Social Media Integration Tips

### Instagram Feed
To show Instagram posts on the website, you can:
1. Use Instagram's embed feature for individual posts
2. Use a service like [SnapWidget](https://snapwidget.com/) for a feed

### TikTok Videos
- Embed TikTok videos using their embed code
- Get embed code from any TikTok video by clicking "Share" → "Embed"

## 💡 Additional Features You Can Add

1. **Image Lightbox**: Add a popup viewer for gallery images
   - Use libraries like [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/) or [GLightbox](https://biati-digital.github.io/glightbox/)

2. **Price List**: Add pricing for each service

3. **Testimonials Section**: Add customer reviews

4. **Blog Section**: Share art process and stories

5. **Online Store**: Integrate with payment systems like:
   - PayPal
   - Stripe
   - Local payment methods

6. **Booking System**: Allow customers to schedule consultations

7. **WhatsApp Button**: Add a floating WhatsApp chat button

## 🎯 SEO Tips

1. Add meta descriptions in the `<head>` section:
```html
<meta name="description" content="Mussawira by Bint-e-Farrukh - Custom portraits, landscape paintings, and handmade crafts. Commission your personalized artwork today.">
<meta name="keywords" content="custom portraits, faceless portraits, landscape paintings, acrylic art, handmade crafts, Pakistan artist">
```

2. Add Open Graph tags for social media sharing:
```html
<meta property="og:title" content="Mussawira by Bint-e-Farrukh">
<meta property="og:description" content="Custom portraits and original artwork">
<meta property="og:image" content="images/hero-image.jpg">
```

3. Use descriptive alt text for all images

4. Create a sitemap.xml file

## 📞 Support

If you need help customizing the website, you can:
- Research specific features on YouTube
- Use ChatGPT or Claude for code help
- Join web development communities on Reddit or Discord
- Hire a freelancer on Fiverr or Upwork for advanced features

## 🎁 Gift Presentation Ideas

When giving this to your sister:
1. Print out a nice card with the website URL
2. Create a short tutorial video showing her how to update content
3. Set up the first few images for her
4. Write a personal note about why you made this for her

## ✨ Credits

Website created with love by [Your Name]
Design: Custom elegant portfolio theme with baby pink aesthetics
Fonts: Playfair Display, Cormorant Garamond, Amiri (Google Fonts)

---

**Note**: This is a single-page HTML file. All CSS and JavaScript are included in the same file for easy deployment. If the website grows, you may want to separate them into different files later.

Enjoy your beautiful new website! 🎨💖
