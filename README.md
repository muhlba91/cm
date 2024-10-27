# gitStream Configuration

[![Build status](https://img.shields.io/github/actions/workflow/status/muhlba91/cm/pipeline.yml?style=for-the-badge)](https://github.com/muhlba91/cm/actions/workflows/pipeline.yml)
[![License](https://img.shields.io/github/license/muhlba91/cm?style=for-the-badge)](LICENSE.md)

This repository contains the configuration for [gitStream](https://gitstream.cm).

---

## Configuration

Each `*.cm` file represents a named configuration for gitStream. The configuration file is a YAML file.

Filters are placed in the `plugins/filters` directory as per [gitStream documentation](https://docs.gitstream.cm/plugins/).

To run the configuration, `.github/workflows/gitstream.yml` is used.

### List of Configurations

- [`renovate.cm`](renovate.cm): auto-approves and merges minor and patch updates
