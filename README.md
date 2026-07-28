# VRP — Sales Channel & Pipeline

Go-to-market operating system for **Vanscoy Rare Pharmacy** (Pittsburgh): how the commercial team sources exclusive / limited-distribution rare therapy business and runs pipeline toward institutional scale.

## Demo on Vercel (shareable link)

### Option A — Fastest (Import Git repo)

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import **`Pelusi83/VRP`**
3. Leave Framework Preset as **Other** (static)
4. Click **Deploy**
5. Share the URL Vercel gives you (e.g. `https://vrp-xxxx.vercel.app`)

Root `/` opens the sales kit demo automatically.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Pelusi83/VRP)

### Option B — CLI from this repo

```bash
npm i -g vercel
vercel login
vercel          # preview URL
vercel --prod   # production URL
```

No build step. Static HTML only (`vercel.json` rewrites `/` → the sales kit).

### Option C — GitHub connected project

In Vercel → Add Project → select this repo → Deploy. Every push to the connected branch gets a new preview URL; `main` gets production.

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
