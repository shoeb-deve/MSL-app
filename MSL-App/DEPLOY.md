# Access MSL CRM on mobile anytime (even when laptop is OFF)

Because your project is static HTML/CSS/JS, you can host it publicly and open it from any phone browser.

---

## Method A (Recommended): Netlify (easiest)

1. Create a GitHub account (if you do not have one).
2. Create a new GitHub repository.
3. Upload/push this project to GitHub.
4. Go to [https://netlify.com](https://netlify.com) and sign in.
5. Click **Add new site** → **Import an existing project**.
6. Connect GitHub and select your repository.
7. Configure:
   - **Build command**: *(leave empty)*
   - **Publish directory**: `MSL-App`
8. Click **Deploy site**.
9. Netlify gives URL like: `https://your-site-name.netlify.app`
10. Open that URL in your mobile browser and login.

✅ Now your website works 24/7 even when VS Code and laptop are closed.

---

## Method B: GitHub Pages (free)

1. Push the project to GitHub.
2. Open your repo on GitHub.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: select your branch and folder `/MSL-App`
5. Save.
6. Wait 1–5 minutes.
7. You will get URL like: `https://your-username.github.io/repo-name/`
8. Open this URL on your phone.

---

## Mobile usage steps (after deployment)

1. Open the deployed URL on phone.
2. Login with your username/password.
3. Open browser menu and tap **Add to Home Screen**.
4. Next time, open app directly from phone home screen.

---

## Important notes

- Login state is saved in browser `localStorage`.
- If you clear browser data, you must login again.
- To update website later, edit code and push to GitHub again (Netlify/GitHub Pages auto-update).
