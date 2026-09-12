# VETUSTUS build source

The private repository stores the alpha.13 base source as a Base64-encoded ZIP plus a small hardened overlay. GitHub Actions decodes the archive into a temporary build workspace, applies the hardened overlay, runs the full QA suite, and produces the Windows artifacts.

This layout deliberately keeps the distributable source out of public release artifacts. The Ed25519 private signing key is never stored here.
