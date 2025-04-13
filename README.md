# edge-cluster

## install via flux
```bash
flux bootstrap git \
  --url=ssh://git@github.com/seboknt/edge-cluster.git \
  --branch=main \
  --private-key-file=/root/.ssh/id_ed25519 \
  --path=clusters/edge
```