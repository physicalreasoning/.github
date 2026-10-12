# Security policy

This policy applies to every repository in the
[physicalreasoning](https://github.com/physicalreasoning) organization that does not have its
own `SECURITY.md`.

## Reporting a vulnerability

Please report security issues privately through GitHub's private vulnerability reporting:

1. Open the affected repository on GitHub.
2. Go to the **Security** tab and click **Report a vulnerability**.
3. Describe the issue, the affected code or service, and steps to reproduce.

Do not open a public issue, pull request, or discussion for a security problem.

Examples of what to report:

- A credential, token, or private key committed to a repository or its history.
- A vulnerability in a service we run, such as the isotherm API or MCP server.
- Code that could leak private data, execute untrusted input, or let a sealed forward-test entry
  be changed after its freeze without detection.

## What to expect

We are a small research collective, so responses are best effort. We aim to acknowledge a report
within a few days, keep you informed while we work on a fix, and credit you in the advisory if you
would like to be credited.

## Supported versions

Only the latest commit on each repository's default branch is supported. Results and frozen
entries from past rounds are published as records and are not patched.
