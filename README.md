# Travel Systems Academy — Professional LMS Starter

## Stack
- Next.js App Router
- React + TypeScript
- Supabase Auth + Postgres
- Supabase Row Level Security
- Responsive LMS UI
- Ready for MP4/HLS video storage
- Quiz and certificate data model
- Admin dashboard starter

## Local setup
1. Install Node.js 20+.
2. Create a Supabase project.
3. Run `supabase/schema.sql` in Supabase SQL Editor.
4. Copy `.env.example` to `.env.local`.
5. Add your Supabase URL and anon key.
6. Run:
   `npm install`
   `npm run dev`
7. Open http://localhost:3000.

## Production architecture
Recommended:
- Hosting: Vercel
- Database/Auth: Supabase
- Video files: Supabase Storage or a dedicated video CDN
- Domain: your own Travel Systems Academy domain
- HTTPS: automatic through the hosting provider

## Important production work
Before accepting paid enrollments, add:
- server-side admin authorization checks
- payment gateway/webhook handling
- secure private video storage / signed URLs
- email verification and password reset
- instructor/admin CRUD pages
- audit logs
- rate limiting and abuse protection
- privacy policy / terms / consent
- real certificate verification endpoint
- backups and monitoring

The supplied UI is an original LMS implementation and does not reproduce proprietary Amadeus course text, video, assets or branding.
