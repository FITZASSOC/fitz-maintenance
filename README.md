# Fitz Maintenance

Daniel Florez's maintenance dashboard for Fitz & Associates, LLC (Reno properties): work orders, calls & texts, tenants and vendors, reimbursements, team messages.

The page itself holds no data. Everything is loaded from the fitz-ops Supabase project after sign-in, and the database decides what each person can see (role access grid in `public.role_access`). The key in `index.html` is Supabase's publishable key, which is meant to be public.

Published with GitHub Pages from the `main` branch.
