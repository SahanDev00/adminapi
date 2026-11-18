ADMIN FRONTEND
1. Open app.js and replace https://YOUR-BACKEND.onrender.com with your deployed Render backend URL.
2. Deploy this folder as a separate Netlify site.
3. Add this site's URL to ALLOWED_ORIGINS on Render.
4. Sign in with ADMIN_PASSWORD configured on Render.
Admin session token is held in browser localStorage and expires after 12 hours. Use a strong unique admin password and do not share the admin URL publicly.
