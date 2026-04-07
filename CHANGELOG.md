# Changelog

All notable changes to the Smile Identity API specifications will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added

- Initial v3 OpenAPI specifications:
  - `v3-token.yaml` — Token generation (`POST /v3/token`)
  - `v3-biometric-enrollment-entry.yaml` — Biometric enrollment (`POST /v3/enroll`)
  - `v3-biometric-kyc-entry.yaml` — Biometric KYC (`POST /v3/biometric_kyc`)
  - `v3-enhanced-kyc-entry.yaml` — Enhanced KYC (`POST /v3/enhanced_kyc`)
  - `v3-replay-callback.yaml` — Callback replay (`POST /v3/replay/{job_id}`)
- Spectral validation workflow
- Redoc documentation site
