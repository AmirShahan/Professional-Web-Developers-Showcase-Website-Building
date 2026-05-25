# Website Deployment Guide

This guide will help you deploy your portfolio website to the internet for FREE using multiple methods.

## 🚀 Method 1: GitHub Pages (Recommended - FREE)

### Prerequisites
- GitHub account (create one at https://github.com)
- Git installed on your computer

### Steps:

1. **Initialize Git Repository** (if not already done)
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Portfolio website"
   ```

2. **Create a New Repository on GitHub**
   - Go to https://github.com/new
   - Repository name: `amirshahan-portfolio` (or any name you prefer)
   - Make it Public
   - Don't initialize with README (we already have files)
   - Click "Create repository"

3. **Push Your Code to GitHub**
   ```bash
   git remote add origin https://github.com/AmirShahan/amirshahan-portfolio.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait 2-3 minutes

5. **Your Website is Live!**
   - URL: `https://amirshahan.github.io/amirshahan-portfolio/`
   - GitHub will show you the URL in the Pages settings

---

## 🌐 Method 2: Netlify (Easiest - FREE)

### Option A: Drag & Drop (No Git Required)

1. **Go to Netlify**
   - Visit https://app.netlify.com/drop
   - No account needed for first deployment!

2. **Drag Your Folder**
   - Drag the entire project folder to the Netlify drop zone
   - Wait for upload to complete

3. **Your Website is Live!**
   - Netlify will give you a URL like: `https://random-name-123.netlify.app`
   - You can change the name in site settings

### Option B: Connect to GitHub (Recommended)

1. **Sign up on Netlify**
   - Go to https://netlify.com
   - Sign up with your GitHub account

2. **New Site from Git**
   - Click "Add new site" → "Import an existing project"
   - Choose "GitHub"
   - Select your repository
   - Click "Deploy site"

3. **Automatic Deployments**
   - Every time you push to GitHub, Netlify auto-updates your site!

---

## 🔥 Method 3: Vercel (FREE)

1. **Sign up on Vercel**
   - Go to https://vercel.com
   - Sign up with GitHub

2. **Import Project**
   - Click "Add New" → "Project"
   - Select your GitHub repository
   - Click "Deploy"

3. **Your Website is Live!**
   - URL: `https://your-project.vercel.app`

---

## 🎯 Method 4: Render (FREE)

1. **Sign up on Render**
   - Go to https://render.com
   - Sign up with GitHub

2. **New Static Site**
   - Click "New" → "Static Site"
   - Connect your GitHub repository
   - Build command: (leave empty)
   - Publish directory: `.` (current directory)
   - Click "Create Static Site"

3. **Your Website is Live!**
   - URL: `https://your-site.onrender.com`

---

## 🌟 Method 5: Cloudflare Pages (FREE)

1. **Sign up on Cloudflare**
   - Go to https://pages.cloudflare.com
   - Create account

2. **Create a Project**
   - Click "Create a project"
   - Connect to GitHub
   - Select your repository
   - Click "Begin setup" → "Save and Deploy"

3. **Your Website is Live!**
   - URL: `https://your-project.pages.dev`

---

## 📱 Custom Domain (Optional)

After deploying, you can add a custom domain like `amirshahan.com`:

### For GitHub Pages:
1. Buy a domain from Namecheap, GoDaddy, or Google Domains
2. In your repository, create a file named `CNAME` with your domain
3. In your domain registrar, add these DNS records:
   - Type: A, Host: @, Value: 185.199.108.153
   - Type: A, Host: @, Value: 185.199.109.153
   - Type: A, Host: @, Value: 185.199.110.153
   - Type: A, Host: @, Value: 185.199.111.153

### For Netlify/Vercel/Render:
1. Go to site settings
2. Click "Add custom domain"
3. Follow the DNS configuration instructions

---

## ✅ Recommended Deployment Method

**For Beginners:** Netlify Drag & Drop (Method 2A)
- Fastest and easiest
- No Git knowledge required
- Free SSL certificate included

**For Developers:** GitHub Pages + Netlify (Methods 1 + 2B)
- Version control with Git
- Automatic deployments
- Professional workflow

---

## 🔧 Troubleshooting

### Website not loading?
- Wait 5-10 minutes after deployment
- Clear browser cache (Ctrl + F5)
- Check if files are uploaded correctly

### Images not showing?
- Make sure image paths are relative (e.g., `./images/photo.jpg`)
- Check file names match exactly (case-sensitive)

### Form not working?
- The contact form needs a backend service
- Use Netlify Forms (free) or Formspree
- See FORM_SETUP.md for instructions

---

## 📞 Need Help?

If you encounter any issues:
1. Check the deployment platform's documentation
2. Verify all files are uploaded
3. Check browser console for errors (F12)

---

## 🎉 Your Website is Live!

Congratulations! Your portfolio is now accessible worldwide. Share your URL with:
- Potential clients
- Employers
- Social media
- Your resume

Don't forget to update your website regularly with new projects and skills!