# Jin Li Homepage Notes

This worktree customizes the WD7ang/WowPage Jekyll template into Jin Li's academic homepage.

## Main Files

- `_config.yml`: site identity, author profile, email, GitHub, Google Scholar, and repository metadata.
- `_data/navigation.yml`: top navigation anchors and CV link.
- `_pages/about.md`: homepage content, including news, education, experience, publications, projects, awards, patents, and skills.
- `assets/css/home.css`: homepage-specific responsive layout and card styling.
- `files/LI_Jin_CV.pdf`: CV copied from `/Users/jolley/Documents/LI Jin-CV (0605).pdf`.
- `images/publications/`: publication poster images copied from `/Users/jolley/Documents/my_papers`.

## Run Locally

The project is a Jekyll site based on Academic Pages / GitHub Pages:

```bash
bundle install
bundle exec jekyll serve
```

On this machine, the default macOS Ruby is `2.6.10`, while the current `github-pages` dependency resolution pulls gems that require Ruby 3. Use Ruby 3.x, for example through `rbenv`, `asdf`, Homebrew Ruby, or GitHub Pages' build environment, before running the commands above.

## Content Sources

- CV: `/Users/jolley/Documents/LI Jin-CV (0605).pdf`
- Paper projects: `/Users/jolley/Documents/my_papers`
- Google Scholar: `https://scholar.google.com/citations?user=SkpNdIoAAAAJ&hl=zh-CN`
- GitHub: `https://github.com/Rivflyyy`
- Featured projects:
  - `https://github.com/Rivflyyy/HappyTorch`
  - `https://github.com/Rivflyyy/OpenVTON-Bench`

## Image Generation Note

The request asked to use the `$imagegen` skill for paper posters. The skill instructions were loaded, but this session did not expose a callable built-in `image_gen` tool. To keep the site usable, the current version uses real figures from the local LaTeX paper projects as publication poster assets. These can be replaced later with generated bitmap posters if the image generation tool or CLI fallback with `OPENAI_API_KEY` is available.
