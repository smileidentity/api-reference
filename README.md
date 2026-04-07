# Smile Identity API Reference

OpenAPI 3.0 specifications for the Smile Identity v3 API.

## Endpoints

| Spec | Endpoint | Description |
|------|----------|-------------|
| [Token](specs/v3/v3-token.yaml) | `POST /v3/token` | Generate authentication token |
| [Biometric Enrollment](specs/v3/v3-biometric-enrollment-entry.yaml) | `POST /v3/enroll` | Biometric selfie enrollment |
| [Biometric KYC](specs/v3/v3-biometric-kyc-entry.yaml) | `POST /v3/biometric_kyc` | Biometric + KYC verification |
| [Enhanced KYC](specs/v3/v3-enhanced-kyc-entry.yaml) | `POST /v3/enhanced_kyc` | ID authority verification |
| [Replay Callback](specs/v3/v3-replay-callback.yaml) | `POST /v3/replay/{job_id}` | Replay a callback webhook |

## Documentation

Rendered API documentation is available via [GitHub Pages](https://smileidentity.github.io/api-reference/).

## Using the Specs

### Import into Postman

1. Open Postman → Import → File
2. Select any spec from `specs/v3/`
3. Postman will generate a collection with all endpoints and example requests

### Generate Client SDKs

Use [OpenAPI Generator](https://openapi-generator.tech/) with the bundled spec:

```bash
npx @openapitools/openapi-generator-cli generate \
  -i bundled/openapi-v3.yaml \
  -g python \
  -o ./generated-client
```

### Validate Specs

```bash
npm install
npm run validate
```

## Versioning

Spec versions are synced with the [Smile Identity API releases](https://github.com/smileidentity/lambda). When a new version is tagged in the main API repository, specs are automatically copied here and a matching release is created.

See [CHANGELOG.md](CHANGELOG.md) for version history.

## Links

- [Smile Identity Documentation](https://docs.usesmileid.com/)
- [API Status](https://status.usesmileid.com/)
