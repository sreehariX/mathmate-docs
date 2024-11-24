---
sidebar_position: 1
---

# Frontend Vercel

# Hosting MathMateAI Frontend on Vercel

## Setup

1. **Project Configuration**
   - Created `vercel.json` for build settings:



2. **Environment Variables**
   - Added this two variables in Vercel project settings->Environment Variables:
   ```
   VITE_API_URL=your_backend_url
   VITE_GOOGLE_CLIENT_ID=your_google_client_id
   ```
   

## Deployment Steps

1. **Connect Repository**
   - Sign up/login to Vercel
   - Select the frontend directory as root

2. **Configure Build**
   - Framework: Vite
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - devCommand: `npm run dev`
   - Install Command: `npm install`

3. **Deploy Through Vercel CLI**
   - Run `npm install` 
   - Run `npm run build`
   - Run `vercel`
   - Wait for build completion
   - Run `vercel deploy --prod`








## Cool thing about Vercel

1. **Vercel is pretty powerful**
   - They took care of the frontend build and deployment it is pretty east to setup.
   - You can setup the environment variables directly in the Vercel project settings.
   - They made the deployment process smooth

2. **Too good but**
   - As we know one your project gets bigger they charge pretty high.
   - But for small project it is good.
   - My next major goal understand vercel in depth.