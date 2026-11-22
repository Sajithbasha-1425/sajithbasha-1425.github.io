# Sajith Basha – Portfolio (GitHub Pages guide)

## Files
- `index.html` – the whole website
- `assets/` – CV PDF and the two project videos

## 1. Publish on GitHub Pages
1. github.com → New repository → name it `Sajithbasha-1425.github.io` (Public) → Create.
2. Add file → Upload files → drag in `index.html`, `README.md` and the `assets` folder → Commit changes.
3. Settings → Pages → Source: "Deploy from a branch" → Branch `main`, folder `/ (root)` → Save.
4. Wait 1–3 minutes, then open https://sajithbasha-1425.github.io

## 2. Make the contact form deliver to your inbox (Formspree)
1. Create a free account at formspree.io and click New Form (use sajithbasha1425@gmail.com).
2. Copy the form address, it looks like `https://formspree.io/f/abcdwxyz`.
3. On GitHub open `index.html` → pencil icon → find the line near the top that starts with
   `window.SB_CONFIG={formEndpoint:""` and put your address between the quotes:
   `formEndpoint:"https://formspree.io/f/abcdwxyz"`
4. Commit. Send a test message from your site; confirm it in Formspree if it asks.
If the service is ever down, visitors automatically get "Open Gmail" and "Copy message" buttons.

## 3. Public visit counter
The counter is already switched on for the GitHub version (`counterNamespace` in the same config line).
It counts once per browser session and shows "Portfolio visits" on the Home page. If it does not appear,
the free counter service is unavailable, and the page simply hides it. To turn it off, set `counterNamespace:""`.

## 4. Changing things later
Open `index.html` on GitHub, click the pencil, edit, and commit. Changes go live in about a minute.
