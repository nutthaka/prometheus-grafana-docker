Experiment setting up prometheus and grafana locally (using Docker)

## Environment Variables
Docker Compose expects BK_ORGANIZATION and BK_ACCESS_TOKEN

You could export those env before running the command
export BK_ACCESS_TOKEN="abc"
export BK_ORGANIZATION="org"

## Run
Create directory /prometheus_data

    docker-compose up

## References

https://finestructure.co/blog/2016/5/16/monitoring-with-prometheus-grafana-docker-part-1