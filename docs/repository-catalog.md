# Hara repository catalog

This catalog is the organization-level orientation map for the ChatGPT Pro
GitHub connector. Project membership was read from the live Projects on
2026-08-24. Repository-local files remain authoritative for implementation.

## Hara Portfolio

Project: https://github.com/orgs/hara-lang/projects/1

| Repository | Responsibility | Connector entry | Validation authority |
| --- | --- | --- | --- |
| [`hara`](https://github.com/hara-lang/hara) | Language runtime and libraries | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-build`](https://github.com/hara-lang/hara-build) | Registry-backed specification management and conformance service for `build.hara-lang.org`; canonical specifications remain in `hara-specs-registry` | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-specs-registry`](https://github.com/hara-lang/hara-specs-registry) | Canonical specification registry | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-docs`](https://github.com/hara-lang/hara-docs) | Published language documentation | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-benchmarks`](https://github.com/hara-lang/hara-benchmarks) | Cross-runtime benchmark definitions and history | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-extensions`](https://github.com/hara-lang/hara-extensions) | Editor integrations | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-identity`](https://github.com/hara-lang/hara-identity) | Package signing identity and trust policy | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-cli`](https://github.com/hara-lang/hara-cli) | CLI distribution and installer endpoint | `README.md` | Needs repository-specific validation map |
| [`hara-status`](https://github.com/hara-lang/hara-status) | Build-health publication | `README.md` | Needs repository-specific validation map |
| [`homebrew-tap`](https://github.com/hara-lang/homebrew-tap) | Hara Homebrew formulas | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |

## Hara Community

Project: https://github.com/orgs/hara-lang/projects/2

| Repository | Responsibility | Connector entry | Validation authority |
| --- | --- | --- | --- |
| [`hara-ui`](https://github.com/hara-lang/hara-ui) | Shared UI components and editor theme | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-play`](https://github.com/hara-lang/hara-play) | Browser-first Hara Studio, project browser, and live kernel editor | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`visual-language`](https://github.com/hara-lang/visual-language) | Hara visual language and Astro primitives | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-learn`](https://github.com/hara-lang/hara-learn) | News, tutorials, and community resources for Hara Lisp | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-www`](https://github.com/hara-lang/hara-www) | Public Hara website | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |
| [`hara-packages`](https://github.com/hara-lang/hara-packages) | Reviewed package registry | `README.md`, `AGENTS.md` | Repository `AGENTS.md` |

## Repository names

The former `hara-specs`, `hara-playground`, and `hara-world` names are not live
repositories. Canonical entries above use `hara-specs-registry`, `hara-play`,
and `hara-learn`; no repository ownership is inferred for retired aliases.

## Selection rule

Choose the repository that owns the observable outcome. For cross-repository
work, keep one parent issue in the outcome-owning repository and create one
sub-issue and pull request per changed repository. Do not copy an issue into
multiple repositories.
