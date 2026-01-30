# helm-pihole-k3s
A simple helm chart to deploy a pihole inside a k3s cluster. Can be used as an external DNS server.

## Pre-requesite
Uses traefik for it's ingress. Leave value piHoleHostname empty if not needed.

## Installation
Run command:
``` 
helm -n pihole install pihole . --create-namespace
```

## Upgrade
```
helm -n pihole upgrade pihole .
```