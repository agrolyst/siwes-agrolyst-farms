Agrolyst SIWES Portal
=====================

Student industrial-training application portal for Agrolyst Integrated Farms and Services.

Clean URL paths without .html: /, /login/, /dashboard/, /compliance/, /acceptance-letter/ and /admin/.

RENDER: Connect this repository to Render as a Static Site. The included render.yaml publishes the repository root and rewrites clean URLs to index.html. No build command is needed.

SUPABASE: Connected to project orhlccyodjuhwoaelmyd. Browser code uses only its publishable key, not a service-role or secret key. Expects public.siwes_applications, public.siwes_documents, and the private siwes-private Storage bucket.

Reviewer access uses trusted JWT app_metadata.siwes_role values reviewer or admin. Do not set a role from browser code. Add your Render hostname to Supabase Auth redirect URL settings and configure Google OAuth before testing Google sign-in.