# Aaron Roodhart | Portfolio

Portfolio site set up for **GitHub Pages**.

## Hosting on GitHub Pages

### 1. Create a new repo on GitHub

- Repo is already created: **Wealthsimple-application**  
  [github.com/AaronRoodhart/Wealthsimple-application](https://github.com/AaronRoodhart/Wealthsimple-application)

### 2. Push this project from your computer

In **Terminal**, go to this folder and run:

```bash
cd "/Users/aaronroodhart/Downloads/Aaron Wealthsimple website"

git init
git add .
git commit -m "Initial commit: portfolio site"
git branch -M main
git remote add origin git@github.com:AaronRoodhart/Wealthsimple-application.git
git push -u origin main
```

If Git says you have not agreed to the Xcode license, run this first (then retry the commands above):  
`sudo xcodebuild -license`

### 3. Turn on GitHub Pages

- Open your repo on GitHub → **Settings** → **Pages** (left sidebar).
- Under **Build and deployment**:
  - **Source**: Deploy from a branch
  - **Branch**: `main` → **/ (root)** → **Save**.
- After a minute or two, the site will be at:  
  **https://aaronroodhart.github.io/Wealthsimple-application/**

## Assets

- Add your images in the **`assets`** folder. The site uses paths like `assets/article-preview.jpg`, `assets/dot-stationery.jpg`, etc. If a file is missing, placeholders (Unsplash) are shown via `onerror`.
- You can add any filenames you like and update the `src` in `index.html` to match, or use the same names as the current placeholders.

## Local preview

Open `index.html` in a browser, or run a simple server, e.g.:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
