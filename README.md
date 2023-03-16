# Setup AppPack CLI GitHub Action

This action downloads the [AppPack](https://apppack.io) CLI from the [GitHub releases page](https://github.com/apppackio/apppack/releases).

## Inputs

### `version`

**Optional** Defaults to `latest`

## Outputs

### `version`

The version of the CLI that was setup

## Example usage

```yaml
- name: AppPack CLI
  uses: apppackio/setup-apppack-cli@v1
```
