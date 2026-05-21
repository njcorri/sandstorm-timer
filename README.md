# 🟢 Sandstorm Timer

A 1-minute countdown timer that plays Darude - Sandstorm. Hit Start, vibe.

## Deploy to Railway

### Option A: GitHub (recommended)

1. Push this folder to a new GitHub repo:
   ```
   git init
   git add .
   git commit -m "sandstorm timer"
   gh repo create sandstorm-timer --public --push
   ```

2. Go to [railway.app](https://railway.app) → **New Project** → **Deploy from GitHub repo**

3. Select your repo. Railway auto-detects Node.js and runs `npm start`.

4. Once deployed, click **Settings → Networking → Generate Domain** to get a public URL.

### Option B: Railway CLI

```bash
npm install -g @railway/cli
railway login
railway init
railway up
railway domain
```

## Local dev

```bash
node server.js
# open http://localhost:3000
```
