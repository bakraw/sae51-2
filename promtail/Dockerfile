FROM grafana/promtail:latest

EXPOSE 9080

COPY promtail-config.yaml /etc/promtail/config.yaml

CMD ["-config.file=/etc/promtail/config.yaml"]
