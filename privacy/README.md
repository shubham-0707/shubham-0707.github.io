# Privacy policies

One self-contained HTML file per product. Each file is copied as-is into the build and served at:

    https://shubham-0707.github.io/privacy/<product>.html

| Product | File | Live URL |
|---|---|---|
| YTPlay | `ytplay.html` | https://shubham-0707.github.io/privacy/ytplay.html |

## Adding a product

1. Copy `ytplay.html` to `<product>.html` (lowercase, no spaces) and edit the content.
2. Keep it self-contained: inline CSS, no React, no build step.
3. Add a row to the table above.
4. Push to `master`. The deploy workflow publishes it in a few minutes.

Never add pages directly to the `shubham-0707.github.io` repo. Each deploy replaces that repo with the build, so anything not in this folder is deleted.
