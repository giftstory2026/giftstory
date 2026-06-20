# Gift Story — Deployment Steps

This document explains how to deploy the Gift Story official website from GitHub to Cloudflare Pages.

The current live website uses the `public/` folder.

---

## 1. Official Repository

GitHub repository:

```text
giftstory2026/giftstory
```

The repository should be managed using the Gift Story GitHub account only.

Recommended local Git identity for this project:

```text
Name: Gift Story
Email: giftstory2026@gmail.com
```

---

## 2. Current Project Structure

The clean project structure should be:

```text
giftstory/
  README.md
  DEPLOYMENT_STEPS.md

  docs/
  website/
  commerce/
  forms/
  inventory/
  assets/

  public/
    index.html
    assets/
```

The live website file is:

```text
public/index.html
```

The `public/` folder is the only folder Cloudflare Pages should publish.

---

## 3. Active Source Rule

The `docs/` folder is the active source of truth for Gift Story.

The most important source file is:

```text
docs/00_MASTER_SOURCE.md
```

Files inside `archive/`, old uploaded references, or previous project versions are historical references only.

If any archived or older file conflicts with the active files inside `docs/`, the decision inside `docs/` must be followed.

---

## 4. What Goes Inside `public/`

Only live website files should go inside `public/`.

Allowed:

```text
public/
  index.html
  assets/
    website images
    logo files used by the website
    favicon
    og image
    optimized web assets
```

Do not put these inside `public/`:

```text
AI source files
large raw photos
old HTML files
archive files
internal documents
inventory files
pricing spreadsheets
unused mockups
private operation files
```

---

## 5. Source Folders Outside `public/`

These folders are project source and reference folders:

```text
docs/
website/
commerce/
forms/
inventory/
assets/
archive/
```

They are useful for managing the project, but they are not all meant to be published as the live website.

---

## 6. Cloudflare Pages Settings

Use these exact settings in Cloudflare Pages:

```text
Framework preset: None
Build command: leave empty
Build output directory: public
Root directory: leave empty
Production branch: main
Automatic deployments: Enabled
```

Important:

```text
Build output directory must be: public
```

This is because the live website file is:

```text
public/index.html
```

---

## 7. Clean GitHub Upload From VS Code

Use this method if you want to replace the old GitHub repository content with the current clean source.

Open the final Gift Story project folder in VS Code.

Then open Terminal and run:

```bash
git config user.name "Gift Story"
git config user.email "giftstory2026@gmail.com"
```

Check the current remote:

```bash
git remote -v
```

Remove the old remote if needed:

```bash
git remote remove origin
```

Add the correct Gift Story repository remote:

```bash
git remote add origin https://giftstory2026@github.com/giftstory2026/giftstory.git
```

Create a clean main branch from the current folder:

```bash
git checkout --orphan clean-main
git add .
git commit -m "Clean Gift Story source"
git branch -M main
git push -u origin main --force
```

Important:

```text
The --force command replaces the current GitHub repository content with the clean local source.
Use it only when the local folder is confirmed as the final clean version.
```

---

## 8. Normal Update Workflow After Clean Upload

After the clean upload is complete, future updates should use the normal workflow:

```bash
git status
git add .
git commit -m "Update Gift Story website"
git push origin main
```

Cloudflare Pages will automatically deploy after each push to `main`.

---

## 9. Updating Only the Website

If the update is only for the live website, usually update:

```text
public/index.html
public/assets/
```

Then run:

```bash
git add public
git commit -m "Update website"
git push origin main
```

---

## 10. Updating Documentation

If the update is related to project rules, brand decisions, pricing, operations, launch planning, or commerce structure, update the relevant files inside:

```text
docs/
website/
commerce/
forms/
inventory/
```

Then run:

```bash
git add .
git commit -m "Update project documentation"
git push origin main
```

---

## 11. GitHub Check After Upload

After pushing to GitHub, open:

```text
https://github.com/giftstory2026/giftstory
```

Confirm that these exist:

```text
README.md
DEPLOYMENT_STEPS.md
docs/
website/
commerce/
forms/
inventory/
assets/
public/index.html
```

Also confirm that old files are not mixed into the root, such as:

```text
old1.html
old2.html
old3.html
old4.html
old deployment files
random test files
```

---

## 12. Cloudflare Deployment Check

Open Cloudflare:

```text
Workers & Pages
giftstory
Deployments
```

Confirm:

```text
Latest deployment status: Success
Branch: main
Repository: giftstory2026/giftstory
```

Then open:

```text
https://giftstory.pages.dev
```

The website should load correctly.

---

## 13. Custom Domains

After Cloudflare Pages deployment succeeds, connect:

```text
gift-story.com
www.gift-story.com
```

In Cloudflare Pages:

```text
Pages Project
Custom domains
Add custom domain
```

Add:

```text
gift-story.com
```

Then add:

```text
www.gift-story.com
```

DNS changes may take time to activate.

---

## 14. Pre-Launch Checklist

Before announcing the website publicly, confirm:

```text
The website opens on mobile.
The website opens on desktop.
The design matches Gift Story identity.
The website is Arabic-first and RTL-friendly.
The main CTA is clear.
The shop link works or is intentionally disabled.
No placeholder text appears publicly.
No old WhatsApp-first checkout flow appears unless intentionally approved.
No old prices appear by mistake.
No logistics number appears publicly.
The official WhatsApp number is correct if used: +966576362810.
The internal logistics number is not shown as a public customer contact.
The website loads quickly.
Images are clean and optimized.
```

---

## 15. Current Launch Notes

The current Gift Story website is a brand and trust website.

The official website should:

```text
Introduce the brand.
Show the Gift Story world.
Present Little Stories as the first active direction.
Explain the packaging experience.
Show Coming Soon categories elegantly.
Guide customers to the active commerce platform.
Support special requests through a proper form when ready.
```

The official website should not be treated as a full checkout system unless this is intentionally changed later.

Sales, checkout, prices, payment, inventory, and order management should happen through the selected commerce platform such as Salla or Zid.

---

## 16. Shop Link Rule

The current shop link may be temporary:

```text
https://shop.gift-story.com
```

Replace it with the final Salla or Zid store link when the commerce platform is ready.

Do not announce the website as fully ready for ordering until the shop link or order flow is working properly.

---

## 17. Special Request Form Rule

The Special Gift Story Request page or button should eventually connect to an approved form, such as:

```text
Google Forms
Typeform
Tally
Salla/Zid custom form
```

Until the form is ready, avoid wording that makes customers think the request has been submitted automatically.

---

## 18. Troubleshooting

If Cloudflare shows a blank page or 404, check:

```text
Is public/index.html present?
Is Build output directory set to public?
Was the latest code pushed to GitHub?
Is Cloudflare connected to giftstory2026/giftstory?
Is Cloudflare connected to the main branch?
```

If images are not showing, check:

```text
Are the image files inside public/assets?
Are the file paths correct in public/index.html?
Are filenames spelled exactly the same?
Are filenames simple English names without spaces?
```

If the old website still appears, check:

```text
Was the latest commit pushed?
Did Cloudflare finish the new deployment?
Is the browser cache showing an old version?
Is the correct Pages project connected to the correct GitHub repository?
```

---

## 19. Final Deployment Rule

For the current Gift Story structure, the most important Cloudflare setting is:

```text
Build output directory: public
```

The most important live website file is:

```text
public/index.html
```

The most important source rule is:

```text
docs/ is the active source of truth.
```

GitHub is the source.

Cloudflare Pages is the publishing layer.

Gift Story should remain clean, premium, organized, and easy to update.
