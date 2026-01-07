# PGP Key Management Notes

## Objective
The goal of this exercise was to understand and apply basic Public Key Cryptography (PGP)
for secure communication and identity verification.

## Key Generation
- A PGP key pair was generated using standard parameters.
- The private key was kept secure and was **never shared or uploaded**.
- The public key was exported in `.asc` format for distribution.

## Public Key Usage
- Public keys can be shared to allow others to:
  - Encrypt messages intended for the key owner
  - Verify digital signatures
- Only public keys are included in this repository.

## Security Considerations
- Private keys must never be exposed or committed to version control
- Public keys are safe to share, but should not contain sensitive metadata
- Key backups should be protected using encryption and secure storage

## Lessons Learned
- Public key cryptography enables secure communication without sharing secrets
- Key management is as important as key generation
- Proper separation between public and private data is essential for OPSEC

