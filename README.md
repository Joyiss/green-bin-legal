# Green Bin Legal

A static GitHub Pages site containing the Green Bin Privacy Policy.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository named `green-bin-legal`.
2. Upload all files from this folder to the repository root.
3. Commit the files to the `main` branch.
4. Open the repository's **Settings**.
5. In the left sidebar, select **Pages**.
6. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
7. Select **Save**.
8. GitHub will display the published site URL after deployment.

The default URL will follow this format:

`https://YOUR_GITHUB_USERNAME.github.io/green-bin-legal/`

Use the final URL in:

- Google Play Console → Policy and programs → App content → Privacy policy
- The Green Bin app's Profile or About screen

## Before publishing

Open `index.html` and verify:

- The last-updated date
- The contact email
- The named service providers
- The production backend hosting description
- The target-audience language

## Optional custom domain

After buying a domain, add it in:

**Repository Settings → Pages → Custom domain**

GitHub will add or update a `CNAME` file. Configure the required DNS records with your domain provider, wait for DNS verification, and enable **Enforce HTTPS**.

## Updating the policy

1. Edit `index.html`.
2. Change the “Last updated” date.
3. Commit and push to `main`.
4. GitHub Pages will republish the site automatically.
