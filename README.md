# Task 5 — Deploy a Static Website Using GitHub Pages

A responsive developer portfolio website built with HTML, CSS, and JavaScript. It is designed to be hosted for free using GitHub Pages.

## Files
- `index.html` — website content and page structure
- `style.css` — responsive layout, colors, and styling
- `script.js` — mobile navigation and automatic footer year

## Run locally
Open `index.html` in a browser. No build tools or package installation are required.

## Publish using GitHub Pages
1. Sign in to GitHub and create a **public** repository. For a user site, name it exactly `YOUR-USERNAME.github.io` (replace with your GitHub username).
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository's root folder.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for the deployment to finish. Your site should be available at `https://YOUR-USERNAME.github.io/`.
7. If you use a normal repository name instead, the URL is usually `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.
8. Replace the sample GitHub and email links in `index.html` with your real links before sharing.

## Interview questions — short answers
1. **What is Git and why use it?** Git is a distributed version-control system that records changes and helps developers collaborate.
2. **How do you push code to GitHub?** Stage changes, commit them, and push the commit to a remote repository (`git add .`, `git commit -m "message"`, `git push`).
3. **What is GitHub Pages?** A free hosting service for static websites stored in a GitHub repository.
4. **Static vs dynamic websites?** Static pages are served as prepared files; dynamic sites generate or personalize content using server-side logic or data.
5. **How do you revert commits in Git?** `git revert COMMIT_ID` creates a new commit that reverses an earlier commit. `git reset` changes history and should be used carefully.
6. **What is branching?** A branch is an independent line of development for making changes without directly changing another branch.
7. **What are pull requests?** A way to propose, review, and discuss changes before merging them into a target branch.
8. **How do you resolve merge conflicts?** Open conflicted files, decide the correct combined content, remove conflict markers, test, then commit the resolution.
9. **How can you host a website for free?** Options include GitHub Pages and other static hosting services, depending on their current free-tier terms.
10. **What is continuous deployment?** Automatically releasing validated code changes to an environment after they pass the configured workflow.

## Before submitting
- [ ] Replace sample profile/contact details.
- [ ] Confirm the repository is public if required.
- [ ] Confirm GitHub Pages deployment succeeds.
- [ ] Open the live URL in a private/incognito window.
- [ ] Submit both the repository link and the live website link if requested.

**Note:** Creating this project does not publish it automatically. You must upload it to your own GitHub account and enable GitHub Pages.
