# MANGO

A small web game + download hub powered by Supabase.

## Structure
- `game/` browser game prototype
- `website/` polished landing/download site
- `supabase/schema.sql` database schema + RLS

## Setup
1. Create a Supabase project.
2. Run `supabase/schema.sql` in the SQL editor.
3. Put the project URL and publishable key in `website/config.js`.
4. Replace the download URL in `website/config.js` with the real game build.
