@github Perform a security-focused code review on this pull request.
Look for:
- Injection risks (SQL, command, LDAP)
- XSS, CSRF, SSRF
- Unsafe deserialization
- Insecure API usage
- Unvalidated input or missing sanitization
- Hardcoded secrets
- Authentication/authorization issues
- Error-handling that leaks sensitive info

Provide examples and propose secure code fixes.