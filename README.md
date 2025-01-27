# Ops Automation OpenTelemetry

This repository contains the necessary files for setting up an OpenTelemetry collector.

### Prerequisites

- Docker installed on your local machine (for testing).
- Set up a New Relic account with a license key and update the license key in the collector-config.yaml file under the exporter section of the OTLP.

## Running the app

```bash
# start docker (collector, jaeger, zipkin) in local
$ npm run docker:start

# stop docker
$ mpm run docker:stop
```
