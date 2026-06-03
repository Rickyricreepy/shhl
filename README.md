# Shanghai Huiluo Website

Static bilingual website for Shanghai Huiluo Trade Co., Ltd.

## Free deployment option: GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder to the repository root.
3. Make sure the default branch is `main`.
4. In GitHub, open Settings -> Pages.
5. Set Source to GitHub Actions.
6. Push or re-run the workflow named `Deploy static site to GitHub Pages`.

The site entry file is `index.html`. The GL-300 internal page is `gl300.html`.

## Notes

- The inquiry form uses a free mailto fallback, so it works on GitHub Pages without a backend.
- Downloadable MSDS/CTI documents are watermarked.
- For a real form inbox later, connect Netlify Forms, Formspree, Basin, or a small Cloudflare Worker.
