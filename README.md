# Little Sprouts website: setup in 3 parts

## Part 1. Put the files on GitHub (5 min)
1. On github.com click **+** then **New repository**. Name it `little-sprouts-website`, choose **Public**, click **Create repository**.
2. Click **uploading an existing file**. Unzip this folder, then drag EVERYTHING inside it (admin, content, images, index.html, netlify.toml) into the page. Click **Commit changes**.
3. Your username and repository name are already set in `admin/config.yml`. Use exactly `little-sprouts-website` as the repository name in step 1 so they match.

## Part 2. Connect Netlify to GitHub (this is the automatic sync)
1. On app.netlify.com click **Add new site**, then **Import an existing project**, then **GitHub**. Approve access and pick your repository.
2. Leave the build command empty and the publish directory as `.`, then click **Deploy**.
From now on every change saved to GitHub (including edits made in the CMS) is published by Netlify automatically in about a minute.

## Part 3. Let the CMS log you in (one time only)
1. GitHub: **Settings, Developer settings, OAuth Apps, New OAuth App**.
   Homepage URL = your Netlify address. Authorization callback URL = `https://api.netlify.com/auth/done`. Register, then click **Generate a new client secret**.
2. Netlify: **Site configuration, Access and security (Access control), OAuth, Authentication providers, Install provider**. Choose GitHub and paste the Client ID and Client Secret.
3. Visit `your-site.netlify.app/admin` and log in with GitHub.

## Photos
Upload photos in the CMS (any image field) or replace files in `images/`. Suggested sizes:
- Hero: 1600 x 1250 px, children playing together
- About: 1200 x 960 px, a calm classroom moment
- Programme panels (2): 1280 x 720 px, one daycare and one tuition scene
- Gallery (5 to 6): 1200 x 900 px each, mixing activities and children
- Teachers (3): 600 x 600 px, face centred
- Map: use a screenshot of your location
Use your own photos with parents' written consent, or licensed stock images. Keep a mix of children from your community.
