# AquaGuard — Water Pollution Awareness Website

A responsive React + Vite single-page site based on the uploaded community service project report.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Create a GitHub repository and upload this project folder (keep `public/project-report.pdf`).
2. In Vercel choose **Add New → Project** and import the repository.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Click **Deploy**. No environment variables or backend are required.

The original PDF is available at `/project-report.pdf`. Pledges are stored locally in the visitor's browser; there is no central database.

## Notes

- The timeline displays the six weekly activity logs present in the uploaded report; the report states the overall programme duration as eight weeks.
- Field photos are extracted from the uploaded PDF. The website does not claim that visual appearance establishes drinking-water safety.
