# Security

Report a vulnerability privately through the repository's **Security** tab, **Report a
vulnerability** (GitHub's private vulnerability reporting). Do not open a public issue.

Include the repository, the commit or image version, what an attacker gains, and the
steps to reproduce. You get an answer within seven days.

The threat model is
[docs/THREAT-MODEL.md](https://github.com/apex-linux/apex/blob/main/docs/THREAT-MODEL.md).
Images are signed with cosign; their keys and the RPM signing key never leave the
owner's machines.
