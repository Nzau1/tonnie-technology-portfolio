# Tonnie Technology Portfolio — Render deployment

This is a static, responsive website. It works on phones, tablets, and desktop browsers.

## Deploy to Render

1. Create or sign in to your Render account: https://render.com/
2. Put the contents of this folder into a GitHub repository. The `index.html`, `render.yaml`, and `assets/` folder must be at the repository root.
3. In Render, choose **New +** → **Blueprint** and connect that GitHub repository.
4. Render will detect `render.yaml`. Review the service named `tonnie-technology-portfolio` and click **Apply**.
5. Wait for deployment to finish. Render will provide a public `onrender.com` URL.

Alternative: create a **Static Site** in Render and select the repository. Set the publish directory to `.` and leave the build command blank.

## Before publishing
- The website intentionally omits CEO/founder titles and private contact details.
- The contact button opens an email draft without a hard-coded email address. Add a public contact address only if you want one displayed.
