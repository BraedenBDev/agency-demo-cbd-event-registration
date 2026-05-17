# agency-demo-cbd-event-registration

CBD-branded event registration module — single-page form that generates a QR code with the registrant data. Hosted at `https://cbd-event-registration.demo.almostimpossible.agency`.

## Stack
- Static `index.html` + `app.js` + `libs/qrcode.min.js`
- Zero-dependency Node http server (`server.js`) for hosting

## Local
```
node server.js
# → http://localhost:5173
```

## Deploy
Auto-deploys to Coolify (VM 200) on push to `main` via the `CoolifyAAL` GitHub App.

See `AGENTS.md` for app behavior notes.
