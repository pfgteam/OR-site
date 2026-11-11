# Open Ronin website

Marketing site for [Open Ronin](https://openronin.com), the open-source agent-driven agency operations platform.

The software itself lives in [pfgteam/open-ronin](https://github.com/pfgteam/open-ronin).

## Local

Open `index.html` in a browser, or run:

```bash
npx serve .
```

## Deploy

This repo is linked to the existing Vercel project `open-ronin`, which serves [openronin.com](https://openronin.com) and [open-ronin.vercel.app](https://open-ronin.vercel.app).

To update the Vote for Ronin link, edit `VOTE_FOR_RONIN_URL` near the top of `index.html` (and the matching constant in `404.html`).

## License

[Unlicense](UNLICENSE) (public domain).
