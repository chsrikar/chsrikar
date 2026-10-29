# 🎨 GitHub Profile Setup Guide

## Welcome, Sri Sushmita Dasari!

This guide will help you customize and publish your premium burgundy-themed GitHub profile.

---

## ✅ Pre-Publication Checklist

### 1. **Replace All Placeholders**

Search for and replace the following throughout `README.md`:

- `[username]` → Your actual GitHub username
- `[email]` → Your email address
- `[portfolio-url]` → Your portfolio website URL

### 2. **Update Project Information**

In the **Featured Projects** section:
- Replace placeholder project names with your actual projects
- Add real repository links (e.g., `https://github.com/yourusername/project-name`)
- Add live demo links if available
- Write brief, compelling descriptions (1-2 sentences)
- Verify technology stacks are accurate

### 3. **Add Coding Profile Links**

In the **Let's Connect** section, update:
- LeetCode: `https://leetcode.com/yourusername`
- CodeChef: `https://codechef.com/users/yourusername`
- HackerRank: `https://hackerrank.com/yourusername`
- Kaggle: `https://kaggle.com/yourusername`

Remove any platform you don't use.

### 4. **Verify Education & Achievements**

✅ Current information (as verified):
- B.Tech in AI & ML from Aditya Engineering College
- CGPA: 9.10
- Flipkart GRiD 7.0 — National Semi-Finalist
- Myntra WeForShe HackerRamp 2026 — Top 100 Teams

If any details need correction, edit the corresponding sections.

### 5. **Add Certifications** (Optional)

In the **Certifications** section, add your verified certifications:
```markdown
| Certification | Issuer | Year |
|--------------|--------|------|
| AWS Certified Developer | Amazon Web Services | 2024 |
```

### 6. **Privacy Check** ✨

**CRITICAL**: Verify that your phone number does NOT appear anywhere in:
- README.md
- Any SVG files
- Any other files in the repository

---

## 🎨 Assets Created

### Animated SVG Files

1. **`assets/sushmita-hero.svg`** (1200×400)
   - Main hero banner with animated gradients
   - Burgundy color scheme with moving elements
   - Technical grid pattern and orbital geometry

2. **`assets/footer-burgundy.svg`** (1200×120)
   - Animated footer decoration
   - Glowing accent elements

3. **`assets/divider-burgundy.svg`** (1200×40)
   - Section divider with animated center dot

### Color Palette

- Midnight: `#10070C`
- Dark Wine: `#190B12`
- Burgundy: `#451126`
- Wine Accent: `#701A3D`
- Rose: `#C77B9B`
- Pale Rose: `#E5B5C7`
- Ivory: `#F8F0F3`

---

## 📱 Preview Your Profile

### Local Preview

1. Open `README.md` in a Markdown preview tool
2. Use VS Code's built-in preview (Ctrl+Shift+V or Cmd+Shift+V)
3. Or use an online Markdown editor

### GitHub Preview

GitHub's README sanitization means:
- SVG animations will work ✅
- SMIL animations are supported ✅
- No JavaScript execution (by design) ✅
- Light/Dark mode supported ✅

---

## 🚀 Publishing Your Profile

### Step 1: Create the Repository

Your GitHub profile README must be in a repository named exactly as your username.

1. Go to https://github.com/new
2. Repository name: `[your-username]` (must match exactly)
3. Make it **Public**
4. Do NOT initialize with README (you already have one)
5. Click "Create repository"

### Step 2: Push Your Changes

Using **GitHub Desktop**:

1. Open GitHub Desktop
2. File → Add Local Repository
3. Select this folder: `c:\Users\srika\OneDrive\Documents\chsrikar`
4. If not already initialized, GitHub Desktop will offer to create a repo
5. **Commit changes:**
   - Summary: "Initial commit: Premium burgundy profile"
   - Description: "Animated SVG hero, project showcase, burgundy theme"
6. **Publish repository:**
   - Click "Publish repository"
   - Uncheck "Keep this code private"
   - Repository name MUST be your GitHub username
   - Click "Publish Repository"

Using **Command Line**:

```bash
# Navigate to repository
cd "c:\Users\srika\OneDrive\Documents\chsrikar"

# Initialize git (if not already done)
git init

# Add files
git add README.md assets/sushmita-hero.svg assets/footer-burgundy.svg assets/divider-burgundy.svg

# Commit
git commit -m "Initial commit: Premium burgundy GitHub profile"

# Add remote (replace [username] with your actual GitHub username)
git remote add origin https://github.com/[username]/[username].git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Verify

1. Visit `https://github.com/[yourusername]`
2. Your profile README should appear automatically
3. Check that:
   - SVG animations are working
   - All images load correctly
   - Links work as expected
   - Both light and dark modes look good

---

## 🔧 Troubleshooting

### SVG Not Displaying

- Ensure file paths are relative: `assets/hero.svg` not `/assets/hero.svg`
- Check that SVG files are committed and pushed
- Verify SVG syntax is valid

### GitHub Stats Not Showing

- Replace `[username]` in the stats URLs with your actual username
- Note: Stats may take a few hours to generate for new accounts
- Ensure your repository is public

### Animations Not Working

- GitHub supports SMIL animations in SVG
- Animations work in most modern browsers
- Some email clients may show static fallback (this is expected)

### Links Broken

- Double-check all URLs are complete and correct
- Test each link after publishing
- Update any that are incorrect

---

## 🎯 Next Steps

### Enhance Your Profile

1. **Add More Projects**: As you build more, update the Featured Projects section
2. **Write Blog Posts**: Link to your technical writing
3. **Showcase Work**: Add screenshots or GIFs of your projects
4. **Keep Stats Updated**: GitHub stats update automatically
5. **Regular Updates**: Keep your achievements and skills current

### Content Ideas

- **Pinned Repositories**: Pin your 6 best projects on your GitHub profile
- **Project READMEs**: Write detailed READMEs for each project
- **Contribution Graph**: Maintain consistent contributions
- **Open Source**: Contribute to projects you use

---

## 📞 Support

If you need to make changes:

1. Edit the files locally
2. Commit changes with a meaningful message
3. Push to GitHub
4. Changes appear immediately on your profile

---

## ✨ Design Notes

This profile was designed with:
- **Premium burgundy aesthetic** — cinematic and editorial
- **Animated SVG elements** — subtle motion for sophistication
- **GitHub-compatible** — no JavaScript, respects sanitization
- **Light/Dark mode aware** — adapts to user preference
- **Mobile-responsive** — readable on all devices
- **Accessibility** — proper ARIA labels and semantic markup

**Remember**: Your GitHub profile is often the first impression recruiters and collaborators have of you. Keep it updated, authentic, and professional.

---

**Good luck, and happy coding! 🚀**
