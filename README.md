# Smile Identity API Reference

OpenAPI 3.0 specifications for the Smile Identity v3 API.

## Endpoints

<!-- SPEC_TABLE_START -->
| Spec | Endpoint | Description |
|------|----------|-------------|
| [Biometric Authentication](specs/v3/v3-biometric-authentication-entry.yaml) | `POST /v3/authentication` | Submit biometric authentication |
| [Biometric Enrollment](specs/v3/v3-biometric-enrollment-entry.yaml) | `POST /v3/registration` | Submit biometric enrollment |
| [Biometric KYC](specs/v3/v3-biometric-kyc-entry.yaml) | `POST /v3/biometric_kyc` | Submit Biometric KYC verification |
| [Document Verification](specs/v3/v3-document-verification-entry.yaml) | `POST /v3/document_verification` | Submit Document Verification |
| [Enhanced Document Verification](specs/v3/v3-enhanced-document-verification-entry.yaml) | `POST /v3/enhanced_document_verification` | Submit Enhanced Document Verification |
| [Enhanced KYC](specs/v3/v3-enhanced-kyc-entry.yaml) | `POST /v3/enhanced_kyc` | Submit Enhanced KYC verification |
| [One Time Aml](specs/v3/v3-one-time-aml-entry.yaml) | `POST /v3/aml` | Submit One-Time AML screening |
| [Replay Callback](specs/v3/v3-replay-callback.yaml) | `POST /v3/replay/{job_id}` | Replay a callback for a completed verification |
| [Report User Fraud](specs/v3/v3-report-user-fraud.yaml) | `POST /v3/users/{user_id}/report_fraud` | Flag or clear fraud status for a user |
| [Services](specs/v3/v3-services.yaml) | `GET /v3/services/bank_codes` | List bank codes |
| [Services](specs/v3/v3-services.yaml) | `GET /v3/services/id_status` | Get ID type availability status |
| [Services](specs/v3/v3-services.yaml) | `GET /v3/services/supported_documents` | List supported documents for verification |
| [Services](specs/v3/v3-services.yaml) | `GET /v3/services/supported_id_types` | List supported KYC ID types |
| [Smart Selfie Compare](specs/v3/v3-smart-selfie-compare-entry.yaml) | `POST /v3/compare` | Submit smart selfie compare |
| [Token](specs/v3/v3-token.yaml) | `POST /v3/token` | Generate v3 Auth Token |
| [Verification Status](specs/v3/v3-verification-status.yaml) | `GET /v3/status/{jobId}` | Get verification status |
<!-- SPEC_TABLE_END -->

> The table above is regenerated automatically on each spec sync. Don't hand-edit between the markers.

## Documentation

Rendered API documentation is available via [GitHub Pages](https://smileidentity.github.io/api-reference/).

The page is styled with the Smile ID design system. `docs/tokens.css` is a verbatim copy of that
system's generated `dist/css/tokens.css` — don't hand-edit it. To refresh it, copy the file across
again and record the source revision below. Its own header refers to a `tokens/` directory and a
build command that belong to the design system repo, not this one.

| | |
|---|---|
| Copied from | Smile ID design system, `dist/css/tokens.css` |
| Copied on | 25 July 2026 |

CI checks that every `--si-*` token `docs/index.html` references is defined in `docs/tokens.css`, so
a rename in a refreshed copy fails the build rather than silently unstyling the page.

## Using the Specs

### Import into Postman

1. Open Postman → Import → File
2. Select any spec from `specs/v3/`
3. Postman will generate a collection with all endpoints and example requests

### Generate Client SDKs

Use [OpenAPI Generator](https://openapi-generator.tech/) directly against any spec file:

```bash
npx @openapitools/openapi-generator-cli generate \
  -i specs/v3/v3-token.yaml \
  -g python \
  -o ./generated-client
```

### Validate Specs

```bash
npx --yes @stoplight/spectral-cli@^6.14.0 lint specs/v3/*.yaml
```

## Versioning

Specs are versioned and released alongside the Smile Identity v3 API. Each release here corresponds to a deployed API version; see [CHANGELOG.md](CHANGELOG.md) for version history and [Releases](https://github.com/smileidentity/api-reference/releases) for tagged versions.

## Links

- [Smile Identity Documentation](https://docs.usesmileid.com/)
- [API Status](https://status.usesmileid.com/)
