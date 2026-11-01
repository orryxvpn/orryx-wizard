# Release security

Official release metadata is signed with Ed25519. Downloaded packages must match the signed size andSHA256. The public key is included in the application and this repository. The private signing key is never distributed. A failed or expired signature must not be bypassed to install an update.

The local dashboard has a separate password. No subscription links, router passwords, GitHub tokens or private keys belong in issues. Contact https://app.orryx.org/#/support-chat/new for security reports.

This is authenticity and integrity verification, not unbreakable DRM, hardware attestation or OS code signing. A patched verifier can bypass client-side checks. The application does not expose its dashboard to the Internet by default.
