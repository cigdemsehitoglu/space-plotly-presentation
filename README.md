# Beyond Earth: Interactive Exploration of the Solar System

An original R Markdown presentation featuring **interactive Plotly visualizations** of Solar System data.

## Features
- Beautiful xaringan presentation (16:9)
- Two interactive Plotly plots (hover, zoom, pan)
- Current date automatically inserted
- Clean modern design with space-themed styling

## How to render locally

1. Open `index.Rmd` in RStudio
2. Make sure these packages are installed:
   ```r
   install.packages(c("rmarkdown", "xaringan", "plotly", "dplyr"))
   ```
3. Click **Knit** → HTML

## Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload all files in this folder
3. Go to **Settings → Pages**
4. Source: Deploy from a branch → `main` / `root` (or `/docs` if you put the HTML there)
5. After rendering, rename the output HTML to `index.html` and push it

Alternatively you can publish the knitted HTML directly to RPubs or NeoCities.

## Date
This document was created on the date shown in the presentation (uses `Sys.Date()`).

Enjoy exploring the Solar System interactively!
