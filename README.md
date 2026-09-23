# RCCG Living Spring Consecration Confession

A mobile-friendly, single-page consecration confession for RCCG Living Spring Miracle Center.

## Deploy on Vercel

### Option 1: Upload with GitHub

1. Create a new GitHub repository.
2. Upload all the files and folders from this project.
3. Sign in to [Vercel](https://vercel.com/).
4. Select **Add New → Project**.
5. Import your GitHub repository.
6. Leave **Framework Preset** as **Other**.
7. Leave the build command and output directory empty.
8. Select **Deploy**.

### Option 2: Deploy using the Vercel CLI

From inside this folder, run:

```bash
npx vercel
```

Follow the prompts, then run this when you are ready to publish publicly:

```bash
npx vercel --prod
```

## Project files

- `index.html` — the complete page, styling, and share/print functionality
- `assets/living-spring.png` — Living Spring logo
- `assets/rccg.png` — RCCG logo
- `vercel.json` — Vercel configuration

## After deployment

Open the URL Vercel gives you and confirm that the page and both logos load. Generate a new QR code using the final Vercel URL so the QR points to your own deployment.

