# GitHub Website Starter

A minimal static site you can deploy with **GitHub Pages** in minutes.

## Quick start

1. Create a new repo on GitHub (public recommended):  
   **Repository name:** `your-username.github.io` *(special case for a profile/root site)*  
   or any name for a project site, e.g. `my-site`.

2. Upload the files in this folder (or push with git).

3. Enable GitHub Pages:  
   - Go to **Settings → Pages**  
   - **Source:** `Deploy from a branch`  
   - **Branch:** `main` (root) → **Save**  
   - Wait ~1 minute, then open the shown URL.

4. (Optional) Custom domain:  
   Add your domain in **Settings → Pages**, then create DNS records as documented.

## Local development (optional)

```bash
# If starting from scratch on your computer
mkdir my-site && cd my-site
# Create files (copy from this starter)
# Initialize git
git init
git add .
git commit -m "Initial commit"
# Create a new repo on GitHub and connect it
git branch -M main
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main
```

## Notes

- Only static files run on GitHub Pages. For forms or databases, use a 3rd‑party service or a separate backend.
- For a site under a subpath (project site), make sure asset URLs are relative (as in this starter).
