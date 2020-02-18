FROM grafana/grafana:5.2.1

COPY datasource-prometheus.yaml /etc/grafana/provisioning/datasources/
COPY dashboard-provider.yaml /etc/grafana/provisioning/dashboards/
COPY jvm-dashboard.json /var/lib/grafana/dashboards/