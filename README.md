
# Maalot Beit Yaakov — Vite + React + Tailwind

This package fixes Netlify build error `Cannot find package '@vitejs/plugin-react'` by adding the missing devDependency.

## Deploy with Netlify (GitHub import, no local git needed)
1. Upload all files in this folder to a new GitHub repository.
2. In Netlify: Add new site → Import an existing project → GitHub → select the repo.
3. Build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
   - (Optional) Environment variable: `NODE_VERSION = 18`
4. Deploy.

