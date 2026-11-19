React + TypeScript + Tailwind + Recharts + Leaflet. Run:

```bash
npm install
cp .env.example .env
npm run dev
```

- Air quality, weather, and place search use Open-Meteo (no API key).
- Surroundings use OpenStreetMap (Overpass API).
- Map station markers need `VITE_OPENAQ_KEY`.
- Scan logging to Supabase is optional: run `supabase/schema.sql`, then set the two Supabase variables.
- `VITE_DEMO_MODE=true` shows clearly labelled sample data.
- The `components/ui` files follow shadcn/ui conventions (cva + tailwind-merge). To use the full library, run `npx shadcn@latest init`.
