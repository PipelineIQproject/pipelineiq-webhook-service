# PipelineIQ Webhook Service

Independent repository staging folder for the PipelineIQ webhook service.

## Build

```bash
docker build -t nimeshsv814/pipelineiq-webhook-service:v1.0.0 -f services/webhook-service/Dockerfile .
```

## Run

This service expects PipelineIQ environment variables from Kubernetes ConfigMap and Key Vault secrets.
