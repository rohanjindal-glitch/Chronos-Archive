# Chronos Archive

A pixel-art time-travel detective game in a single static page. No build step.

## Deploy to Vercel

**Option A: Vercel CLI**
1. Install Node.js (https://nodejs.org) if you don't have it.
2. Unzip this folder, open a terminal inside it, and run:
   ```
   npx vercel        # first run: log in and accept the defaults
   npx vercel --prod # publish to your production URL
   ```

**Option B: GitHub + Vercel dashboard**
1. Create a new GitHub repository and upload `index.html`, `vercel.json` and this README.
2. In Vercel, choose Add New > Project, import the repository.
3. Framework preset: Other. Leave build command and output directory empty. Deploy.

Controls: WASD/arrows move, Shift sneak, E interact, Space takedown, Q Chrono Sense, J casebook, H manual, Esc pause.
