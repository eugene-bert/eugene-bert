# eugene-bert

GitHub profile README repo. Content of `README.md` renders on the GitHub profile page.

## Structure

- `README.md` — profile page content (HTML + markdown)
- `.github/workflows/snake.yml` — generates contribution snake animation SVG

## CI

- `snake.yml` — runs on schedule, generates `github-contribution-grid-snake.svg` via `Platane/snk`

## Important

- Do not remove the snake workflow — it auto-generates the contribution graph animation
- README uses HTML for layout — preserve `<div align="center">` structure
