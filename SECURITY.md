# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| latest (main) | ✅ |

## Scope

SimCivic Web is a static informational landing page with no user accounts, no backend, no database, and no data collection. The attack surface is intentionally minimal.

## Reporting a Vulnerability

If you discover a security issue (e.g. a malicious dependency introduced via a CDN, a reflected XSS vector, or a sensitive credential accidentally committed), please **do not open a public issue**.

Instead, email: **tr16cnguyen@gmail.com**

Include:
- A description of the vulnerability
- Steps to reproduce
- Potential impact

You can expect an acknowledgement within **72 hours** and a resolution or status update within **7 days**.

## Security Considerations

- This project loads fonts from Google Fonts (external CDN). No other third-party scripts are loaded.
- No user data is collected or stored.
- No cookies are set.
- The "Open Dashboard" link points to a separate repository (`SimCivic`) — review that repo's security policy independently.
