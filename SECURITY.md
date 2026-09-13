# Security

VETUSTUS is currently Beta/Pre-Beta software.

## Sensitive material

Do not commit or publish:

- API keys or user credentials
- production Ed25519 activation signing private keys
- TLS private keys
- activation secrets or one-time administrative URLs
- private server configuration
- local vault contents or user data

The public verification material used by the client may be distributed with the application. Production signing private keys and server-side authorization secrets must remain on the official `vxd.mobi` infrastructure.

## Beta authorization

The current R8 build performs an automatic authorization/authenticity check with the official `vxd.mobi` service and validates an Ed25519-signed response. No account, email address or manual activation code is required.

The mechanism is intended to distinguish official authorization responses and discourage casual repackaging. It must not be described as impossible to bypass or as a substitute for operating-system code signing.

## Reporting a security issue

If you find a security issue, avoid posting exploitable details publicly before the maintainer has had a reasonable opportunity to review it. Use the contact route published on https://www.vxd.mobi/ when available.
