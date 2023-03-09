# Reproduction for netlify redirects not working with 11ty serve

Steps to reproduce

1. clone the repo
2. `npm i`
3. `npm run dev`
4. Click in the browser on "Should still be good". The url should change, but the title should stay the same.

This works with `eleventy --serve` and `netlify dev`.
