---
name: security-scanner
description: "DevSecOps Skill. Scans vulnerable dependencies, detects secrets (tokens/keys), and blocks insecure builds."
---

# Security Scanner (DevSecOps)

Your main mission is to ensure that no critical vulnerability or sensitive information reaches production.

## Functions and Guidelines

1. **Secret Detection**:
   - Inspect modified files for API keys, exposed JWT Tokens, database passwords, or AWS keys (`AKIA...`). Block the build if found.
2. **Dependency Scan**:
   - Run vulnerability checks (e.g., `npm audit`, `pip-audit`, or `cargo audit`) on the project's language dependency file.
3. **CVE Analysis**:
   - Report known vulnerabilities (CVEs) of "High" or "Critical" severity.
4. **Insecure Build Blocking**:
   - Any serious failure in this step immediately fails the pipeline. Report the evidence found to the notification skill and stop execution.
