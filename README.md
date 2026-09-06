# Utsav Malik — Portfolio

A single-file static site (`index.html`). No build step needed.

## Deploy on Render

1. Push this folder to a GitHub repo (or upload it directly if Render supports a manual upload for your account).
2. On Render: **New +** → **Static Site**.
3. Connect the repo.
4. Settings:
   - **Build Command:** leave blank
   - **Publish Directory:** `.` (the root, since `index.html` sits at the top level)
5. Click **Create Static Site**. Render will give you a live URL in a minute or two.

## Editing content

Everything — text, colors, and layout — lives in `index.html`:
- Contact details (email, GitHub, LinkedIn) are near the bottom in the `#contact` section — swap in your real links.
- Colors are defined once at the top of the `<style>` block under `:root`, so changing `--red` or the green shades updates the whole site.
