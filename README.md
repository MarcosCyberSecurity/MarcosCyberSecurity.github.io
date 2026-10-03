# marcoscybersecurity.github.io

Personal cybersecurity portfolio — static site hosted on GitHub Pages.

## Security

- HTTPS enforced (automatic on github.io)
- Content Security Policy via `<meta>` tag
- Vulnerability disclosure: see [`.well-known/security.txt`](.well-known/security.txt) (RFC 9116)
- External API calls restricted to the CIRCL CVE feed via CSP `connect-src`

To report a security issue, please use the contact listed in `security.txt`.
