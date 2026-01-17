# SECURITY — Operational Safety for This Repository

## No Secrets Policy
Do not commit:
- API keys, tokens, session identifiers
- VPN configs or exported credentials
- Private device identifiers
- Unredacted logs containing auth strings

## If a Secret Is Exposed
1. Revoke/rotate the secret immediately.
2. Remove the secret from the repository files.
3. If the secret was committed, rewrite history (do not rely on delete-only).
4. Consider temporarily making the repository private until confirmed clean.

## Reporting
If you believe unauthorized access occurred, preserve evidence:
- timestamps, screenshots, access logs, and GitHub audit events (where available).
