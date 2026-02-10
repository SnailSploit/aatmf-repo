# Contributing to AATMF

Thank you for your interest in improving the Adversarial AI Threat Modeling Framework.

## How to Contribute

### New Techniques

1. Fork the repository
2. Add the technique to the appropriate tactic file in `docs/`
3. Include: description, AATMF-R v3 risk score, at least 2 attack procedures, detection pattern, mitigation
4. Use the namespaced ID format: `T{n}-AT-{next_sequence}`
5. Submit a pull request with evidence (paper, PoC, CVE reference)

### Detection Signatures

- YARA rules go in `signatures/yara/`
- Sigma rules go in `signatures/sigma/`
- Include tactic/technique references in metadata

### Case Studies

- Must involve responsibly disclosed vulnerabilities
- Include timeline, impact, IR lessons, and AATMF classification

### Cross-Framework Mappings

- Verify mappings against current versions of MITRE ATLAS, OWASP, NIST
- Include rationale for non-obvious mappings

## Code of Conduct

This is a defensive security framework. Contributions that exist solely to enable attacks without providing detection or mitigation guidance will not be accepted.

## Contact

- Kai Aizen ([@snailsploit](https://twitter.com/snailsploit))
- [snailsploit.com](https://snailsploit.com)
