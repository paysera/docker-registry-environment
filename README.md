# docker-registry-environment

### Control
##### Start/restart environment
```bash
./scripts/launch.sh
```

### Config
##### Registry htpasswd
```bash
docker run --entrypoint htpasswd registry:2 -Bbn testuser testpassword >> registry/htpasswd
```
