# Security Policy

This repository is a community fork of [Altair GraphQL Client](https://github.com/altair-graphql/altair). It may contain fork-specific workflow, dependency, and maintenance changes. Please identify whether a report affects upstream Altair or only this fork.

## Supported versions

For upstream Altair, consult the upstream project's supported-version policy and security advisories. This fork does not promise a separate release cadence or security-support SLA. Fork-specific fixes are prioritized on the default branch.

## Reporting a vulnerability

**Please do not report vulnerabilities, credentials, exploit payloads, personal data, or unpatched security details in public pull requests, discussions, or issue trackers.**

- **Upstream Altair:** Report vulnerabilities affecting the upstream project through the [upstream Altair Security page](https://github.com/altair-graphql/altair/security), following its current private-reporting instructions.
- **Fork-specific changes:** Use GitHub's **Report a vulnerability** option on this fork's Security tab if private vulnerability reporting is enabled. If the option is unavailable, contact the fork maintainer through the [GitHub profile](https://github.com/prayaggaikwad96) and request a private disclosure route. Do not post exploit details publicly.

A useful report includes the affected commit or version, impacted file or workflow, security impact, safe reproduction steps, and a suggested mitigation when known. Avoid sending real credentials or private user data.

## Response expectations

Reports will be triaged as time and severity permit. This fork does not promise a fixed response-time or remediation SLA. Please allow reasonable time for assessment and coordinated disclosure.

## Secrets

Never commit API keys, tokens, signing credentials, private registry credentials, or other secrets. If a credential is exposed, revoke or rotate it immediately; removing it from a later commit does not invalidate it.
