# 🚀 GitHub Profile Portfolio — Setup & Deployment Guide

This guide explains how to activate your new GitHub Profile Portfolio README on your personal GitHub profile (`https://github.com/kiran-atcore`).

---

## 🌟 How the GitHub Profile README Works

GitHub provides a special feature:
When you create a **public** repository whose name matches your GitHub username **character-for-character** (e.g., `kiran-atcore/kiran-atcore`), GitHub automatically displays that repository's `README.md` at the very top of your personal profile page.

---

## 🛠️ Step 1: Create the Special Repository on GitHub

1. Open your browser and navigate to [github.com/new](https://github.com/new).
2. Set **Repository name** to:
   ```text
   kiran-atcore
   ```
   *(GitHub will show a green banner: "✨ You found a secret! kiran-atcore/kiran-atcore is a special repository that you can use to add a README.md to your GitHub profile.")*
3. Set the repository visibility to **Public** *(required for it to show on your profile)*.
4. **Leave "Add a README file" unchecked** (since we already have the custom `README.md` right here).
5. Click **Create repository**.

---

## 💻 Step 2: Push This Repository to GitHub

In your terminal within `c:\dev\GitHubPortfolio`, run:

```bash
# 1. Initialize git
git init -b main

# 2. Add all files
git add .

# 3. Commit
git commit -m "feat: initial GitHub profile portfolio README with dynamic stats & showcases"

# 4. Link your remote repository
git remote add origin https://github.com/kiran-atcore/kiran-atcore.git

# 5. Push to GitHub
git push -u origin main
```

*(Once pushed, refresh your GitHub profile at `https://github.com/kiran-atcore` to see your portfolio live!)*

---

## 🐍 Step 3 (Optional): Enable the Contribution Snake Animation

We've pre-configured `.github/workflows/snake.yml`. To enable automated snake generation:

1. In your repository on GitHub (`kiran-atcore/kiran-atcore`), navigate to **Settings** > **Actions** > **General**.
2. Scroll to **Workflow permissions** and select **"Read and write permissions"**, then click **Save**.
3. Go to the **Actions** tab, select **"Generate Contribution Snake"**, and click **"Run workflow"**.
4. Once it finishes, the snake SVG will be saved in the `output` branch.
5. You can embed it in your `README.md` anytime with:
   ```markdown
   <picture>
     <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kiran-atcore/kiran-atcore/output/github-contribution-grid-snake-dark.svg">
     <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kiran-atcore/kiran-atcore/output/github-contribution-grid-snake.svg">
     <img alt="github contribution grid snake" src="https://raw.githubusercontent.com/kiran-atcore/kiran-atcore/output/github-contribution-grid-snake.svg">
   </picture>
   ```

---

## 🎨 Included Sections in Your Profile README

- **Dynamic Animated Banner**: Waving gradient banner with your name and title.
- **Typing SVG Animation**: Real-time typewriter effect cycling your core competencies.
- **Quick Links**: Direct badges for LinkedIn, Live Portfolio, Email, and GitHub.
- **About Me Card**: Structured YAML-style developer synopsis and background.
- **Metric Highlights**: Fast scannable impact stats (4+ systems, 75% time reduction, 50+ endpoints, 9+ certifications).
- **Categorized Badges**: High-contrast, brand-colored badges for Frontend, Backend, AI/ML, and DevOps.
- **Featured Projects Grid**: Detailed breakdowns of DispatchR, DeepFake Detection, Vicinio, and 3D Portfolio with direct links.
- **Verified Credentials**: AWS, DataBricks, and IBM certification lists.
- **Real-Time GitHub Stats**: GitHub Readme Stats, Top Languages breakdown, and GitHub Streak counter.
- **Footer Contact**: Modern interactive closing banner.
