# Source

Vendored, unmodified, from https://github.com/cloudflare/security-audit-skill
(commit c1c8a8c1471069fb0e188eeaff69b8e8db6564a8, 14 Sep 2026), MIT licence (see LICENSE).
The same copy is in every HANZALA repository; copy this folder into every new project.

To update: copy `skills/security-audit/` from a newer commit of that repository and change the commit above.

Use: ask Claude Code "security audit this codebase". The skill writes results outside the
repository (default `~/security-audit-skill/<repo>/run-N`). Never publish findings for a
public repository; report them privately.
