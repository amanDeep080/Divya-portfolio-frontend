# Divya Singh — Portfolio (Frontend)

Static HTML portfolio. Deployed on **Vercel**.

## Files
```
frontend/
├── index.html     ← entire portfolio (single file)
├── vercel.json    ← tells Vercel this is a static site
├── .gitignore
└── README.md
```

## Deploy to Vercel
1. Push this `frontend/` folder to a GitHub repo (e.g. `divya-portfolio-frontend`)
2. Go to vercel.com → New Project → import that repo
3. Framework Preset → **Other**
4. Root Directory → leave blank (or `.`)
5. Click **Deploy**

## After deploying
Copy your Vercel URL (e.g. `https://divya-portfolio-7s7i.vercel.app`) and paste it into:
- Render backend → Environment variable `FRONTEND_URL`
- The `API_URL` line inside `index.html` (search for `YOUR-RENDER-APP`)
