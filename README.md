# Balaji Automobiles CRM V3
Complete static Supabase CRM for Balaji Automobiles, Susner.

## Setup
1. Run `supabase.sql` in Supabase SQL Editor.
2. Create your first user in Supabase Authentication.
3. Promote that user's profile to owner:
`update public.profiles set role='owner' where id=(select id from auth.users where email='YOUR_OWNER_EMAIL');`
4. Put your Supabase Publishable Key in `config.js`.
5. Never put a Supabase Secret/service_role key in frontend code.
6. Upload all files to the root of a GitHub repository.
7. Enable GitHub Pages from the repository Settings > Pages.
8. Open the GitHub Pages URL on computer and phone.

## Features
Owner/Staff login, cloud enquiries, employee assignment, today's and overdue follow-ups, click-to-call, follow-up history, owner employee metrics, reports and CSV export. Data is stored in Supabase so it is shared across devices.
