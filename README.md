# Setugo Governance Root

External public trust-anchor repository for the governed AI development platform.

This repository contains public verification material only. It MUST NOT contain private signing keys, API keys, tokens, passwords, or other secrets.

Authoritative TESTING trust root:

- ID: `SETUGO_MANUAL_GOVERNANCE_ED25519_V1`
- Algorithm: Ed25519
- Public key: `trust-roots/SETUGO_MANUAL_GOVERNANCE_ED25519_V1.pem`
- DER SHA-256: `2b1b97ab0bf99e71f4a93f51fd8e6c3eb30063d83ba2eb4c091492a95f9c11f2`

Governance rule: candidate/runtime code may read or verify against this public material but must not be able to modify this repository through candidate execution credentials. Changes to this repository are manual governance actions and require explicit human control. The repository should be archived after initialization to make the root read-only during TESTING qualification.

This repository does not itself grant RELEASE or PRODUCTION authority.
