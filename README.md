# J & M Designs

Temporary holding site for Railway. Made in Wilton, CT.

The page background is `#FEFEFE`, the same white as the logo, so the artwork sits flush. Under it, in black: **Currently in development**.

## Deploy

This is a static site with a small Node server. It listens on `0.0.0.0` and Railway’s `PORT`. There is no build step.

1. Open [railway.com/new](https://railway.com/new).
2. Choose **Deploy from GitHub repo**.
3. Select **StarFire-MWLord/j-and-m-designs**.
4. When the deploy finishes, open the service → **Settings → Networking → Generate Domain**.

Pushes to `main` redeploy automatically. When the real site is ready, archive this repo.
