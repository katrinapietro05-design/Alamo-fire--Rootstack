# SECURITY MODEL

This repository intentionally excludes:
- secrets
- tokens
- credentials
- environment files
- runtime configurations

All execution keys are device-bound and rotated when exposed.

Public code is declarative, documentary, and non-operational by design.