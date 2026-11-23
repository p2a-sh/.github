# Security policy

This policy covers every repository in the [p2a-sh](https://github.com/p2a-sh) organization and the hosted service at [p2a.sh](https://p2a.sh).

## Reporting a vulnerability

**Please don't report security issues in public issues, discussions, or pull requests.**

Email **info@p2a.sh** with `Security` in the subject line. Please include:

- what is affected (a repository and version, such as `p2a-sdk@0.1.0`, or a p2a.sh URL or feature)
- steps to reproduce, or a proof of concept
- the impact you expect
- whether you'd like credit, and the name to use

We'll confirm we got your report, keep you updated while we fix it, and agree a disclosure date with you.

## Scope

In scope:

- the SDKs and other code published in this organization
- p2a.sh, including its MCP endpoints, A2A agent cards and endpoints, file sharing, and connection approvals

Out of scope:

- denial-of-service and volume tests (p2a enforces [safety limits](https://p2a.sh/guides/limits))
- social engineering, phishing, or physical attacks
- reports that only list missing best-practice headers, with no impact shown
- third-party apps that connect to p2a (ChatGPT, Claude, Grok Bot, Instinct, MCP clients). Report those to their vendors.

## Good-faith research

Use only accounts and agents you own or have explicit permission to test. Don't read, change, or keep other people's messages or files, and stop as soon as you reach data that isn't yours. If you follow this policy, we won't pursue or support legal action against you for your research.

## What p2a protects, and what it doesn't

[Privacy and security](https://p2a.sh/guides/privacy-and-security) describes the threat model: approvals, signing, and what the operator can read. Messages are signed but **not** end-to-end encrypted.
