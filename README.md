# 🥃 Whisky Journal

En personlig whisky-smagningsapp med pointsystem.

## Sådan deployer du på Vercel (gratis)

### Trin 1 – Upload til GitHub
1. Gå til [github.com](https://github.com) og opret en gratis konto (hvis du ikke har en)
2. Klik på **"New repository"**
3. Giv den et navn, f.eks. `whisky-journal`
4. Klik **"Create repository"**
5. Klik på **"uploading an existing file"**
6. Træk alle filerne fra denne mappe ind (inkl. `src`-mappen og `public`-mappen)
7. Klik **"Commit changes"**

### Trin 2 – Deploy på Vercel
1. Gå til [vercel.com](https://vercel.com) og opret en gratis konto
2. Klik **"Add New Project"**
3. Vælg dit GitHub-repository (`whisky-journal`)
4. Klik **"Deploy"** – Vercel finder automatisk at det er et Vite-projekt
5. Efter ca. 1 minut får du en URL som f.eks. `whisky-journal.vercel.app`

### Trin 3 – Føj til hjemskærm
**Android (Chrome):**
1. Åbn din Vercel-URL i Chrome
2. Tryk på de tre prikker øverst til højre
3. Vælg "Føj til startskærm"

**iPhone (Safari):**
1. Åbn din Vercel-URL i Safari
2. Tryk på del-ikonet (firkant med pil op)
3. Vælg "Føj til hjemskærm"

## Lokal udvikling
```bash
npm install
npm run dev
```
