# Luck Pro deployment

## Static demo
This project is currently a frontend/localStorage demo.

### Vercel
1. Upload this folder to a GitHub repository.
2. Import the repository into Vercel.
3. Framework preset: Other (or leave automatic detection).
4. Build command: leave empty.
5. Output directory: leave empty / root.
6. Deploy.

Pages:
- `/index.html` — landing page
- `/auth.html` — login/signup
- `/dashboard.html` — member dashboard
- `/panel.html` — admin/customization UI
- `/admin.html` — admin dashboard UI

## Production upgrade
For real accounts and rewards, replace localStorage with:
- secure server-side authentication
- PostgreSQL/Supabase database
- server-side referral validation
- transaction/points ledger
- protected admin authorization
- audit logs

Never store real passwords or sensitive financial information in localStorage.
