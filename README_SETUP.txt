ELSHA website + Supabase admin dashboard

1) Run SUPABASE_SETUP.sql in Supabase Dashboard > SQL Editor.
2) Before running, verify that admin Auth UUID fa3aeec7-d173-463a-af97-b1fff003c684 is the user you created. If it differs, replace that UUID in the SQL policies.
3) Upload index.html and assets/ to the root of your GitHub Pages repository.
4) Open your site and click Admin. Sign in with the Supabase Auth email/password.
5) Add, edit, delete products and upload product images.

Only the publishable key is embedded in browser code. Never place the Supabase secret key in GitHub.
The products storage bucket is public only so visitors can view product images; upload/update/delete are restricted by RLS to the admin UUID.

Your original ZIP contained only index.html and assets/images/hero-kids.jpg. The page referenced other product photos that were not included. Missing photos display an ELSHA placeholder until you upload real images through Admin.
