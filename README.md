# Helixcer Chat — Home

Marketing site for [chat.helixcer.com](https://chat.helixcer.com).

The product app lives at [app.chat.helixcer.com](https://app.chat.helixcer.com).

## Local preview

```sh
python3 -m http.server 4173
```

Open `http://127.0.0.1:4173`.

## GitHub Pages

1. Settings → Pages → Deploy from branch `main` / `/ (root)`.
2. Custom domain: `chat.helixcer.com` (this repo includes a `CNAME` file).
3. At your DNS provider, point `chat` CNAME at `nisaran.github.io`.
4. Keep the app on `app.chat.helixcer.com` (the `helixcer-chat` repository).

Old app deep links such as `chat.helixcer.com/#inbox/...` redirect to `app.chat.helixcer.com`.
