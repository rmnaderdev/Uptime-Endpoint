# Uptime-Endpoint

## To deploy to docker

```bash
# Build container
docker build -t registry.rmnad.net/uptime-endpoint:latest .

# Push to container registry
docker push registry.rmnad.net/uptime-endpoint:latest

# Then redeploy in portainer
```