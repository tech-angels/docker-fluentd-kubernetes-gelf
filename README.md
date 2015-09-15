# Fluentd Log Collector For Kubernetes

This image reads logs from Docker containers hosted in
a Kubernetes cluster  and send them via the GELF protocol
to a central logging server.

Environment variables used by the image:

* `GELF_HOST` - the logging server address.
* `GELF_PORT` - the UDP port.

You can configure behaviour via the following environment
variables:


This image is an adaptation of fabric8io/docker-fluentd-kubernetes by Jimmi Dyson
which sends logs to Elasticsearch.
