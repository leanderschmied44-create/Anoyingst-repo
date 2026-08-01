# Annoying HTMLs

A tiny, self-contained collection of playful annoying web pages. Each page uses only inline HTML, CSS, and JavaScript; there are no external packages, CDN assets, credential prompts, alert loops, or intentionally freezing scripts.

## Pages

- `index.html` — Landing page with cards linking to every demo and a quick note about the harmless chaos.
- `rainbow.html` — Full-screen animated rainbow gradients, loud headings, floating words, and rotating announcement text.
- `captcha.html` — Fake CAPTCHA panel with absurd prompts such as existential dread, suspicious Tuesdays, and raccoon identity checks.
- `dodging-button.html` — A button that dodges the cursor most of the time, with a very small random chance to become clickable briefly.
- `fake-loader.html` — A fake progress bar that climbs toward 99%, resets, and cycles through silly status messages forever.
- `marquee.html` — Bonus page with scrolling, bouncing, and blinking text inspired by classic marquee chaos.
- `youtube-skip-worse.html` — Fake video player with twenty intentionally terrible skip-ad buttons, each contained in one mini HTML page.

## Accessibility and safety notes

- Every demo includes a visible link back to `index.html`.
- Motion-heavy pages honor `prefers-reduced-motion` by drastically reducing animation duration.
- Dynamic status text uses `aria-live` where feedback changes after interaction.
- The annoyances are visual or interaction-based only; they do not trap the browser or request sensitive information.
