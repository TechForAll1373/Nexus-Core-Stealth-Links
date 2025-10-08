# Security Policy

## Overview

**Nexus Core – Stealth Links** is a 100% static, client-side HTML application. It contains:
- No backend
- No user input fields
- No data collection
- No external scripts
- No cookies or tracking

All links are opened via `window.open(url, "_blank")` in the user's browser.

## Security Guarantees

- ✅ **No XSS**: Content is hardcoded; no dynamic HTML insertion.
- ✅ **No data leakage**: Nothing is sent to any server.
- ✅ **No dependencies**: Entire app in one file.
- ✅ **HTTPS only**: Served via GitHub Pages over TLS.

## Reporting Issues

If you find a genuine security vulnerability:
1. Do **not** disclose publicly.
2. Email: `security@cafepersians.io`
3. Include:
   - Description
   - Steps to reproduce
   - Browser/OS
   - Suggested fix (optional)

We respond within 72 hours.

## External Links

This portal links to third-party services. Once you leave, you are subject to their policies. We do not control or monitor external destinations.
