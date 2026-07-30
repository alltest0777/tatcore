# Security Policy

The TatCoin team takes the security of the network, software, infrastructure, and users seriously.

We appreciate responsible reports from security researchers, developers, validators, and community members.

---

## Supported Versions

Security updates are currently provided for the latest published version of TatCoin.

| Version | Supported |
|---------|-----------|
| Latest release | Yes |
| Older releases | No |
| Development branches | Best effort |

Users, node operators, and validators should always run the latest stable release unless a specific network announcement states otherwise.

---

## Reporting a Vulnerability

Please do not report security vulnerabilities through public GitHub Issues, public discussions, social media, or community chats.

Instead, report the vulnerability privately by contacting the project maintainers.

Until a dedicated security email address is published, use GitHub's private vulnerability reporting feature for this repository, when available.

Repository:

```text
https://github.com/alltest0777/tatcore
```

When submitting a report, include as much of the following information as possible:

- A clear description of the vulnerability
- The affected TatCoin version or commit
- The affected component
- Steps to reproduce the issue
- Proof-of-concept code, logs, or screenshots
- The potential security impact
- Suggested mitigation, if known
- Whether the issue has been disclosed elsewhere

---

## Security Scope

Security reports may include issues affecting:

- Consensus
- Validator operation
- Transaction processing
- Signature verification
- Key management
- Account security
- Staking and governance
- State synchronization
- P2P networking
- RPC and REST interfaces
- Genesis and network configuration
- Build and release pipelines
- Dependencies
- Wallet integration
- Public infrastructure

---

## Out of Scope

The following are generally not considered security vulnerabilities:

- Issues that require physical access to a user's device
- Social engineering attacks
- Phishing websites not operated by TatCoin
- Vulnerabilities in unsupported or modified builds
- Denial-of-service reports without meaningful network impact
- Missing security headers on non-sensitive development services
- Reports generated only by automated scanners without verification
- Issues already publicly disclosed and fixed
- Problems caused by insecure third-party infrastructure

---

## Responsible Disclosure

Please allow the maintainers reasonable time to investigate and resolve a vulnerability before making it public.

Security researchers are expected to:

- Avoid accessing or modifying data that does not belong to them
- Avoid disrupting the TatCoin network
- Avoid extracting private keys, seed phrases, or confidential information
- Avoid testing against production infrastructure without permission
- Keep vulnerability details confidential until a fix is released

---

## Response Process

After receiving a valid report, maintainers will aim to:

1. Confirm receipt of the report.
2. Review and reproduce the issue.
3. Evaluate its severity and impact.
4. Develop and test a fix.
5. Prepare a security release or mitigation.
6. Coordinate responsible public disclosure.

Response times may vary depending on severity, complexity, and maintainer availability.

---

## Security Updates

Security fixes may be distributed through:

- GitHub Releases
- Repository security advisories
- Updated documentation
- Network announcements
- Validator upgrade instructions

Node operators and validators are responsible for monitoring official project channels and applying critical updates promptly.

---

## Private Keys and Seed Phrases

TatCoin maintainers will never ask users to provide:

- Seed phrases
- Private keys
- Wallet passwords
- Validator keys
- Authentication tokens

Never share these credentials with anyone.

---

## Dependency Security

TatCoin relies on third-party open-source software, including the Cosmos SDK, CometBFT, Go modules, and related tooling.

Security updates to dependencies will be reviewed and applied as appropriate.

---

## Safe Harbor

Security research conducted in good faith and in accordance with this policy will be treated as authorized research.

Researchers must make a reasonable effort to avoid:

- Privacy violations
- Data destruction
- Service interruption
- Financial loss
- Unauthorized access beyond what is necessary to demonstrate the issue

---

## Contact

A dedicated security contact will be added as the project grows.

For now, use GitHub private vulnerability reporting for the repository whenever available.

Thank you for helping keep TatCoin secure.
