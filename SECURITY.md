# Security

This repository publishes static App Store legal pages only.

## What is public (by design)

- Privacy policy, support, and help HTML
- Stack. app icon assets used as favicons

## What is never stored here

- Game source code
- Private repository contents or links to private repositories
- API keys, tokens, certificates, `.env` files
- Backend credentials or database connection strings
- Build scripts that pull from private projects

## Hardening

- Pages are static HTML with **no JavaScript**
- Content-Security-Policy blocks scripts, network calls, framing, and forms
- Links stay within this site (plus mailto and Google’s public privacy policy)

If you find a security issue with these pages, email **support@khizermahmud.com**.
