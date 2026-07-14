# JBS Interiors — Project & Finance System

## Deploying to Vercel
1. Go to vercel.com and click "Add New Project".
2. Choose "Import" and drag in this folder (or push it to a GitHub repo first and import that repo).
3. Vercel will detect it as a static site — no build settings needed, just deploy.
4. You'll get a live URL like `jbs-interiors.vercel.app` you can send to the client.

## Login (demo only)
- Manager account: emma@gmail.com / 1234
- Once signed in as manager, use "Users & Staff" to add staff accounts (e.g. Project Coordinator, Site Supervisor) with their own email/password.
- Staff accounts can use Quotations, Materials, Projects and the transaction ledger, but net profit figures and the Users & Staff page stay manager-only.
- This is a front-end-only check for demo purposes — it is not real authentication, and passwords are stored in plain text in the browser. Do not use real passwords.

## Important: data storage
This version saves data in the browser's local storage, so it works standalone once deployed.
That means:
- Data is stored per browser/device — you and the client will NOT see the same data unless you're on the same browser.
- Clearing browser history/cache will erase the data.
- This is fine for a click-through demo of the features. If the client wants a real shared system where the whole team sees the same live data, that needs a proper database added next — flag it to me and I'll build that layer in.
