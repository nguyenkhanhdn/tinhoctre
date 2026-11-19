# Tin Học Trẻ – Bảng A (Python)

React + Vite frontend, Vercel Node API, Supabase Auth/PostgreSQL.

## Setup
1. `npm install && npm run dev`
2. Create a Supabase project and run `supabase/schema.sql`.
3. Copy `.env.example` to `.env.local`; set the service-role key only on the server.
4. Deploy to Vercel: build `npm run build`, output `dist`.
5. Deploy a separate isolated Python judge, configure `JUDGE_API_URL` and `JUDGE_API_TOKEN`. Never run untrusted student code in the Vercel API process.

## Status
This is an unfinished scaffold. The database, judge, and deployment are not configured. Additional source files from the local starter package still need to be committed before the app can build.