# TravelPilot

An offline-first intelligent Delhi trip planner and disruption-management demo.

## Run

```bash
npm install
npm run dev
```

Open http://localhost:3000.

For deployment, copy `.env.example` to `.env.local` and set `NEXT_PUBLIC_SITE_URL` to the custom domain you control. The canonical URLs, sitemap, robots file, Open Graph metadata, and schema will then use that domain. DNS and domain registration must be completed with your hosting provider.

## Verify

```bash
npm test
npm run build
```

The itinerary is structured state. Generation, travel time, cost estimation, validation, disruption repair, diffing, and chat all run locally with deterministic data. No API keys are required.
