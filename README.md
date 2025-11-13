# Landing Page

A simple landing page with two buttons to navigate to different websites.

## GitHub Pages Deployment

This repository is configured to automatically deploy to GitHub Pages using GitHub Actions.

### Setup Instructions

1. **Enable GitHub Pages in Repository Settings:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Source", select "GitHub Actions"

2. **Automatic Deployment:**
   - The workflow automatically deploys when changes are pushed to the `main` branch
   - Manual deployments can be triggered via the "Actions" tab using "workflow_dispatch"

3. **Accessing the Page:**
   - Once deployed, the page will be available at: `https://mohanjayanti.github.io/landingpagelocal/`

### Workflow Configuration

The deployment workflow (`.github/workflows/pages.yml`) includes:
- Automatic trigger on push to main branch
- Manual trigger option via workflow_dispatch
- Proper permissions for GitHub Pages deployment
- Uses official GitHub Actions for reliable deployment

## Local Development

To test locally, simply open `index.html` in a web browser.
