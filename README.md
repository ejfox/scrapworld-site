# scrapworld-site

Landing page for [scrapworld](https://github.com/ejfox/scrapworld), served at
https://ejfox.github.io/scrapworld-site/

**Don't edit here.** The source of truth is `docs/` in the (private) scrapworld
repo — edit the markdown in `docs/content/` there and run `docs/deploy.ps1`,
which copies the site into this repo and pushes.

- `index.html` — single-file page, no build step; fetches and renders the markdown
- `content/features.md` — feature list
- `content/hotkeys.md` — keymap (mirrors `PauseMenuManager.Keymap` in-game)
- `content/guide.md` — getting started / guides
