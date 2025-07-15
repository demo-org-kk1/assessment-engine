# Organization-wide Security Policy

Welcome to the `demo-org-kk1` security policy. Security is a top priority for our organization. Please read and follow these guidelines in all repositories.

---

## Reporting Security Issues

If you discover a security vulnerability, please report it responsibly:

- **Email:** security@demo-org-kk1.com
- **GitHub:** Open a [security advisory](https://github.com/demo-org-kk1/.github/security/advisories/new)
- Do **not** publicly disclose vulnerabilities until we have addressed them.

---

## Security Best Practices

All contributors and maintainers must follow these rules:

- **Default Branch Protection:**  
  The default branch (usually `main` or `master`) must be protected.  
  - Require pull request reviews before merging.
  - Require status checks to pass before merging.
  - Do not allow force pushes or deletions of the default branch.

- **No Secrets in Code:**  
  Never commit secrets (API keys, passwords, tokens, credentials) to any repository.  
  - Use environment variables or secret management tools.
  - If a secret is accidentally committed, rotate it immediately and notify the security team.

- **Dependency Management:**  
  Keep dependencies up to date and avoid using deprecated or unmaintained packages.

- **Multi-Factor Authentication:**  
  All organization members must enable 2FA on their GitHub accounts.

- **Security Reviews:**  
  All significant changes must undergo security review as part of the pull request process.

---

## Automated Enforcement

We use [Allstar](https://github.com/ossf/allstar) to automatically enforce many of these policies, including:
- Branch protection rules
- Secret scanning
- Required reviews and status checks

If you have questions about automated enforcement, contact the security team.

---

## Our Commitment

- We will investigate all reported vulnerabilities promptly.
- We will keep reporters informed of progress and resolution.
- We will credit responsible disclosure in our release notes (if desired).

---

Thank you for helping keep `demo-org-kk1` secure!
