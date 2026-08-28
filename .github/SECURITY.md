# Security Policy

The security of this project is taken seriously. We appreciate your efforts to
responsibly disclose any findings and will make every effort to acknowledge
your contributions.

## Supported Versions

Security updates are provided only for the latest released version of this
app. Users are strongly encouraged to keep their installations up to date.

| Version        | Supported          |
| -------------- | ------------------ |
| Latest release | :white_check_mark: |
| Older releases | :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues,
discussions, or pull requests.**

Instead, report them privately through GitHub's private vulnerability
reporting:

[**Report a vulnerability**](https://github.com/hassio-addons/app-whisparr/security/advisories/new)

If for any reason you are unable to use GitHub's private vulnerability
reporting, you may also reach out to the maintainer by email at
[opensource@frenck.dev](mailto:opensource@frenck.dev).

When reporting, please include as much of the following as possible:

- A clear description of the vulnerability and its potential impact.
- Steps to reproduce, or a proof of concept.
- Affected version(s) of the app.
- Any known mitigations or workarounds.

## Disclosure Timeline

- **Acknowledgement:** you will receive an acknowledgement of your report
  within **48 hours**.
- **Initial assessment:** a triage and initial severity assessment will be
  shared within **7 days** of the acknowledgement.
- **Fix and disclosure:** valid reports are targeted for resolution and
  coordinated public disclosure within **90 days** of the initial report,
  depending on complexity and impact.

You will be kept informed throughout the process and credited in the release
notes for the fix, unless you prefer to remain anonymous.

## Out of Scope

The following are **not** considered security vulnerabilities in this project:

- Vulnerabilities in upstream or transitive dependencies. These are handled
  continuously by [Renovate](https://github.com/renovatebot/renovate) and
  addressed through regular dependency updates.
- Issues in the Whisparr application itself; please report those directly to
  the [Whisparr project](https://github.com/Whisparr/Whisparr).
- Issues in the Home Assistant Supervisor or the underlying base image; please
  report those to the [Home Assistant](https://github.com/home-assistant) and
  [app base](https://github.com/hassio-addons/app-base) projects respectively.
- Exposure of the Whisparr web interface caused by the user publishing the
  configured port to an untrusted network. This app assumes the network it is
  exposed on is trusted.

## Scope

This security policy covers the Whisparr app published from this repository,
and its source code.
