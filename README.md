# Black Duck CoPilot pip/Azure Pipelines Example

Shows a working setup for using Black Duck CoPilot to analyze the risk of project dependencies

## Azure Pipelines Setup

The `azure-pipelines.yml` file has been modified to upload the generated data to Black Duck CoPilot:

```yaml
- script: bash <(curl -s https://copilot-valid.blackducksoftware.com/ci/azure/scripts/upload)
```
