# Lightning Skills

A collection of [Claude Code](https://claude.ai/code) skills for Lightning Network development.

## What are skills?

Skills are reusable knowledge packages that extend Claude Code with domain-specific context, code patterns, and best practices. When a skill is installed, Claude automatically invokes it when your question matches its domain — no manual prompting required.

Each skill lives in its own directory and contains a `SKILL.md` file with metadata and reference content.

## Available skills

| Skill | Description |
|-------|-------------|
| [litd-grpc](./litd-grpc/) | litd gRPC API in Go: accounts, macaroons, payments, LNC sessions |
| [lnc-app](./lnc-app/) | Building a Lightning Node Connect web app using lnc-web |
| [lnd-navigate](./lnd-navigate/) | Navigating the lnd Go codebase |
| [taproot-assets-rpc](./taproot-assets-rpc/) | LND + Taproot Assets gRPC in Go |

## Installing a skill

1. Download or clone this repository.
2. In Claude Code, run:
   ```
   /skills install <path-to-skill-directory>
   ```
   For example:
   ```
   /skills install ./litd-grpc
   ```
3. The skill is now active in your Claude Code session.

For more details on skills, see the [official documentation](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills).
