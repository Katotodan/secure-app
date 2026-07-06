# Security Policy

## Vulnerability Reporting

Report security vulnerabilities to: security@example.com

## Security Scanning

This project uses automated security scanning:

- **Container Scanning**: Trivy (daily)
- **Dependency Scanning**: npm audit (on every commit)
- **Code Scanning**: CodeQL (weekly)
- **Secret Scanning**: Gitleaks (on every commit)

## Security Gates

### Deployment Blockers
- CRITICAL vulnerabilities: ❌ Block deployment
- HIGH vulnerabilities: ⚠️ Review required
- MEDIUM/LOW vulnerabilities: ✅ Track and fix

### Exceptions
- Document in security-exceptions.md
- Require security team approval
- Set expiration date

## Best Practices

1. Keep dependencies updated
2. Review security alerts weekly
3. Use dependabot for automated updates
4. Never commit secrets
5. Use security-focused base images

## Remediation SLAs

- CRITICAL: Fix within 24 hours
- HIGH: Fix within 7 days
- MEDIUM: Fix within 30 days
- LOW: Fix within 90 days

## Security Tools

- [Trivy](https://github.com/aquasecurity/trivy) - Container scanning
- [npm audit](https://docs.npmjs.com/cli/audit) - Dependency scanning
- [CodeQL](https://codeql.github.com/) - Code analysis
- [Gitleaks](https://github.com/gitleaks/gitleaks) - Secret detection
