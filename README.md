# VRP — Sales Channel & Pipeline

Go-to-market operating system for **Vanscoy Rare Pharmacy** (Pittsburgh): how the commercial team sources exclusive / limited-distribution rare therapy business and runs pipeline toward institutional scale.

## Demo on Vercel (shareable link)

The live demo is static HTML at `public/index.html` (served at `/`).

**Important:** Production must deploy a branch that includes `public/index.html`. If Vercel is pointed at an empty `main`, you will get a 404.

### Option A — Fastest (Import / Redeploy)

1. Go to [vercel.com/new](https://vercel.com/new) **or** open the existing VRP project → **Deployments**
2. Import / deploy branch **`main`** (after this PR is merged) — or set Production Branch to this PR branch temporarily
3. Framework Preset: **Other** · Output Directory: leave default / blank (do **not** set a custom empty folder)
4. Deploy → open the `*.vercel.app` URL (root `/` is the sales kit)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Pelusi83/VRP)

### Option B — CLI from this repo

```bash
npx vercel login
npx vercel          # preview URL
npx vercel --prod   # production URL
```

No build step.

### Option C — Fix an existing 404

If the project already exists and shows Vercel’s 404 page:

1. Vercel → Project → **Settings → Git** → Production Branch = `main` (with this code) **or** `cursor/vrp-sales-channel-pipeline-ba0f`
2. **Settings → General → Build & Development**: Framework = Other, Build Command empty, Output Directory empty
3. **Deployments → Redeploy** the latest commit that contains `public/index.html`

---

## Start here (local)

Open the handoff package:

**[sales-kit/VRP_Sales_Channel_Pipeline.html](sales-kit/VRP_Sales_Channel_Pipeline.html)**

Then read **[sales-kit/HANDOFF.md](sales-kit/HANDOFF.md)** for install steps, file map, and 90-day success criteria.

## Kit contents

```
sales-kit/
├── VRP_Sales_Channel_Pipeline.html   # Boardroom brief (print to PDF)
├── HANDOFF.md                        # Head of Sales install guide
├── data/
│   ├── pipeline-tracker.csv          # Stage model + import template
│   ├── target-account-framework.csv  # ICP book structure (Lanes A–D)
│   └── channel-calendar.csv          # Annual channel cadence
└── templates/
    ├── discovery-talk-track.md
    ├── executive-email-sequences.md
    └── win-loss-codes.md
```

## Commercial focus

- **Primary offer:** Exclusive / limited specialty pharmacy for rare & orphan therapies  
- **Buyers:** Biopharma market access, patient services, brand/commercial, trade  
- **Channels:** Named-account hunting, Asembia/BIO/NASP, referrals, thought leadership, displacement, ecosystem  
- **Proof points (public):** Redemplo® (plozasiran) exclusive SP; Cycle VENXXIVA exclusive pharmacy partner
