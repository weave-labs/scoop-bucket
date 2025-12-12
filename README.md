# Weave Labs Scoop Bucket

This repository contains the [Scoop](https://scoop.sh/) bucket for Weave Labs tools.

## Prerequisites: Install Scoop

Install Scoop (PowerShell):

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

## Add This Bucket

To add this bucket to your Scoop installation:

```powershell
scoop bucket add weave-labs https://github.com/weave-labs/scoop-bucket
```

## Available Manifests

### Weave CLI (`weave-cli`, binary: `wv`)

CLI tool for generating API tests from OpenAPI specifications using LLMs.

```powershell
scoop install weave-labs/weave-cli
wv --help
```

## Update / Upgrade

- Refresh buckets: `scoop update`
- Upgrade tools from this bucket (example): `scoop update weave-labs/weave-cli`

- List buckets to confirm added: `scoop bucket list`

## License

The tools in this bucket are distributed under their respective licenses. See each tool's repository for details.
