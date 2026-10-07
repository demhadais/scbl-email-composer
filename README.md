# scbl-email-composer
A tiny web app that creates a templated data-delivery email for use by the SCBL at The Jackson Laboratory.

## Deploy

```bash
cp .env.example .env   
# set TLS_CERTIFICATE_PATH and TLS_KEY_PATH to the host's cert
docker compose -f compose.yaml -f compose.prod.yaml up -d
```
