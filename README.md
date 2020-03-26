# Helm Charts for SysFlow Kubernetes+S3 Deployment

To download the SysFlow yaml charts:
```
helm repo add my https://weii666.github.io/charts/

helm pull my/sf-exporter-chart --version 0.1-rc2
```

To deploy Sysflow agent which exports data to S3:
```
./installExporterChart
```
This script takes S3 confidential from environment variables.
