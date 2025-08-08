# 🚀 APEX Athletic Website - Deployment Guide

This guide will walk you through deploying your APEX Athletic website to the internet using Vercel.

## 📋 Prerequisites

- A computer with internet access
- The website files (this folder)
- An email address for creating accounts

## 🌐 Option 1: Deploy with Vercel (Easiest)

### Step 1: Prepare Your Files
1. Make sure you have the complete `apex-athletic-website` folder
2. Verify it contains:
   - `index.html`
   - `css/` folder
   - `js/` folder
   - `assets/` folder

### Step 2: Create a Vercel Account
1. Go to [https://vercel.com](https://vercel.com)
2. Click "Sign Up"
3. Sign up with your email or GitHub account
4. Verify your email if needed

### Step 3: Deploy Your Website
1. On Vercel dashboard, click "Add New Project"
2. Choose "Continue with CLI/Drag & Drop"
3. Drag the entire `apex-athletic-website` folder into the upload area
4. Wait for upload to complete (usually 10-30 seconds)
5. Click "Deploy"

### Step 4: Get Your Live URL
1. Once deployed, you'll see a success message
2. Your website URL will look like: `https://apex-athletic-xxxxx.vercel.app`
3. Click the URL to view your live website!

## 🔧 Option 2: Deploy with GitHub + Vercel

### Step 1: Create GitHub Account
1. Go to [https://github.com](https://github.com)
2. Click "Sign up"
3. Follow the registration process

### Step 2: Upload to GitHub
1. Click "New repository"
2. Name it `apex-athletic-website`
3. Set to Public
4. Click "Create repository"
5. Click "uploading an existing file"
6. Drag all website files
7. Click "Commit changes"

### Step 3: Connect to Vercel
1. Go to [https://vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Import Project"
4. Select your `apex-athletic-website` repository
5. Click "Deploy"

### Step 4: Automatic Updates
- Any changes you make to GitHub will automatically update your live site!

## 📱 Custom Domain (Optional)

To use your own domain (like `www.apex-athletic.com`):

1. In Vercel dashboard, go to your project
2. Click "Settings" → "Domains"
3. Enter your domain name
4. Follow the DNS configuration instructions
5. Wait 24-48 hours for propagation

## 🛠️ Troubleshooting

### Website not loading?
- Check all files were uploaded
- Ensure `index.html` is in the root folder
- Try refreshing the page

### Images not showing?
- The demo uses colored placeholders
- To add real images:
  1. Replace files in `assets/images/`
  2. Keep the same filenames
  3. Use JPG or PNG format

### Animations not working?
- Ensure JavaScript is enabled in your browser
- Check internet connection (GSAP loads from CDN)

## 📞 Need Help?

### Vercel Support
- Documentation: https://vercel.com/docs
- Support: https://vercel.com/support

### Common Issues
1. **Upload fails**: Try smaller batches of files
2. **Domain issues**: Contact domain registrar
3. **Performance**: Optimize images before upload

## ✅ Post-Deployment Checklist

- [ ] Test on mobile devices
- [ ] Check all links work
- [ ] Verify contact form displays
- [ ] Test page load speed
- [ ] Share with team for feedback

## 🎉 Congratulations!

Your APEX Athletic website is now live on the internet! Share the URL with anyone to show off your premium sports brand.

---

**Remember**: This is a static website demo. To make the contact form functional, you'll need to integrate a form service like Formspree or Netlify Forms.