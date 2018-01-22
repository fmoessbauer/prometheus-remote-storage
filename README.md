# Remote Storage Adapter for Prometheus

This docker container provides a build of the [prometheus
remote storage adapter](https://github.com/prometheus/prometheus/tree/master/documentation/examples/remote_storage/remote_storage_adapter).

To keep the container as small as possible, the adapter is pre-compiled.

# Running

We recommend to run the container in a prometheus docker-stack.
Just add it to your docker-compose file and adjust the run-command.
