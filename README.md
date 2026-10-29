# NutriMesh

> Household Nutrition Mesh — Shared-pot calorie tracking, an AI meal logger, an optimisation engine, and a 450+ dish Indian nutrition catalogue.

## Features

- **The Shared-Pot Simulator**: Real-time multi-family member portion calculation and macronutrient distribution.
- **Dynamic Island Navigation**: Floating navigation bar with language selection, theme switching, and smooth section scrolling.
- **NutriMesh Flow Dashboard**: Built-in dashboard interface for detailed household nutrition tracking.
- **Multi-language Support**: English, Hindi, Marathi, Tamil, Telugu, Bengali, Gujarati, and Punjabi.
- **Dark / Light Mode**: Tailored HSL color palette and ambient canvas mesh animation.

## Project Structure

```
nutrimesh/
├── index.html            # Main landing page
├── styles.css            # Global styling and design system tokens
├── app.js                # Core landing page interactivity and localization
├── assets/               # Brand assets and graphics
│   ├── hero-mesh.jpg
│   └── logo.png
└── dashboard/            # Local dashboard application
    ├── index.html
    └── assets/
        ├── index-BFOqa3Hw.css
        └── index-DQQKmG5Q.js
```

## Deployment on Vercel

1. Import this repository in [Vercel](https://vercel.com/new).
2. Framework Preset: **Other** (Standard Static Site).
3. Root Directory: `./` (default).
4. Click **Deploy**. Both the main site (`/`) and the dashboard (`/dashboard`) will be served seamlessly.
