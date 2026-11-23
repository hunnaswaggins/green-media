# Green Media — Creator Hub

This is a free, static landing page for the Green Media YouTube channels.

## Preview locally
Open `index.html` in a web browser.

## Publish free with GitHub + Vercel

1. Create/sign in to a free GitHub account: https://github.com/
2. Create a new repository named `green-media`.
3. Upload `index.html` to the repository root and commit the change.
4. Create/sign in to Vercel: https://vercel.com/
5. Choose **Add New → Project**, import the `green-media` GitHub repository.
6. Keep the framework preset as **Other** and leave build/output settings at their defaults.
7. Click **Deploy**. Vercel will provide a public `*.vercel.app` address.
8. To update the site later, edit `index.html` in GitHub and commit; Vercel automatically redeploys.

## Channels currently included
- Gaming: Forza, BMX Streets, Minecraft
- IRL: Cars, Cats & Family
- BMX & Action Sports: Riding, Full Commit Riding

Seven channels are included in this first version. Add the eighth channel by copying one of the existing `<a class="card"...>` blocks in `index.html` and changing its URL, title, handle, and icon.

## Subscriber count update (future phase)
The current site does not display invented or stale counts. The next phase can add a small server-side endpoint plus a daily scheduled refresh using the YouTube Data API. Keep any API key server-side; do not put a private key in browser JavaScript.
