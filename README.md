# gha-artifact-name

Output an artifact name for use across steps in a job.

This is a utility action created to ensure `ServerlessOpsIO/gha-setup-workspace` and `ServerlessOpsIO/gha-store-artifacts` generate the same artifact name by default. This action is intended to be used in a composite action and not directly in a workflow.

## Description

The `gha-artifact-name` action performs the following tasks:
1. Generates an artifact name based on the provided override or generates a default name.

## Inputs

- `artifact_name` (optional): Override the name of the artifact to use. Default is an empty string.

## Outputs

- `artifact_name`: The generated name of the artifact.

## Usage

for example usage see [ServerlessOps/gha-setup-workspace](https://github.com/ServerlessOpsIO/gha-setup-workspace/blob/main/action.yaml) or [ServerlessOps/gha-store-artifacts](https://github.com/ServerlessOpsIO/gha-store-artifacts/blob/main/action.yaml)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## Contact

For any questions or support, please open an issue in this repository.
