# The Techy Baba — Phase 2

Responsive React + Vite storefront with a separate developer sign-in route.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173/).

## Developer portal preview

Open `/vijayverma` on the same local host, e.g. `http://localhost:5173/vijayverma`.

**Local prototype credentials (demo only):**
- Username: `vijayverma`
- Password: `Vijay@TTB2026!`

The login check is currently client-side for UI demonstration only. It is not secure authentication and must not be deployed as a production access control. Before publishing, move authentication to a backend, store a salted password hash, issue secure server-side sessions, and enforce role-based access on every protected API route. Change the demo password before any public deployment.

## Phase 2 changes

- Removed developer sign-in from the shopper login modal on the public homepage.
- Kept shopper sign-in and account creation actions in the main site.
- Added a standalone developer portal at `/vijayverma` with a responsive sign-in design.
- Added demo login feedback and a post-login placeholder state.
- User auth, developer dashboard, database, and server-enforced permissions remain future backend work.
