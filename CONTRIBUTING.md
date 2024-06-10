# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:eupf_0.6.4_amd64.rock docker-daemon:eupf:0.6.4
docker run eupf:0.6.4
```
