# Uptime-Endpoint

## To deploy to docker

```bash
# Build container
docker buildx build --platform linux/amd64,linux/arm64 -t registry.rmnad.net/uptime-endpoint:latest --push .

# Then redeploy in portainer
```