# DMDQO Design Trust

Official public trust anchors and release verification keys for DMDQO Design.

## Web Project Lite Public Bundle

**Product:** Web Project Lite Public Bundle — AI Web Project Starter  
**Signature algorithm:** Ed25519  
**Public key:** `keys/dmdqo-web-project-lite-ed25519-public.pem`  
**Public-key DER SHA-256:** `bba61d87a78be92ad656f25401f417e76b6373b53eab052715c2ed4db32df76d`

Use this public key as the DMDQO trust anchor when verifying signed Web Project Lite Public Bundle manifests. A bundle is not verified merely because a signature matches an arbitrary key; the verification key must match this published DMDQO trust anchor/fingerprint.

## Key continuity

A public verification key that has been used for a DMDQO signed release is immutable at its published path.

- Do not overwrite or delete an existing published public-key file used by a signed release.
- If a signing key is rotated or retired, publish the new public key at a new path with its own fingerprint.
- Keep prior public keys available so historical signed releases remain independently verifiable against the exact trust-anchor path and fingerprint recorded in their signed manifests.

Private signing keys are never published in this repository.
