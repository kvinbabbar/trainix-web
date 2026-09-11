# Trainix Web

Marketing site and support pages for [Trainix](https://trainix.codeyardstudio.com/) — workout tracker, nutrition, habits, and coaching for iOS and Android.

**Live site:** https://trainix.codeyardstudio.com

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

GitHub Pages from `main` with custom domain `trainix.codeyardstudio.com` (see `CNAME`).

Add a DNS `CNAME` record: `trainix` → `kvinbabbar.github.io` (or your Pages host).
