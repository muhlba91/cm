# gitStream Configuration

[![Build status](https://img.shields.io/github/actions/workflow/status/muhlba91/cm/pipeline.yml?style=for-the-badge)](https://github.com/muhlba91/cm/actions/workflows/pipeline.yml)
[![License](https://img.shields.io/github/license/muhlba91/cm?style=for-the-badge)](LICENSE.md)
[![](https://api.scorecard.dev/projects/github.com/muhlba91/cm/badge?style=for-the-badge)](https://scorecard.dev/viewer/?uri=github.com/muhlba91/cm)

This repository contains the configuration for [gitStream](https://gitstream.cm).

---

## Configuration

Each `*.cm` file represents a named configuration for gitStream. The configuration file is a YAML file.

Filters are placed in the `plugins/filters` directory as per [gitStream documentation](https://docs.gitstream.cm/plugins/).

To run the configuration, `.github/workflows/gitstream.yml` is used.

### List of Configurations

- [`renovate_github_actions.cm`](renovate_github_actions.cm)
  - auto-approves and merges updtes to GitHub Actions workflows
- [`renovate_minor.cm`](renovate_minor.cm)
  - auto-approves and merges minor updates
  - excludes Kubernetes GitOps repositories
- [`renovate_patch.cm`](renovate_patch.cm)
  - auto-approves and merges patch updates
- [`repository_owner.cm`](repository_owner.cm)
  - auto-approves pull requests from the repository owner
