Dockerfiles for Day to Day development

- Elasticsearch + Kibana
- JupyterLab Minimal Notebook with Nodejs Kernel
- Mongodb
- Redis + Mods (Search, JSON, Graph, TimeSeries, Bloom, Gears, AI)
- Redis Cluster with modules support (HELM Chart image)
    - `helm repo add bitnami https://charts.bitnami.com/bitnami`
    - update `password` & `storage engine` in `Redis-Cluster/example-values.yaml`
    - `helm install redis bitnami/redis-cluster -f Redis-Cluster/example-values.yaml`
    - To create you own image update Dockerfile in `Redis-Cluster` directory and update image repository accordingly
- Influx DB
