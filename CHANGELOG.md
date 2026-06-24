# Changelog

All notable changes to the Smile Identity API specifications will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [v3.695.0] - 2026-06-23

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-smart-selfie-compare-entry`
- Updated `v3-token`


## [v3.694.0] - 2026-06-23

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-smart-selfie-compare-entry`


## [v3.667.0] - 2026-06-15

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-smart-selfie-compare-entry`


## [v3.662.0] - 2026-06-15

### Changed
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-report-user-fraud`
- Updated `v3-services`
- Updated `v3-smart-selfie-compare-entry`


## [v3.640.0] - 2026-06-05

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-report-user-fraud`
- Updated `v3-smart-selfie-compare-entry`

## [v3.639.0] - 2026-06-05

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-report-user-fraud`
- Updated `v3-smart-selfie-compare-entry`

## [v3.638.0] - 2026-06-05

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-report-user-fraud`
- Updated `v3-smart-selfie-compare-entry`

## [v3.637.0] - 2026-06-05

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-report-user-fraud`
- Updated `v3-smart-selfie-compare-entry`

## [v3.636.0] - 2026-06-04

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-report-user-fraud`
- Updated `v3-smart-selfie-compare-entry`

## [v3.635.0] - 2026-06-04

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-report-user-fraud`
- Updated `v3-smart-selfie-compare-entry`

## [v3.634.0] - 2026-06-04

### Changed
- Updated `v3-report-user-fraud`

### Removed
- `v3-block-user`

## [v3.619.0] - 2026-05-29

### Changed
- Updated `v3-biometric-authentication-entry`

## [v3.553.0] - 2026-05-08

### Changed
- Updated `v3-services`
- Updated `v3-verification-status`

### Removed
- `v3-enhanced-kyc-job-status`
- `v3-id-status`
- `v3-supported-documents`

## [v3.549.0] - 2026-05-08

### Changed
- Updated `v3-biometric-authentication-entry`
- Updated `v3-biometric-enrollment-entry`
- Updated `v3-biometric-kyc-entry`
- Updated `v3-block-user`
- Updated `v3-document-verification-entry`
- Updated `v3-enhanced-document-verification-entry`
- Updated `v3-enhanced-kyc-entry`
- Updated `v3-enhanced-kyc-job-status`
- Updated `v3-id-status`
- Updated `v3-replay-callback`
- Updated `v3-services`
- Updated `v3-smart-selfie-compare-entry`
- Updated `v3-supported-documents`
- Updated `v3-token`


### Added

- Initial v3 OpenAPI specifications:
  - `v3-token.yaml` — Token generation (`POST /v3/token`)
  - `v3-biometric-enrollment-entry.yaml` — Biometric enrollment (`POST /v3/enroll`)
  - `v3-biometric-kyc-entry.yaml` — Biometric KYC (`POST /v3/biometric_kyc`)
  - `v3-enhanced-kyc-entry.yaml` — Enhanced KYC (`POST /v3/enhanced_kyc`)
  - `v3-replay-callback.yaml` — Callback replay (`POST /v3/replay/{job_id}`)
- Spectral validation workflow
- Redoc documentation site
