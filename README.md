# GitHub Actions Workflows

Example GitHub Actions workflows for DevOps CI/CD patterns. Six workflow files covering triggers, inputs, conditions, and concurrency.

## Files

| File | Concept |
|---|---|
| `01-hello-world.yaml` | Basic workflow structure: trigger, job, step |
| `02-triggers.yaml` | `on:` triggers: push, pull_request, schedule, workflow_dispatch |
| `03-inputs.yaml` | `inputs:` with `${{ github.event.inputs }}` |
| `04-context.yaml` | Context objects: `${{ github.sha }}`, `${{ runner.os }}` |
| `05-conditions.yaml` | `if:` conditions, `needs`, environment guards |
| `06-concurrency.yaml` | `concurrency:` to prevent parallel runs on same branch |

## Prerequisites

- GitHub repository with `actions` permission
- Secrets configured for AWS credentials (if deploying)

