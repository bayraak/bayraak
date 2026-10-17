# Bayram Ali Basgul

Product engineer in Skopje. I build things where the guarantee is enforced by code or tooling, not by an instruction someone has to remember: the model chooses, code computes.

## Public work

- **[sagaflow](https://github.com/bayraak/sagaflow)** ([npm](https://www.npmjs.com/package/sagaflow-js)): an embedded saga engine for TypeScript with zero dependencies. Workflows undo themselves, leave a record and announce themselves once. A TLA+ model of it found five defects, each documented with what closed it.
- **[load-planner-mcp](https://github.com/bayraak/load-planner-mcp)**: an OR-Tools CP-SAT solver behind an MCP server. The explain tool takes one opaque id, so the model can narrate a result but cannot originate a number, and a verifier rejects any figure the solver did not produce.
- **[biological-ui-arch](https://github.com/bayraak/biological-ui-arch)** ([npm](https://www.npmjs.com/package/eslint-plugin-biological-ui-arch)): 35 lint rules that enforce a tiered UI architecture at the linter, where it cannot be skipped.
- **[verify-arch](https://github.com/bayraak/verify-arch)** ([npm](https://www.npmjs.com/package/verify-arch)): a whole-graph gate for Medusa 2.x that catches the cross-file mistakes a per-file linter cannot see, such as modules that silently overwrite each other.
- **[2ndm1nd-runtime](https://github.com/bayraak/2ndm1nd-runtime)**: a local-first capture app and daily consolidation job for a personal vault on macOS. There is no model in the capture path, by architecture.

Also published: [playwright-visual-diff-manifest](https://github.com/bayraak/playwright-visual-diff-manifest), a manifest-driven visual regression harness, and [geonosis](https://www.npmjs.com/package/geonosis), an agent-engineering toolchain (npm only; its source is private).

## Upstream

- npm-check-updates: [#1662](https://github.com/raineorshine/npm-check-updates/pull/1662), merged.
- void: [#440](https://github.com/voidzero-dev/void/pull/440), merged.
- Cloudflare docs: [#34386](https://github.com/cloudflare/cloudflare-docs/pull/34386), open, with a [minimal reproduction](https://github.com/bayraak/workflows-local-rollback-status-repro).

[bayramali.basgul.com](https://bayramali.basgul.com)
