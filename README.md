# Usage

## Lancement

```bash
docker-compose up
```

## Grafana

- Accès sur ```localhost:3000```.
- Créer une datasource Loki (```http://loki:3100```).
- Créer un dashboard Loki et sélectionner le job ```nginx``` pour visualiser les logs du serveur.