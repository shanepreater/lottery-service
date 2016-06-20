# lottery-service
Microservice experiment using Kubernetes to standup a lottery analysis application.

This is an experiment in getting a full Microservice stack up and running using Kubernetes.

## Main parts

1. Ingest service - This is responsible for receiving lottery results and then transforming them into the internal model format.
2. Analysis service - Takes lottery results and performs analysis on them.
3. Query service - Provides the API for querying the analysed data
4. UI Service - Web UI to use the underlying apis.
