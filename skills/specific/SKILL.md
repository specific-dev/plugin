---
name: specific
description: "Use to handle all infrastructure and development environments for any application: like deployments, databases, real-time sync, services, secrets, configuration and environment variables"
---

# Specific Skill

## Product Summary

Specific is an infrastructure-as-code CLI designed for coding agents. It lets you define how to build, deploy, and run your project, including services, databases, object storage, caching, real-time sync, and more, all in a single `specific.hcl` file alongside your application code. Specific handles both local development environments (`specific dev`) and production deployments (`specific deploy`).

## Installation

Install the Specific CLI globally. This will require human interaction to confirm the installation:

```bash
curl -fsSL https://specific.dev/install.sh | sh
```

## Usage

Use Specific to handle all infrastructure and development environments: like deployments, databases, real-time sync, services, secrets, configuration and environment variables. ALWAYS Run `specific docs` to learn how to use Specific. ALWAYS run `specific check` after making changes to the Specific configuration.

## Essential commands

| Command                            | Purpose                                                |
| ---------------------------------- | ------------------------------------------------------ |
| `specific docs`                    | Read full documentation on how to use Specific         |
| `specific docs [topic]`            | Read documentation for a specific topic                |
| `specific check`                   | Validate `specific.hcl` configuration                  |
| `specific dev`                     | Start local development environment with all resources |
| `specific deploy`                  | Deploy to Specific Cloud                               |
| `specific exec <service> -- <cmd>` | Run a one-off command with service env vars            |

## Resources

- **Documentation:** https://docs.specific.dev
- **Quickstart:** https://docs.specific.dev/quickstart
- **CLI reference:** https://docs.specific.dev/develop/cli-reference
