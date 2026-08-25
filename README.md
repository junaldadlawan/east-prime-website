# East Prime Print Lab — Website

A single-page site for East Prime Printing, built around the sunrise logo and dark navy/gold brand you're already using on your poster.

## Structure

```
index.html        the whole site (plain HTML/CSS, no build step, no dependencies)
assets/logo.png    full "EastPrime" wordmark + sunburst, transparent background
assets/sun-mark.png  the sunburst icon on its own, used in the hero
```

## Editing it

There's nothing to install. Open the folder in Claude Code (or any editor) and edit `index.html` directly — colors, copy, and layout are all in that one file. To preview changes, just open `index.html` in a browser, or run a tiny local server from this folder if you want auto-reload-style iteration:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Brand tokens (defined at the top of the `<style>` block)

| Token | Hex | Used for |
|---|---|---|
| `--bg` | `#17181b` | page background |
| `--gold` | `#f9c623` | sunburst / highlight gradient |
| `--amber` | `#f8a71a` | primary accent, buttons |
| `--white` | `#ffffff` | headlines |
| `--text-muted` | `#a2a6ae` | body copy |

Fonts (Google Fonts, already linked in `index.html`): **Baloo 2** for headlines, **Inter** for body text, **Oswald** for uppercase labels/badges.

## Still open (search "TODO" in `index.html`)

- Both "Message Us" buttons point to `#` — swap in your real Facebook Page / Messenger link once it's live.
- The "ID & Lanyard" capability card is marked "New capability" since it wasn't on your existing poster (equipment supports it via the PVC ID cutter) — remove that label, or the card entirely, if you'd rather not lead with it yet.
- Product line cards say "Bulk pricing soon" to match your poster — replace with real prices once you've settled on them.
- No real product photos yet — the design leans on the sunrise gradient and icon set instead of photography; swap in real shots of finished mugs/shirts/IDs whenever you have them.

## Related

The marketing strategy and social media plan this site is built from live in your East Prime Printing Claude project, and a combined playbook page was published separately.
