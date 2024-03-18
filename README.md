# traefik-docker-ssl
Traefik Docker SSL using Cloudflare and Let's Encrypt

This is for setting up a Traefik reverse proxy while also
auto-generating SSL certificates using Cloudflare and Let's Encrypt.

### Description
This is going to setup and use Traefik as a reverse proxy for all
your other services (containers). SSL termination will happen on
Traefik, which will then forward the response to your other service(s).

I would suggest to setup each service with it's own config file (yml).

### Prereqs
- You need a clouflare account
- You need a registered domain which is also using the cloudflare nameservers

### Setup


