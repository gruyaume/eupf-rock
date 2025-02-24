# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:eupf_0.7.0_amd64.rock docker-daemon:eupf:0.7.0
docker run eupf:0.7.0
```
