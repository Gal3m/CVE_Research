# CVE-2026-115563

**ClientCredentialsOAuthProvider leaks the pre-shared client_secret to an authorization server chosen by an untrusted MCP server.**

| Field | Value |
|---|---|
| CVE | [CVE-2026-115563](https://nvd.nist.gov/vuln/detail/CVE-2026-115563) |
| Severity | 🟠 High |
| Status | Assigned |
| Target library | python-sdk (MCP) |
| Target repo | https://github.com/modelcontextprotocol/python-sdk |

## Description

ClientCredentialsOAuthProvider leaks the pre-shared client_secret to an authorization server chosen by an untrusted MCP server.

## References
- **NVD** (official CVE description): https://nvd.nist.gov/vuln/detail/CVE-2026-115563
- MITRE CVE Record: https://www.cve.org/CVERecord?id=CVE-2026-115563
- OSV: https://osv.dev/vulnerability/CVE-2026-115563
- GitHub Advisory Database: https://github.com/advisories?query=CVE-2026-115563
- Affected project: https://github.com/modelcontextprotocol/python-sdk

> Reported under coordinated disclosure. Advisory-level summary only; no exploit code or proof-of-concept.
