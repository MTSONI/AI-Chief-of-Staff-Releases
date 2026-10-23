# AI Chief of Staff — Releases

This is the **public release-hosting repository** for the AI Chief of Staff desktop
application. It exists so installed copies of the app can fetch update metadata and
signed installers over HTTPS **without any credentials**.

It contains **only**:
- signed Windows installers (`AI-Chief-of-Staff-Setup-<version>.exe`),
- their `.blockmap` files, and
- the `latest.yml` update manifest,

attached to GitHub Releases.

It contains **no source code, no secrets, no credentials and no customer data**.
The application source lives in a separate private repository.

No production release has been published yet. Releases appear here only after a build
is code-signed by the publisher and passes the gated release procedure.