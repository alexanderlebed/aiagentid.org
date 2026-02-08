# Optional Blockchain Anchoring

## Purpose

The AI Agent Registry may optionally anchor agent declarations
to a public blockchain in order to provide
cryptographic proof of existence and timestamping.

Anchoring serves as an evidentiary layer.
It does not define agent identity, authority, or behavior.

## Scope

Blockchain anchoring is:

- optional,
- non-normative,
- chain-agnostic,
- declarative only.

The registry remains the canonical source of meaning.
The blockchain serves as an immutable witness.

## Anchored Data (Minimal)

Only a cryptographic hash MAY be anchored, derived from:

- Agent ID
- declared scope of delegation
- responsible principal
- standard version
- registration timestamp

No personal data, executable logic,
or registry content is stored on-chain.

## Interpretation

Anchoring does not assign legal liability,
certify behavior,
or imply endorsement.

It provides verifiable proof
that a specific declaration existed at a specific time.

## Versioning

Blockchain anchoring is not part of Agent ID Standard v0.1.

It is reserved for a future version
as an optional extension.
