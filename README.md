# Camera Hub Botswana website

A simple static website. Products and shop details live in `data/` and are edited through `admin.html`, so you never need to touch code.

## Put it online with GitHub Pages (free)
1. Create a GitHub account, then a **new public repository** (e.g. `camera-hub`).
2. Upload everything in this folder to the repository (Add file > Upload files). Include the `data`, `assets` and `images` folders and `.nojekyll`.
3. Go to **Settings > Pages**. Under "Build and deployment" choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After about a minute your site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Update stock, prices and details
1. Create an access token: GitHub > Settings > Developer settings > Personal access tokens > **Fine-grained tokens** > Generate. Choose your repository only and set **Contents: Read and write**. Copy the token.
2. Open `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/admin.html`.
3. Enter your username, repository name, branch (`main`) and token, then Connect.
4. Edit products (price, stock, photo, show/hide, add, delete) or **Site details** (phone, WhatsApp, address, hours, map, homepage text).
5. Press **Publish changes**. The live site updates in about a minute.

Keep the token private. Anyone can open the admin page, but nobody can save changes without your token.

## Adding a domain later
Settings > Pages > Custom domain. Add the domain, then point its DNS records to GitHub as shown in their instructions.

## Good to know
- Replace the sample products, phone, WhatsApp (digits only, e.g. 26771234567) and address with your real details.
- The cart sends the customer's order to your WhatsApp. Online payments would need a shop platform later.
- Open the site through GitHub Pages, not by double-clicking `index.html`, or the products won't load.
- Other text (services, brands, footer) is in `index.html`; edit it on GitHub with the pencil icon.
