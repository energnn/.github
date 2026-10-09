# Security Policy

## Reporting a Vulnerability

The EnerGNN community takes security issues seriously.

If you believe you have discovered a security vulnerability in EnerGNN, please report it privately and responsibly.

Please do not disclose security vulnerabilities publicly until they have been assessed and addressed by the maintainers.

### Preferred Reporting Method

Please report vulnerabilities by contacting the maintainers through one of the following channels:

- Maintainers list : [COMMITTERS.csv](COMMITTERS.csv)
- LF Energy project contacts: balthazar.donon@rte-france.com

When reporting a vulnerability, please include:

- A description of the issue
- The affected version(s)
- Steps to reproduce
- Potential impact
- Any proposed mitigation or fix

We will acknowledge receipt of the report as soon as possible and work with you to understand and resolve the issue.

## Responsible Disclosure

We ask security researchers to:

- Give maintainers reasonable time to investigate and remediate issues.
- Avoid public disclosure before a fix or mitigation is available.
- Avoid accessing, modifying, or destroying data that does not belong to you.

## Supported Versions

EnerGNN is an evolving open source project.

Security fixes are generally provided for:

- The latest release
- The current development branch, when applicable

Older releases may not receive security updates.

## Incident Response

The project maintainers will:

1. Assess reported vulnerabilities.
2. Determine severity and impact.
3. Develop and validate a fix.
4. Coordinate disclosure with affected stakeholders.
5. Publish security advisories when appropriate.

## Cyber Resilience Act (CRA) Stewardship

This project is supported under the Linux Foundation CRA stewardship framework, as described at:

https://www.linuxfoundation.org/security

Security vulnerabilities should be reported through the mechanisms described above, which we will coordinate with our CRA steward.

For actively exploited vulnerabilities and severe incidents that may require CRA escalation, project maintainers should use the project's emergency security reporting mechanisms as appropriate.

## CRA Escalation

If project maintainers become aware of:

- An actively exploited vulnerability; or
- A severe security incident (for example, a compromise of the release process)

they should immediately notify:

steward@linuxfoundation.org

while simultaneously working to contain and remediate the issue.

## Security Best Practices for Contributors

Contributors are encouraged to:

- Keep dependencies up to date.
- Follow secure coding practices.
- Review third-party dependencies before introducing them.
- Avoid committing credentials, tokens, or secrets.
- Use reproducible and verifiable release processes whenever possible.

## Scope

EnerGNN is an LF Energy open source project developing graph neural network technologies and associated tooling for power system applications.

This policy applies to:

- The EnerGNN source code repositories
- Official releases
- CI/CD infrastructure managed by the project
- Project-maintained containers and packages