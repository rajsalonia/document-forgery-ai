# Contributing to Proofly

Proofly is an explainable fraud-risk analysis **prototype**, not a substitute for certified document verification or financial advice.

## Guidelines
1. Discuss larger architecture or detection changes in an issue before implementing.
2. Use synthetic examples for all uploaded files. Never commit real IDs, passports, bank documents, private communications, or credentials.
3. Keep outputs **explainable**: distinguish an indicator or heuristic from verified evidence, and document false-positive limitations.
4. Preserve the application's safety boundaries: no investment recommendations or guaranteed authenticity claims.
5. Submit focused pull requests with the reproduction steps, implementation notes, and tests you ran.

## Development
Follow the setup and test commands in [README.md](README.md). Validate the affected backend/API and frontend paths before submitting changes.

## Security
Please **do not** disclose vulnerabilities in a public issue. Follow [SECURITY.md](SECURITY.md) for private reporting guidance.

## Pull request checklist
- [ ] Test inputs are synthetic or public and redistribution-safe
- [ ] New behaviors have tests or a reproducible manual test plan
- [ ] Explanations include limitations and uncertainty
- [ ] No user data, API tokens, model weights with incompatible licensing, or large generated outputs are committed
