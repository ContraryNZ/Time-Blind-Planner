# Time Blind Day Planner — GitHub Pages Setup Guide

## What you need
- Your GitHub account (you already have this)
- The **day-planner** folder containing these files:
  - `index.html` (the app)
  - `manifest.json` (tells phones it's an app)
  - `sw.js` (makes it work offline)
  - `icons/icon-192.png` and `icons/icon-512.png`

## Step 1: Create a new repository

1. Go to **github.com** and sign in
2. Click the **+** button (top right) → **New repository**
3. Name it: `day-planner`
4. Make sure **Public** is selected (required for free GitHub Pages)
5. Tick **"Add a README file"**
6. Click **Create repository**

## Step 2: Upload the files

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag in ALL the files from the day-planner folder:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - The `icons` folder (with both .png files inside)
3. Click **"Commit changes"** at the bottom

## Step 3: Turn on GitHub Pages

1. Go to your repository's **Settings** tab (top menu)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** and leave the folder as **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes, then refresh the page

You'll see a message: **"Your site is live at:"** followed by your URL.

It will be something like: `https://yourusername.github.io/day-planner/`

## Step 4: Install it on your phone

1. Open that URL in Chrome on your phone
2. You should see a banner saying **"Add Time Blind to Home screen"** — tap it
3. If no banner appears: tap the **three-dot menu** → **"Add to Home screen"** (Android) or **Share** → **"Add to Home Screen"** (iPhone/Safari)
4. It now sits on your home screen like a real app
5. It works offline once you've loaded it the first time

## Sharing with your friend

Just send them the link! e.g. `https://yourusername.github.io/day-planner/`

They open it, install it to their home screen, and they get their own blank planner. Everyone's data is private — stored only on their own device.

## Updating the app later

If you make changes (e.g. using Claude Code!):
1. Go to your repository on GitHub
2. Click the file you changed → pencil icon to edit, or upload the new version
3. Commit the changes
4. The live site updates within a minute or two

**Tip:** When you update, change `day-planner-v1` to `day-planner-v2` (etc.) in `sw.js` so phones pick up the new version.
