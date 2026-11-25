# Morph4D safe Windows diagnostics

This branch provides the implementation scaffold for read-only system diagnostics and bounded agent controls.

## Scope

- Read-only Windows hardware inventory
- GPU and Python environment status
- Optional HTTP health and diagnostics API
- Human approval for agent operations
- Audit event logging
- Explicit allowlist for executable operations
- No credential collection
- No privilege escalation
- No network scanning or exploitation
- No destructive or self-modifying actions

## Prohibited operations

The diagnostics integration must not add password extraction, process injection, persistence, bypasses, exploitation, credential stealing, malware staging, or unrestricted autonomous shell execution.
