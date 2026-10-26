# Update verification key

The public Ed25519 key in this directory identifies the initially configured ATRI update signer. The private signing key is not stored in either GitHub repository.

Clients must pin the trusted public key in their installed application. A key downloaded from an untrusted update feed does not establish trust and must not replace the installed key automatically.

This key publication does not indicate that an installer or stable update is available.
