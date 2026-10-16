## Node4

**Proxies on IP blocks we own.** Dedicated, shared and rotating datacenter proxies in the United States, Italy and Spain, plus residential proxies in 170+ countries. HTTP(S) and SOCKS5 on every paid plan, one login for every product, and a free tier with no card required.

| Product | Best for | Billed by |
|---|---|---|
| [Dedicated datacenter](https://node4.io/datacenter-proxies) | logins, whitelisted APIs, a fixed set of IPs | per proxy, no data cap |
| [Shared datacenter](https://node4.io/shared-proxies) | development, QA and light crawling on a budget | per proxy, pooled bandwidth |
| [Rotating Unmetered](https://node4.io/rotating-proxies) | scraping at volume on targets that accept datacenter IPs | concurrent connections, no data cap |
| [Rotating Datacenter](https://node4.io/rotating-proxies) | rotating exits at lower volume | per GB |
| [Residential](https://node4.io/residential-proxies) | targets that refuse datacenter ranges; country, state, city and ASN targeting | per GB |

### Quick start

```sh
curl -x "http://USER:PASS@gw-rotating_datacenter.node4.io:8083" https://api.ipify.org
```

Rotation is per connection: every new connection can leave from a different IP, and a session ID in the username holds one IP for up to 30 minutes.

### Links

[Pricing](https://node4.io/pricing) · [Setup guides](https://node4.io/help) · [REST API](https://node4.io/help/proxy-management-api) · [Status](https://node4.io/status) · [Free tools](https://node4.io/tools) · support@node4.io
