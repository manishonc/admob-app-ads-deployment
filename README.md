# AdMob app-ads.txt Deployment

This repository contains the app-ads.txt file required for AdMob integration.

## Deployment Steps for Cloudflare Pages

1. Log in to your Cloudflare dashboard
2. Go to Pages > Create a project > Connect to Git
3. Select this repository
4. Configure your build settings:
   - Build command: (leave empty)
   - Build output directory: / (root directory)
5. Deploy site

After deployment, your app-ads.txt file will be accessible at:
`https://your-project-name.pages.dev/app-ads.txt`

Use this URL in your AdMob settings.
