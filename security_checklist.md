# Application Security Checklist

- Keep the application, plugins, themes, and server packages fully updated
- Enforce strong authentication and enable MFA for administrator accounts
- Remove default accounts, sample content, and unused modules
- Validate and sanitize all user input
- Use HTTPS with valid TLS configuration and secure cookies
- Restrict file upload types and verify uploads server-side
- Apply least-privilege permissions to files, folders, and database users
- Protect secrets and API keys outside the web root
- Enable logging, alerting, and regular backup verification
- Review admin panel exposure and brute-force protections

## Example Test
To test file upload security, I would attempt to upload different file types including allowed files, blocked extensions, renamed executable files, and oversized files. I would confirm the server rejects dangerous files, stores uploads safely, and prevents uploaded files from executing as code.
