# Betcy Business – GitHub Pages website

This is a static website: it needs **no backend, database, Google password, or WhatsApp API**.

## Publish free on GitHub Pages

1. Create a new GitHub repository, for example `betcy-business`.
2. Upload the contents of this folder (including `index.html`, `favicon.svg`, `robots.txt`, and `sitemap.xml`) to the repository root.
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`, then save.
5. GitHub gives you the live website address in a few minutes.

The website is already ready for GitHub Pages: it contains only static HTML, CSS, JavaScript and image files. No server setup is needed.

## How customer requests work

The customer completes the form and chooses WhatsApp or Gmail. The complete request message opens automatically. A selected file cannot be sent automatically by a static website: the customer attaches it manually in the WhatsApp or Gmail message before pressing Send. This is a security restriction of both services.

After getting a custom domain, replace `YOUR-DOMAIN.example` in `sitemap.xml` and `robots.txt` with the real website address.

## Google setup after publishing

- **Google Search Console:** add the live website as a property, then submit `https://YOUR-SITE/sitemap.xml`. Google gives you a verification value to add to the page.
- **Google Analytics:** create a free Google Analytics property, then add its Measurement ID (`G-...`) to `index.html`. An ID is required before Analytics can collect visits.
