# Deploy Groundwork Digital Website

## Step 1: Push site code to GitHub

Run these commands in your terminal:

```bash
# Navigate to the Groundwork Digital folder in your Documents
cd ~/Documents/Groundwork\ Digital

# Initialize git repo
git init

# Add website files
git add index.html logo_v2_concept_1.svg logo_v2_concept_2.svg logo_v2_concept_3.svg

# Commit
git commit -m "Initial commit: Groundwork Digital Studio website"

# Set the branch to main
git branch -M main

# Connect to your GitHub repo
git remote add origin https://github.com/apappas57/groundwork-digital-website.git

# Push
git push -u origin main
```

## Step 2: Deploy on Vercel

1. Go to https://vercel.com/new
2. Paste this URL: `https://github.com/apappas57/groundwork-digital-website`
3. Click "Deploy"
4. Wait ~30 seconds — your site will be live at `groundwork-digital-website.vercel.app`

## Step 3: Register domain (optional but recommended)

1. Go to https://ventraip.com.au or https://crazydomains.com.au
2. Search for `groundworkdigital.com.au`
3. Register it (~$30/year) — you'll need your ABN: 42 538 114 280
4. In Vercel dashboard → your project → Settings → Domains
5. Add `groundworkdigital.com.au`
6. Update DNS at your registrar to point to Vercel (Vercel will show you the exact records)
