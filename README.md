# Everywhere Routing Policy

This repository hosts the Android routing policy and manifest used by Everywhere VPN for automatic list updates.

## Files

- `manifest.json` - current policy version, SHA-256, and raw file URL
- `routing_policy.json` - routing overrides for:
  - direct RU traffic
  - foreign services routed via NL
  - domains forced through RU proxy

The Android app uses bundled fallback data first and then refreshes from this repository automatically.
