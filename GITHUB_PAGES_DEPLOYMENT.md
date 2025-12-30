# 🚀 Deploy Your Portfolio to GitHub Pages

Your website is ready to go live! Follow these simple steps to deploy it.

## ✅ Step 1: Repository Prepared (DONE)

I've already set up Git for you:
- ✅ Git initialized
- ✅ All files committed
- ✅ Branch named 'main' (GitHub standard)

---

## 📝 Step 2: Create GitHub Repository

### Option A: Using GitHub Website (Recommended for Beginners)

1. **Go to GitHub:**
   - Open https://github.com in your browser
   - Sign in (or create a free account if you don't have one)

2. **Create New Repository:**
   - Click the **"+"** icon in the top right
   - Select **"New repository"**

3. **Repository Settings:**
   - **Repository name:** `benedictmusila.github.io` 
     (This special name gives you: https://benedictmusila.github.io as your URL!)
   - **Description:** "Professional portfolio website for Benedict Musila - Senior Software Engineer"
   - **Public** (select this - required for free GitHub Pages)
   - **DO NOT** check "Add a README file" (we already have one)
   - **DO NOT** add .gitignore (we already have one)
   - Click **"Create repository"**

4. **Copy the Repository URL:**
   - You'll see a page with setup instructions
   - Look for the URL like: `https://github.com/YOUR_USERNAME/benedictmusila.github.io.git`
   - Keep this page open - you'll need it for Step 3

---

## 🔗 Step 3: Connect & Push Your Code

### Open your terminal and run these commands:

**Note:** Replace `YOUR_USERNAME` with your actual GitHub username!

```bash
cd /Users/benedictmusila/Documents/Personalised/MyPortfolio

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/benedictmusila.github.io.git

# Push your code to GitHub
git push -u origin main
```

**Example:** If your GitHub username is "bmusila", the command would be:
```bash
git remote add origin https://github.com/bmusila/benedictmusila.github.io.git
```

**If prompted for credentials:**
- You may need to use a Personal Access Token instead of password
- See "GitHub Authentication" section below if needed

---

## ⚙️ Step 4: Enable GitHub Pages

1. **Go to your repository on GitHub**
   - https://github.com/YOUR_USERNAME/benedictmusila.github.io

2. **Click "Settings"** (top menu)

3. **Click "Pages"** (left sidebar)

4. **Configure GitHub Pages:**
   - **Source:** Deploy from a branch
   - **Branch:** Select `main`
   - **Folder:** Select `/ (root)`
   - Click **"Save"**

5. **Wait 1-2 minutes** for deployment

6. **Get Your Live URL:**
   - Refresh the page
   - You'll see: "Your site is live at https://benedictmusila.github.io"
   - Click the link to visit your live website! 🎉

---

## 🌟 Your Website Will Be Live At:

```
https://benedictmusila.github.io
```

(Replace with your actual GitHub username if different)

---

## 🔐 GitHub Authentication (If Needed)

GitHub no longer accepts passwords for git operations. You need a Personal Access Token:

### Create a Personal Access Token:

1. Go to https://github.com/settings/tokens
2. Click **"Generate new token"** → **"Generate new token (classic)"**
3. Give it a name: "Portfolio Deployment"
4. Select expiration: 90 days (or "No expiration" if you prefer)
5. Check the box for: **repo** (Full control of private repositories)
6. Click **"Generate token"**
7. **Copy the token** (you won't see it again!)

### Use the token when pushing:

When asked for password, paste your Personal Access Token instead.

---

## 🔄 Updating Your Website Later

Whenever you make changes to your website:

```bash
cd /Users/benedictmusila/Documents/Personalised/MyPortfolio

# Stage your changes
git add .

# Commit with a message
git commit -m "Update portfolio content"

# Push to GitHub
git push

# Wait 1-2 minutes for GitHub Pages to rebuild
```

Your live site will automatically update!

---

## ✅ Post-Deployment Checklist

After your site is live:

- [ ] Visit your live URL to verify everything works
- [ ] Test on mobile device
- [ ] Check that profile photo displays correctly
- [ ] Test the contact form
- [ ] Test all navigation links
- [ ] Share with a friend for feedback

---

## 📱 Share Your Portfolio

Once live, add your portfolio URL to:

1. **LinkedIn:**
   - Edit your profile
   - Add to "Featured" section
   - Add to "Contact Info" → Website

2. **Email Signature:**
   ```
   Benedict Musila
   Senior Software Engineer
   Portfolio: https://benedictmusila.github.io
   LinkedIn: linkedin.com/in/benedict-musila-8ab1b2157
   Email: musilabeny@gmail.com
   ```

3. **Resume/CV:**
   - Add your website URL at the top
   - Include it in your contact information

4. **Job Applications:**
   - Include the link in cover letters
   - Add to application forms

---

## 🎯 Custom Domain (Optional)

Want to use a custom domain like `www.benedictmusila.com`?

1. **Buy a domain** (from Namecheap, GoDaddy, Google Domains, etc.)

2. **Configure DNS** in your domain provider:
   - Add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Add CNAME record: `www` → `YOUR_USERNAME.github.io`

3. **Configure in GitHub:**
   - Go to Settings → Pages
   - Enter your custom domain
   - Enable "Enforce HTTPS"

4. **Wait for DNS propagation** (can take up to 48 hours)

---

## 🆘 Troubleshooting

### Site not showing up?
- Wait 2-3 minutes after enabling GitHub Pages
- Check repository name is `benedictmusila.github.io` (or similar)
- Verify repository is Public (not Private)
- Check GitHub Pages is enabled in Settings → Pages

### 404 Error?
- Make sure `index.html` is in the root directory (not in a subfolder)
- Check that branch is set to `main` in Pages settings

### Profile photo not showing?
- Ensure `assets/profile.png` is committed to GitHub
- Check the image path in index.html is correct

### Authentication failed?
- Use Personal Access Token instead of password
- See "GitHub Authentication" section above

### Changes not appearing?
- Wait 1-2 minutes after pushing
- Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)
- Check GitHub Actions tab to see if build completed

---

## 📊 Monitor Your Site

GitHub provides free analytics:
- Go to repository → Insights → Traffic
- See visitor counts and popular pages

For more detailed analytics, add:
- Google Analytics
- Cloudflare Analytics (free)

---

## 🎉 Success!

Once deployed, your professional portfolio will be:
- ✅ Live on the internet 24/7
- ✅ Fast and reliable (GitHub's infrastructure)
- ✅ Free forever
- ✅ Easy to update anytime
- ✅ Secure with HTTPS
- ✅ Accessible worldwide

**Congratulations on launching your professional portfolio! 🚀**

---

*Need help? Check the README.md or SETUP_GUIDE.md files for additional documentation.*

