# Publishing your GitHub portfolio

Replace `your-username` with your actual GitHub username everywhere below.

## Part 1: Portfolio website (GitHub Pages)

1. On GitHub, click **New repository**.
2. Name it exactly **`your-username.github.io`**, set it to **Public**, and create it.
3. Upload `index.html` and `style.css` from the `portfolio-site` folder:
   - Easiest: on the repo page click **Add file → Upload files**, drag both files in, then **Commit changes**.
   - Or with Git:
     ```
     git clone https://github.com/your-username/your-username.github.io
     cd your-username.github.io
     # copy index.html and style.css into this folder
     git add .
     git commit -m "Add portfolio site"
     git push
     ```
4. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
5. Wait 1-2 minutes. Your site is live at `https://your-username.github.io`.

## Part 2: Profile README

1. Create another new repository named exactly **`your-username`** (the same as your username). It must be **Public**.
2. Tick **Add a README file** when creating it (GitHub shows a "special repository" notice).
3. Open `README.md`, click the pencil icon, paste in the contents of `profile-readme/README.md`, and commit.
4. Visit `https://github.com/your-username`. The README now appears at the top of your profile.

## Part 3: Make it yours

- Replace every placeholder in both files (name, university, email, links, projects).
- Pin your 3-6 best repositories: on your profile click **Customize your pins**.
- Give each pinned project a clear README with a screenshot, what it does, and how to run it.
- Add a profile photo and a short bio under **Settings → Public profile**.
- No projects yet? Turn a class assignment into a repo, or build a small project (to-do app, budget tracker, data analysis of a public dataset).

## Part 4: Preview locally (optional)

Double-click `portfolio-site/index.html` to open it in your browser and check changes before uploading.
