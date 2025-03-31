# Cookie E-commerce Store Deployment Guide

This guide will help you deploy your cookie business e-commerce store with 3D interactive elements to a hosting platform of your choice.

## What's Included in This Package

- `src/`: Source code for the application
  - `app/`: Next.js application pages and routes
  - `components/`: Reusable React components including 3D cookie viewer
  - `lib/`: Utility functions and data
- `public/`: Static assets including cookie images
- Configuration files:
  - `package.json`: Dependencies and scripts
  - `tsconfig.json`: TypeScript configuration
  - `next.config.js`: Next.js configuration

## Deployment Options

### Option 1: Deploy to Vercel (Recommended for Next.js)

1. Extract the package contents
2. Create a GitHub repository and upload the files
3. Sign up for a free Vercel account at https://vercel.com
4. Connect your GitHub account to Vercel
5. Select "Import Project" and choose your repository
6. Vercel will automatically detect it's a Next.js project
7. Click "Deploy" and your site will be live in minutes with a custom domain (e.g., cookie-store.vercel.app)

### Option 2: Deploy to Netlify

1. Extract the package contents
2. Sign up for a free Netlify account at https://netlify.com
3. From the Netlify dashboard, click "New site from Git"
4. Connect your GitHub repository (after uploading the code)
5. Set build command to: `npm run build`
6. Set publish directory to: `.next`
7. Click "Deploy site"

### Option 3: Manual Deployment

If you prefer to deploy to your own hosting:

1. Extract the package contents
2. Install dependencies: `npm install` or `pnpm install`
3. Build the project: `npm run build`
4. Start the production server: `npm start`
5. The site will be available at http://localhost:3000 by default

## Development Setup

If you want to make changes to the code before deploying:

1. Extract the package contents
2. Install dependencies: `npm install` or `pnpm install`
3. Start the development server: `npm run dev`
4. Open http://localhost:3000 in your browser
5. Make your changes to the code
6. The browser will automatically refresh to show your changes

## Features Overview

- **3D Interactive Elements**: The store includes a 3D cookie viewer that allows customers to:
  - Rotate and zoom in on cookies
  - Customize cookie colors and toppings
  - Take a virtual "bite" out of cookies

- **E-commerce Functionality**:
  - Product listings with search and filtering
  - Shopping cart with quantity controls
  - Checkout process

- **Design**:
  - Cute pastel color scheme
  - Playful typography and decorative elements
  - Responsive design that works on all devices

## Customization

- To modify product data: Edit `src/lib/products.ts`
- To change colors and styling: Edit `src/app/globals.css`
- To update images: Replace files in the `public/images/` directory

## Need Help?

If you encounter any issues during deployment or have questions about customizing your store, please reach out for assistance.
