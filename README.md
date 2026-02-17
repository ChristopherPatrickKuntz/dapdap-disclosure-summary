# DapDap -- Responsible Disclosure Record

## Advisory ID: CPK-2026-004

**Target:** [DapDap](https://dapdap.net) -- Multi-chain DeFi Aggregator
**Severity:** Critical
**Status:** Disclosed -- Awaiting Vendor Response
**Disclosure Date:** 2026-02-17

---

## Summary

A critical security vulnerability was identified in DapDap's production web application and associated infrastructure during a passive (non-intrusive) external security assessment conducted by CPK Solutions. The vulnerability involves exposed sensitive material accessible without authentication, with potential implications for application security and third-party service integrations.

The finding was reported to the DapDap team via their published contacts on the date listed above.

## Disclosure Details

| Field | Value |
|-------|-------|
| **Advisory ID** | CPK-2026-004 |
| **CWE** | CWE-215, CWE-798, CWE-942 |
| **Discovery Method** | Automated scan (CPK Scanner) + Manual verification |
| **Affected Components** | Production web application and associated infrastructure |
| **Reported To** | DapDap team |
| **Disclosure Deadline** | 2026-05-18 (90 days) |

## What Is NOT Disclosed Here

In accordance with responsible disclosure best practices, the specific technical details of the vulnerability -- including affected code, service identifiers, and proof-of-concept -- are **withheld from this public record** until:

1. The vendor has remediated the vulnerabilities, **or**
2. The 90-day disclosure deadline has passed

This follows industry standard practice consistent with [Google Project Zero](https://googleprojectzero.blogspot.com/p/vulnerability-disclosure-faq.html), [CERT/CC](https://vuls.cert.org/confluence/display/Wiki/Vulnerability+Disclosure+Policy), and [Trail of Bits](https://blog.trailofbits.com/2024/04/15/5-reasons-to-strive-for-better-disclosure-processes/) disclosure policies.

## Timeline

| Date | Event |
|------|-------|
| 2026-02-17 | Vulnerabilities discovered and verified |
| 2026-02-17 | Advisory submitted to DapDap team |
| 2026-05-18 | Disclosure deadline (90 days) |
| -- | *Updates will be posted here as the disclosure progresses* |

## About CPK Solutions

CPK Solutions performs automated and manual security assessments of Web3 applications, smart contracts, and DeFi protocols. Findings are reported responsibly following the [disclose.io](https://disclose.io/) Core Terms framework.

All assessments referenced in this record were conducted passively using only publicly available data. No private systems were accessed, no credentials were tested beyond a single read-only RPC liveness check, no funds were moved, and no automated exploitation was performed.

**Contact:** christopher@cpk.solutions

---

*This record exists solely to establish a timestamped public record of responsible disclosure. Full technical details will be published after the disclosure deadline or vendor remediation, whichever comes first.*
