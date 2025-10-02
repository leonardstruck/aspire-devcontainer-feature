
# .NET Aspire (dotnetaspire)

Installs Aspire. See https://aka.ms/dotnetaspire

## Example Usage

```json
"features": {
    "ghcr.io/leonardstruck/aspire-devcontainer-feature/dotnetaspire:1": {}
}
```

## Options

| Options Id | Description | Type | Default Value |
|-----|-----|-----|-----|
| version | Select or enter an Aspire version. Use 'latest' for the latest supported version, '9.3.1' for the 9.3.1 version, 'X.Y' or 'X.Y.Z' for a specific version, or 'latest-daily' for the latest unsupported build. | string | latest |
| installCli | Whether to install the Aspire CLI. | boolean | true |

## Customizations

### VS Code Extensions

- `ms-dotnettools.csdevkit`
- `ms-azuretools.vscode-bicep`
- `GitHub.copilot-chat`
- `GitHub.copilot`



---

_Note: This file was auto-generated from the [devcontainer-feature.json](https://github.com/leonardstruck/aspire-devcontainer-feature/blob/main/src/dotnetaspire/devcontainer-feature.json).  Add additional notes to a `NOTES.md`._
