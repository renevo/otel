# Open Telemetry Evaluations

Just playing around with open telemetry.

## Running Signoz

[Signoz](https://signoz.io/docs/install/docker) is an open telemetry stack.

```bash
git clone -b main https://github.com/SigNoz/signoz.git && cd signoz/deploy/
docker-compose -f docker/clickhouse-setup/docker-compose.yaml up -d
```

[Website](http://localhost:3301/)

Stop

```bash
docker-compose -f docker/clickhouse-setup/docker-compose.yaml down
```
