# Trainix Web

Marketing site and support pages for [Trainix](https://codeyardstudio.com/trainix/) — workout tracker, nutrition, habits, and coaching for iOS and Android.

## Pages

- `index.html` — landing page
- `faq.html` — help and FAQs
- `privacy-policy.html` — privacy policy
- `terms-of-use.html` — terms of use
- `dl/deep-link.html` — app download / deep link fallback

## Local preview

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Deploy

Static HTML — host on GitHub Pages, Cloudflare Pages, or any static file host. Point `codeyardstudio.com/trainix` (or your chosen domain) at this repo's published output.
