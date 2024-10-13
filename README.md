[![Check and Publish Helm Charts](https://github.com/ez4-dev/helm-chart-publisher/actions/workflows/weekly-scanner.yaml/badge.svg)](https://github.com/ez4-dev/helm-chart-publisher/actions/workflows/weekly-scanner.yaml)

# Helm Chart Publisher
This publisher attempts to scan and release valuable Helm charts that have not yet been made available on any recognized public registries.

**DISCLAIMER**: This content is intended for personal use. Should you encounter anything that causes discomfort or dissatisfaction, please do not hesitate to raise an issue. I assure you that I will address it earnestly.

## The registry

All these charts will be distributed to [Docker Hub](https://hub.docker.com/u/ez4devcharts) in OCI format. Your usage can be as simple as:

```yaml
dependencies:
  - name: <chart_name>
    version: <chart_version>
    repository: oci://registry-1.docker.io/ez4devcharts
```

## Contribution

Your PRs are welcome. Feel free to add your repository or help me enhance the workflow.

## TODO

- [ ] Support build from branch
- [ ] Support latest tag
- [ ] PR validator
