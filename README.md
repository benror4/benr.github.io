# benr.me starter (GitHub Pages + Jekyll)

## Write a Post
- Add a file in `_posts/` named `YYYY-MM-DD-your-title.md` with front matter:
  ```yaml
  ---
  layout: post
  title: "Your Post Title"
  date: 2025-01-01 09:00:00 -0500
  ---
  ```
- Write in Markdown below the front matter.

## Edit Projects Page
- Open `projects.md` and add sections / links as you wish.

## Customize
- Tweak `_config.yml` (title, description, links, theme options).
- The theme is **minima** (built-in on GitHub Pages).

## DNS for Namecheap → GitHub Pages
In Namecheap → Domain List → benr.me → **Advanced DNS**:
A records (apex):
- `@ → 185.199.108.153`
- `@ → 185.199.109.153`
- `@ → 185.199.110.153`
- `@ → 185.199.111.153`

AAAA (optional IPv6):
- `@ → 2606:50c0:8000::153`
- `@ → 2606:50c0:8001::153`
- `@ → 2606:50c0:8002::153`
- `@ → 2606:50c0:8003::153`

CNAME:
- `www → benr.github.io`

Keep the `CNAME` file in the repo containing exactly `benr.me`.

## Troubleshooting
- After DNS changes, give it some time to propagate.