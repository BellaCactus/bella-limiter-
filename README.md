
---

# 2) bella cactus website README (same style, no emoji headings)

```md
<div align="center">

# 🖤 bella cactus (github pages)

terminal-core personal website.  
black/white/pink by default, optional red “evil” palette.

**static-only** (github pages), **no backend**, just **html/css/js**.

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-ff78c8?style=for-the-badge)
![Static](https://img.shields.io/badge/Static--Only-no%20backend-0b0b0b?style=for-the-badge)
![HTML/CSS/JS](https://img.shields.io/badge/Stack-HTML%20%2F%20CSS%20%2F%20JS-ff4db8?style=for-the-badge)

</div>

---

## what is this?

**bella cactus** is my personal terminal-themed website playground.  
it’s meant to feel like a fake OS / interactive terminal hub rather than a normal portfolio.

this repo is basically:
- mini tools
- experiments
- weird pages
- secrets / easter eggs
- “why did i add this” moments

---

## vibe

- fake-os / terminal playground aesthetic
- black / white / pink palette
- optional red mode (evil palette)
- meant to be explored, not skimmed
- subtle motion > loud motion

---

## highlights

- **intro gate**: auto-playing video if the browser allows it (otherwise click once)
- **music bar + waveform**: random track picker + waveform line
- **terminal script**: types little commands and responses
- **sticker wall**: random image stickers behind the UI
- **command palette**: quick actions + navigation
- **easter eggs**: oneko, secrets, and assorted nonsense

---

## pages

main pages that match the “site world” vibe:

- `index.html` : main hub (terminal + music + stickers + palette)
- `limiter.html` : bella limiter page
- `os.html` : fake cli / fake os page
- `ascii.html` : ascii zoo
- `idle.html` : screensaver-style page (leave it open)
- `glitch.html` : glitch / corruption playground
- `dreams.html` : surreal dream log

extra mini-tools / experiments:

- `encrypter.html`
- `ascii-art-maker-type-shit.html`
- `keyb.html`
- `snkaegame.html`
- `dungeoncrawler.html`
- `shitty-ass-gamez-3d.html`
- `controllar-test.html`
- `boucnignlolgo.html`
- `sigmaness-basiclaly-epic.html`
- `legacy-home.html`
- `shrines.html`
- `vault.html`

---

## controls (good to know)

### index.html

- **ctrl+k** (or **/**) opens the command palette
- **esc** closes palette / overlays

the palette understands stuff like:
- `open dreams`, `open idle`, `open glitch`
- `theme pink` / `theme white` / `theme red`

### idle.html screensaver

- **space**: pause/resume
- **r**: reroll sprites/text
- **t**: cycle theme
- **esc**: back to `index.html`

---

## customization

### change the soundtrack

the music list lives in `index.html` (search for `const tracks = [`)

- drop `.mp3` files in the repo root (same folder as `index.html`)
- add them to the tracks list
- keep filenames exact (spaces + punctuation matter)

### change stickers

the sticker filenames are also listed in `index.html` (search `stickerFiles`)

- add images (`.png/.jpg/.gif`) to the repo root
- update the list

### theme persistence

theme is saved in `localStorage` under:

- `bella_theme` (values: `pink`, `white`, `red`)

---

## run locally

quick and dirty:
- double-click `index.html` and it will mostly work

recommended (avoids some browser weirdness with media):

```bash
# from the repo folder
python -m http.server 8000
