# FliTunes library

My hand-curated album library: `library.json`, and the album covers in
`covers/`. It's the content shown by
[FliTunes](https://github.com/juliandescottes/flitunes), which loads it from
this repo.

Edit it with the app: clone both repos side by side, run `npm run dev` in the
app, and its Save button writes `library.json` here. Then commit and push this
repo. The file format is described in the app's `docs/spec.md`, and the
app's `scripts/covers/` copies new covers into `covers/`.
