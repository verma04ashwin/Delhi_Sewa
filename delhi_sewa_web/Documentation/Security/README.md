# Security

Security is a continuous engineering requirement for DelhiSewa Web.

## Principles

- Treat external input as untrusted.
- Validate input at trust boundaries.
- Enforce authorization server-side.
- Never expose secrets to client code.
- Never commit credentials.
- Prevent injection vulnerabilities.
- Prevent XSS.
- Use safe error responses.
- Avoid sensitive information in logs.
- Apply least privilege.
- Keep dependencies reviewed and updated.
- Apply appropriate security headers.
- Protect authentication and session mechanisms.
- Apply rate limiting where appropriate.
- Restrict and validate file uploads where applicable.

## Security Process

Security must be considered during:

1. Design
2. Implementation
3. Testing
4. Code review
5. Dependency auditing
6. Deployment
7. Monitoring
8. Periodic review

## Limitation

Zero vulnerabilities cannot be guaranteed.

The goal is a disciplined process that continuously reduces security risk.
