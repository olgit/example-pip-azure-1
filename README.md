# Black Duck CoPilot pip/Azure Pipelines Example

[![Build Status](https://dev.azure.com/copilot0022/copilot/_apis/build/status/BlackDuckCoPilot.example-pip-azure)](https://dev.azure.com/copilot0022/copilot/_build/latest?definitionId=5) [![Black Duck Security Risk](https://copilot-valid.blackducksoftware.com/github/repos/BlackDuckCoPilot/example-pip-azure/branches/master/badge-risk.svg)](https://copilot-valid.blackducksoftware.com/github/repos/BlackDuckCoPilot/example-pip-azure/branches/master)

Shows a working setup for using Black Duck CoPilot to analyze the risk of project dependencies

## Azure Pipelines Setup

The `azure-pipelines.yml` file has been modified to upload the generated data to Black Duck CoPilot:

```yaml
- script: bash <(curl -s https://copilot-valid.blackducksoftware.com/ci/azure/scripts/upload)
```
