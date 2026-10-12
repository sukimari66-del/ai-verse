# AIVerse — deployment instructions

**Status: the project source files are not uploaded to this repository yet.** This repository currently contains setup notes only, so do not deploy this repository through Vercel yet.

## Deploy the supplied project ZIP (recommended)

1. Download `aiverse-deploy-ready.zip` from the ChatGPT conversation and extract it on a Windows PC.
2. Install Node.js 22 LTS: https://nodejs.org/en/download
3. Open the extracted `aiverse` folder and double-click `DEPLOY_TO_VERCEL.bat`.
4. Follow the Vercel sign-in prompts. When deployment succeeds, copy the `https://...vercel.app` URL printed by the CLI.

Vercel CLI upload requires an internet connection and a Vercel account. A public website URL does not exist until Vercel completes the production build successfully.

## Project status

This is AIVerse Stage 1. It includes the homepage, featured AI tools, categories, theme toggle, and placeholder routes. AI chat, sign-in, custom AI creation, and personalised news are later stages. Stage 1 does not require API keys.

## Testing note

A full dependency install/build could not be completed in the packaging environment because access to the npm registry timed out. Vercel will perform installation and build during deployment. If it fails, review the build log.