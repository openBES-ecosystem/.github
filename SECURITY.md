# Security Policy

## Supported Versions

Security updates are provided for the following versions of projects in the openBES-ecosystem. Please check individual repository documentation for specific version support details.

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| < Latest| :x:                |

Generally, we recommend using the latest stable release to ensure you have the most recent security patches.

## Reporting a Vulnerability

The openBES-ecosystem takes security issues seriously. We appreciate your efforts to responsibly disclose your findings.

### How to Report

If you discover a security vulnerability, please follow these steps:

1. **Do NOT** open a public GitHub issue
2. **Do NOT** discuss the vulnerability publicly until it has been addressed

3. **Report via GitHub Security Advisory**:
   - Navigate to the specific repository
   - Go to the "Security" tab
   - Click "Report a vulnerability"
   - Fill out the private vulnerability report form

4. **Alternatively**, if the repository doesn't have Security Advisories enabled:
   - Contact the repository maintainers directly through GitHub
   - Use the subject line: `[SECURITY] Description of vulnerability`

### What to Include

Please provide the following information:

- **Description**: Clear description of the vulnerability
- **Impact**: Potential impact and severity assessment
- **Reproduction Steps**: Detailed steps to reproduce the issue
- **Affected Versions**: Which versions are affected
- **Proof of Concept**: Code, configuration, or input that demonstrates the issue
- **Suggested Fix**: If you have a proposed solution (optional)
- **Environment**: Relevant system and software version details

### What to Expect

- **Acknowledgment**: We will acknowledge receipt within 48-72 hours
- **Assessment**: We will assess the vulnerability and determine severity
- **Updates**: We will keep you informed of our progress
- **Resolution**: We will work to resolve the issue promptly
- **Credit**: We will credit you in the security advisory (if desired)

### Timeline

- **Initial Response**: Within 48-72 hours
- **Status Update**: Within 7 days
- **Fix Timeline**: Varies by severity
  - Critical: Immediate action, fix within days
  - High: Within 1-2 weeks
  - Medium: Within 4 weeks
  - Low: Next scheduled release

## Security Best Practices

When using openBES-ecosystem tools:

### For Researchers and Users

- **Keep Updated**: Use the latest stable versions
- **Validate Input**: Always validate and sanitize input data
- **Review Dependencies**: Check dependencies for known vulnerabilities
- **Secure Configuration**: Follow security guidelines in documentation
- **Access Control**: Limit access to sensitive simulation data
- **Data Privacy**: Handle building data responsibly
- **Backups**: Maintain regular backups of important data

### For Contributors

- **Code Review**: All code should be reviewed before merging
- **Dependencies**: Minimize and audit external dependencies
- **Input Validation**: Validate all user inputs
- **Error Handling**: Don't expose sensitive information in error messages
- **Secrets**: Never commit credentials or API keys
- **Testing**: Include security test cases
- **Documentation**: Document security considerations

## Common Vulnerability Areas

Be especially vigilant about:

- **Input Validation**: Simulation parameters, file uploads, API inputs
- **File Operations**: Reading/writing building models and results
- **Dependency Security**: Third-party libraries and packages
- **Data Serialization**: Parsing XML, JSON, CSV, or other data formats
- **API Security**: Authentication, authorization, rate limiting
- **Path Traversal**: File system access controls
- **Injection Attacks**: SQL, command, or code injection

## Security Updates

Security updates will be:

- Published as GitHub Security Advisories
- Included in release notes with "SECURITY" prefix
- Announced through repository releases
- Tagged with severity level (Critical, High, Medium, Low)

## Scope

This security policy applies to:

- All repositories under the openBES-ecosystem organization
- Official releases and stable branches
- Supported versions as documented

This policy does NOT cover:

- Third-party dependencies (report to their maintainers)
- Forked repositories outside the organization
- Unsupported or deprecated versions
- Issues in user configurations (but we're happy to help!)

## Disclosure Policy

- **Coordinated Disclosure**: We follow responsible disclosure practices
- **Embargo Period**: We request a 90-day embargo for critical vulnerabilities
- **Public Disclosure**: After a fix is released, we will publish a security advisory
- **CVE Assignment**: We will request CVEs for significant vulnerabilities

## Security Tools

We encourage the use of:

- **Dependency Scanning**: Tools like Dependabot, Snyk, or OWASP Dependency-Check
- **Static Analysis**: Code quality and security analysis tools
- **Container Scanning**: For Docker images (if applicable)
- **Fuzzing**: For finding edge cases and unexpected behavior

## Contact

For security concerns that don't fit the above process, or for questions about this policy:

- Open a GitHub Discussion in the relevant repository (for general security questions)
- Contact repository maintainers through GitHub

## Recognition

We appreciate security researchers who:

- Follow responsible disclosure practices
- Provide detailed vulnerability reports
- Give us time to fix issues before public disclosure
- Work cooperatively with us

Security contributors will be:

- Credited in security advisories (unless you prefer to remain anonymous)
- Acknowledged in release notes
- Thanked in project documentation

## Compliance

Projects in the openBES-ecosystem strive to follow:

- OWASP security best practices
- Common Weakness Enumeration (CWE) guidelines
- Secure development lifecycle principles
- Open source security standards

Thank you for helping keep the openBES-ecosystem secure! 🔒
