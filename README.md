# SuperReview website

The website for [SuperReview](https://github.com/AutobotsAITech/SuperReview),
an open-source code review skill by [OmniTensorLabs](https://www.omnitensorlabs.com/).

**Live site:** https://superreview.omnitensorlabs.com/

## Local preview

```sh
python3 -m http.server 8000 --directory public --bind 127.0.0.1
```

Open `http://127.0.0.1:8000`. The site uses plain HTML, CSS, and JavaScript.
There are no dependencies, external fonts, analytics, or build step.

## Deployment

Vercel serves `public/` using the configuration in `vercel.json`.
The connected project deploys `main` to production and provides previews for pull requests.
Domain and certificate settings are managed in Vercel; DNS is managed in Cloudflare.

Before publishing, check mobile and desktop layouts, keyboard navigation, agent selection,
and copying the install command. Keep installation examples aligned with the library.

MIT licensed.
