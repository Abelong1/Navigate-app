# NaviGate

A pocket reference app for Computer Engineering students, built with React + Vite.

## Run locally

```bash
npm install
npm run dev
```

## Deploy

### 1. Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

(Create the empty repo on GitHub first at https://github.com/new — don't
initialize it with a README so there's no merge conflict with this push.)

### 2. Deploy to Vercel

**Option A — Vercel dashboard (easiest):**
1. Go to https://vercel.com/new
2. Import the GitHub repo you just pushed.
3. Framework preset: Vite (auto-detected). Build command `npm run build`,
   output directory `dist` (auto-detected).
4. Click Deploy.

**Option B — Vercel CLI:**
```bash
npm install -g vercel
vercel login
vercel --prod
```
