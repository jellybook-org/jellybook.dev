# jellybook.dev

Website for [Jellybook](https://github.com/jellybook-org/jellybook), served
through GitHub Pages at **jellybook.dev**.

Plain HTML and CSS with no build step. `index.html` carries an inline SVG
sprite for every icon; the only external request is the Google Fonts
stylesheet (Quicksand and Inconsolata).

Deployment files that must stay put: `CNAME` (custom domain) and
`.nojekyll` (stops Pages running the files through Jekyll).