# Personal Homepage Template

A clean academic one-page template for **Hanjun Luo**.

## Files
- `index.html`: content and section structure
- `publications.html`: complete publications subpage
- `styles.css`: visual style and responsive layout
- `script.js`: reveal animation, nav active state, dynamic year
- `assets/favicon.svg`: custom site icon

## Quick Start
Open `index.html` directly in a browser.

Or run a local static server:
```bash
cd /home/astar/workspace/tools/mainpage
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

## What to edit first
- Basic info: `index.html` hero section
- Publications and insights: `#publications` section in `index.html`
- Full publication list: `#publist` section in `publications.html`
- Headshot image: `assets/hanjun-headshot-sq.jpeg`
- CV file: `assets/CV_hanjun_luo.pdf`
- GitHub link: `https://github.com/Astarojth` in `index.html` and `publications.html`
- Theme colors/fonts: CSS variables at the top of `styles.css`
