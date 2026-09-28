# Zachary Tayler website

A static academic website for GitHub Pages. No build tools are needed.

## Publish through your existing GitHub repository

1. Download and unzip the website package. Open the zachary-tayler-site folder. You should see index.html, cv.html, styles.css, script.js, and the assets folder.
2. In your GitHub repository, choose Add file → Upload files. Drag the contents of the folder, including the whole assets folder, into the upload area. Do not upload only the zip or put index.html inside another folder. Scroll down and select Commit changes.
3. Open Settings → Pages in that repository. For Build and deployment, select Deploy from a branch, choose main and / (root), then Save.
4. Wait a few minutes and open the Pages address shown in Settings → Pages. It often has the form https://USERNAME.github.io/REPOSITORY/.
5. After the site works at that address, enter your Cloudflare domain in the Custom domain field in Settings → Pages. Configure Cloudflare DNS according to GitHub's current custom domain instructions. Your exact records depend on your domain, GitHub username, and whether you want www or the bare domain as primary.

Before publishing, review the wording, CV entries, and photos. The supplied CV did not include a contact email or CV PDF, so the site links to an HTML CV and uses the Ohio University department page for contact. The Philadelphia Inquirer entry was omitted because its year and publication date conflicted. The 2027 presentations are marked as scheduled on the CV.

To update later, edit index.html or cv.html directly on GitHub (pencil icon), then commit. To replace a photo, upload a new image into assets and update its filename in the HTML.
