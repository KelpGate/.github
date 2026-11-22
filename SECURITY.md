# Security policy

This policy applies to every repository in the Kelpgate organization and to the hosted Kelpgate service.

## Reporting a vulnerability

Please do not open a public issue for a security problem.

Use GitHub's private reporting on the affected repository: open the repository, go to **Security**, then **Report a vulnerability**. This reaches the maintainers privately.

You can also email **security@kelpgate.cloud**. Please keep exploit details to what is needed to reproduce the issue, and do not attach live malware.

Include what you can:

- the repository and version (package, plugin or module version, and the runtime: Node.js, Python, PHP, WordPress or Drupal)
- steps to reproduce, or a proof of concept
- the impact you expect

## What to expect

| Step | Target |
| --- | --- |
| Acknowledgement | within 3 working days |
| First assessment | within 7 working days |
| Fix or mitigation for confirmed issues | depends on severity; we aim for 30 days for high severity |

We will tell you when a fix ships and, if you want, credit you in the release notes. We ask that you give us reasonable time to fix an issue before you publish details.

## Supported versions

We fix security issues in the latest release of each project. Older releases are not patched; upgrade to the current one.

## Scope

In scope: the client libraries for Node.js (`@kelpgate/client`), Python (`kelpgate-client`) and PHP (`kelpgate/client`), the WordPress plugin, the Drupal module, and all other code in this organization's repositories.

For the hosted Kelpgate service (API, console), report through the same private channel and mark the report as service-related.

Please do not run denial-of-service tests, test against other customers' data, or upload live malware to the service. The standard EICAR test string is fine.
