# hummbl-dev Federations

Lightweight index of public repository federations under the `hummbl-dev` account.

This repository contains documentation and manifests only. It has no application code and no GitHub Actions workflows (to conserve Actions minutes).

Federations are clusters of related, independently versioned public repositories. They improve discovery and coherence without requiring a monorepo.

## Agent Tooling

Focused tools for agent evaluation, contracts, memory, provenance, and configuration.

| Repository | Purpose |
|------------|---------|
| [agent-eval](https://github.com/hummbl-dev/agent-eval) | Lightweight evaluation harness for agent outputs, tool calls, and multi-turn traces |
| [agent-provenance](https://github.com/hummbl-dev/agent-provenance) | SLSA-compliant provenance attestation generator and git commit trailer signer for autonomous AI agents |
| [agent-lock](https://github.com/hummbl-dev/agent-lock) | Producer for hash-addressed agent configuration lockfiles (companion to acve) |
| [prompt-contract](https://github.com/hummbl-dev/prompt-contract) | Compile-time and runtime typecheckers, schema fuzzers, and contract tests for LLM prompts and tool calls |
| [sparse-context](https://github.com/hummbl-dev/sparse-context) | AST-level semantic context compressor for LLMs |
| [codemode-eval](https://github.com/hummbl-dev/codemode-eval) | Eval harness for sandboxed code-orchestration agents |
| [acve](https://github.com/hummbl-dev/acve) | Agentic Configuration Vulnerability Enumeration |

**Suggested topic:** `hummbl-agent-tooling`

## Governance Atoms

Small, independently usable reference implementations of governance primitives. Complementary to (not a replacement for) packages in `hummbl-io/oss`.

| Repository | Purpose |
|------------|---------|
| [governance-atoms](https://github.com/hummbl-dev/governance-atoms) | Reference implementations of core primitives (kill-switch, circuit-breaker, cost governor) |
| [tuple-lite](https://github.com/hummbl-dev/tuple-lite) | Minimal typed-tuple primitives and validators (contract, evidence, attest style). Stdlib-only |

**Suggested topic:** `hummbl-governance-atoms`

## Zero-dependency Utilities

Pure or near-pure stdlib tools that stay easy to copy or depend on lightly.

| Repository | Purpose |
|------------|---------|
| [bus-client](https://github.com/hummbl-dev/bus-client) | Stdlib Python client for an append-only TSV coordination log |
| [worktree-gc](https://github.com/hummbl-dev/worktree-gc) | Fail-closed git worktree garbage collector (stdlib Python) |
| [forge-sync](https://github.com/hummbl-dev/forge-sync) | Zero-dependency bidirectional git mirror and failover orchestrator |
| [model-tier-lint](https://github.com/hummbl-dev/model-tier-lint) | Validate and lint model-tier catalogs (MD/YAML) against a schema |

**Suggested topic:** `hummbl-stdlib`

## How to use this index

- Each member repository should include a short “Federation” section in its README that links back here and lists its siblings.
- Apply the suggested GitHub topic to member repositories for searchability.
- New public repositories that fit an existing federation should be added to the appropriate table above.
- This index itself stays free of CI and application code.

## Related

- Planning and conventions: [radix-sos-aoa-plans](https://github.com/hummbl-dev/radix-sos-aoa-plans) (private)
- Organization monorepo: [hummbl-io/oss](https://github.com/hummbl-io/oss)

## License

Apache-2.0
