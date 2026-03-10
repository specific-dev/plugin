---
name: specific-dev
description: Start the local development environment with all resources
---

# Start Local Development

Start the local development environment by running:

```bash
specific dev
```

This will:
- Start all services defined in `specific.hcl`
- Provision local databases and resources
- Set up an HTTP proxy for routing
- Watch for file changes and restart services automatically

Before starting:
1. Ensure `specific.hcl` exists and is valid by running `specific check`
2. Make sure the Specific CLI is installed (`specific --version`)
