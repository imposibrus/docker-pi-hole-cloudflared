# Pi-hole with cloudflared for secure DNS

Pi-hole uses cloudflared to resolve all DNS-queries, so (almost) nobody can spy on you or hijack server response.

## Run

```bash
cp example.env .env
# fill .env file with your values
cp keepalived/keepalived.example.conf keepalived/keepalived.conf
# fill keepalived/keepalived.conf file with your values

docker-compose up -d
```

