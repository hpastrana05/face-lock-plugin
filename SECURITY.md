# Security policy

## Reporting

Please report vulnerabilities privately through GitHub's **Report a
vulnerability** function rather than a public issue.

## Authentication safety

Face recognition is a convenience factor, not a substitute for a strong
password. This plugin keeps Omarchy's password PAM service unchanged and uses
a separate face-only service. Do not remove password authentication.

Review the AUR package and every setup-script change before running it. Omarchy
plugins and their QML execute unsandboxed inside the user's shell process.
