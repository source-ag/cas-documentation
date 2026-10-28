# Plant Measurements documentation

Grower documentation for the Source **Plant Measurements**, published at
<https://source-ag.github.io/cas-documentation/>.

It explains what Plant Measurements is, how the app is used screen by screen, the measurement
protocol, and the glossary — in English, Dutch and French.

## This repository holds output, not source

`index.html` is **generated**. Editing it here is a dead end: the next publish
overwrites the file wholesale.

The source lives in the monorepo, at
[`frontends/mobile-app/docs/cas-documentation/`](https://github.com/source-ag/source/tree/main/frontends/mobile-app/docs/cas-documentation)
— prose in `content.mjs`, structure in `template.html`, screenshots in `shots/`.

To change the site: edit the source there, run `node build.mjs`, and copy the
resulting `dist/index.html` over the `index.html` in this repository.

The page is one self-contained file with its screenshots inlined, so this
repository is only ever the single HTML file plus this README.
