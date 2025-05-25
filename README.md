
# HVAC Pro Website – Client Guide

Welcome to your new HVAC Pro website! This guide will help you understand the structure, usage, and maintenance of your website.

---

## ✅ What's Included

- **Responsive Website** (Mobile & Desktop Ready)
- **Live Booking Form** – Sends submissions to your email
- **Contact Page** – For inquiries
- **SEO Optimized Pages** – Metadata + social previews
- **404 Error Page** – Friendly fallback if a page isn’t found
- **Performance Optimized** – Preloaded assets + lazy image loading

---

## 📁 Folder Structure

```
.
├── index.html           → Homepage
├── services.html        → Services you offer
├── about.html           → About your business
├── contact.html         → Contact form
├── booking.html         → Service booking form
├── faq.html             → Frequently asked questions
├── blog.html            → Placeholder for articles
├── 404.html             → Fallback error page
└── /images
    └── hero-background.jpg
```

---

## ✉️ Form Setup

Your contact and booking forms use **[Formspree](https://formspree.io/)** to collect submissions.

To enable:
1. Go to [https://formspree.io](https://formspree.io)
2. Sign up and create a new form
3. Replace the placeholder URL in `contact.html` and `booking.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_ID_HERE" method="POST">
   ```

---

## 🚀 How to Launch

### Option A: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files (preserve structure)
3. Go to **Settings > Pages** and choose root `/ (index.html)`

### Option B: Netlify (One-click)
1. Go to [https://netlify.com](https://netlify.com)
2. Drag & drop your folder or connect a GitHub repo

---

## 🛠️ Editing Content

You can open any `.html` file with:
- **VS Code**
- **Notepad++**
- **Brackets**

Update the text directly in the `<section>` elements. No coding required!

---

## 📞 Need Help?

This site was developed by **Chyke Web Craft Agency**.  
For updates or support, email: `chykewebcraft@example.com`

---

Thank you for choosing us to build your HVAC web presence!
