# Demo

Environment variables and their scopes work as you'd expect in GitHub Actions.

They're also fairly self-contained, so any changes you make are isolated to the job you're in.

One thing that can cause confusion is the fact that environment variables defined within a step aren't accessible until the next step.

## Overview

- Read env vars
- Write env vars
- Pass env vars
- Modify PATH env var

## References

- [GitHub Docs: GitHub Actions](https://docs.github.com/en/actions)
- [GitHub Docs: Setting an environment variable](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/workflow-commands-for-github-actions#setting-an-environment-variable)
- [GitHub Docs: jobs.<job_id>.outputs](https://docs.github.com/en/actions/writing-workflows/workflow-syntax-for-github-actions#jobsjob_idoutputs)
- [GitHub Docs: Adding a system path](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/workflow-commands-for-github-actions#adding-a-system-path)
