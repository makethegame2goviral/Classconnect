# ClassConnect

ClassConnect is a responsive private class space built with HTML, CSS, JavaScript and Supabase.

## Included
- Email/password sign-up and sign-in
- Private rooms with 12-character invitation codes
- Live group chat using Supabase Realtime
- Shared room notes with automatic saving
- Member list and mobile/iPad-friendly layout
- Row Level Security on all ClassConnect database tables
- PWA manifest and static asset cache

## Open the website
After GitHub Pages is enabled, the site is available at:

https://makethegame2goviral.github.io/Classconnect/

The repository includes a GitHub Actions deployment workflow. The first workflow run attempts to enable Pages automatically. If GitHub blocks that action, open **Settings → Pages** and select **GitHub Actions** as the build source, then rerun the workflow.

## Accounts
Each person creates their own account with an email address and password. Email addresses are not shown to room members; use an alias/display name rather than posting personal information in a room.

## Supabase
The app uses the NEXYRON Supabase project with a browser-safe publishable key. No service-role or secret key is included in the website.
