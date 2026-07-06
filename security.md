# Security Policy

MythosIDE reads and writes files directly on your local disk, so we take
security reports seriously — especially anything touching file handling,
the local indexing engine, or the update mechanism.

## Reporting a vulnerability

**Please do not open a public issue for security vulnerabilities.**

Instead, email **security@mythoside.com** with:

- A description of the vulnerability and its potential impact
- Steps to reproduce (a minimal example helps a lot)
- The version/commit you tested against
- Your platform (Windows / macOS / Linux) if relevant

We aim to acknowledge reports within a few business days. Once a fix is
available, we'll coordinate with you on disclosure timing and, if you'd like,
credit you in the release notes.

## Supported versions

While MythosIDE is in early development, only the latest released version is
supported with security fixes. This section will be updated with a formal
support table once we reach a stable 1.0 release.

## Scope

In scope:

- The MythosIDE desktop application (this repository)
- The local file-indexing engine and its handling of user files
- The auto-update mechanism

Out of scope:

- Third-party dependencies (please report upstream, though we'd appreciate a
  heads-up so we can track it)
- Issues that require physical access to an already-compromised machine
