# Jekyll Lab Starter (Minimal Mistakes)

A minimal, GitHub Pages–friendly starter for a personal research lab site using the **Minimal Mistakes** theme.

## Quick start
1. Create a repo named `YOUR-USERNAME.github.io` on GitHub.
2. Download this starter, unzip, and replace `YOUR-USERNAME` in `_config.yml`.
3. Commit and push to the new repo.
4. In **Settings → Pages**, ensure the site is building from `main` (root). Your site will be at `https://YOUR-USERNAME.github.io`.

## Local preview (optional)
- Install Ruby (3.1+ recommended), then:
```bash
gem install bundler
bundle install
bundle exec jekyll serve
```
Open http://127.0.0.1:4000

## Customize
- Edit `_data/navigation.yml` to change the top menu.
- Add people in `_people/`, publications in `_publications/`, projects in `_projects/`.
- New posts (news) go in `_posts/` as `YYYY-MM-DD-title.md`.
