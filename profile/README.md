# Protet: CI/CD runtime security designed for GitLab

Protet watches what your CI jobs do when they run: the processes they start, the connections they open and the DNS names they look up. It flags attacks in CI jobs, supply-chain compromises such as malicious npm packages among them.

- Self-hosted next to your GitLab runners on Kubernetes, built to run air-gapped.
- Evidence for DORA, NIS2 and FINMA reviews.
- **Protet Intel:** a public record of confirmed malicious npm package versions, with NDJSON, Atom and OSV feeds: [protet.io/intel](https://protet.io/intel). Look up a package at [protet.io/check](https://protet.io/check).

**Repositories**
- `monitor`: a preview GitHub Action. Not a protection yet.

Report a vulnerability: [protet.io/trust](https://protet.io/trust#disclosure) · Website: [protet.io](https://protet.io)
