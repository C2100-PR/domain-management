# Domain Management

This repository manages Cloud Run configurations for multiple domains.

## Structure
- `/domains` - Contains domain configurations
- `/scripts` - Automation scripts for domain management
- `/configs` - Cloud Run configurations

## Domain Configuration Template
```yaml
domain:
  name: example.com
  cloudrun:
    service: my-service
    region: us-central1
  dns:
    type: CNAME
    value: ghs.googlehosted.com
    ttl: 600
```
