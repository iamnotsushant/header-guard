# HeaderGuard — HTTP Security Header Review

A client-side checklist that reviews pasted HTTP response headers for several common browser security controls.

## Try it

Open `index.html`, paste response headers, and select **Review headers**. Use **Load example** to see the report. It checks CSP, HSTS, `X-Content-Type-Options`, clickjacking controls, `Referrer-Policy`, `Permissions-Policy`, and cookie flags.

The tool does not make a network request or scan a live site. Its score is a learning aid, not a security certification. Header settings must be evaluated against the app's requirements.

## GitHub Pages

Upload `index.html` and this README to a public repository. In **Settings → Pages**, publish from the `main` branch and `/ (root)`.
