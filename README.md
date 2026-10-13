# Talent Jack portfolio

TanStack Start and Vite application configured for Vercel.

## Run locally

```sh
npm install
npm run dev
npm run build
```

## Deploy on Vercel

Import this repository into Vercel. The `vercel.json` file selects the TanStack Start framework. Use the default build command (`npm run build`). No Lovable account or environment variables are required.

## Change images

All page images are referenced from `public/images` as `/images/<filename>.svg`. Replace a file with your own image while keeping the filename, or update the corresponding `src/pages-html/*.body.html` reference to a `.png`, `.jpg`, or `.webp` file you add there. The original image bytes were not present in the Git repository: Lovable stored them outside Git and several illustrations were served from Google. The included labeled placeholders make the missing images visible until originals are provided.

Keep the original image files in your own backup before replacing the placeholders.
