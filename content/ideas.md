---
title: "Ideas"
date: 2023-06-02T09:00:43-07:00
draft: false
---

Here's a random, unsorted braindump of jumbled ideas for what I'd like this site to provide. I'm not necessarily advocating for any of these tools/sites/services (yet), just listing various things I'm aware of that could be useful.

## What compute/services to use?

* Raspberry Pi (and equivalents)
  * And slimmer hardware (old Android phones)
  * And beefier hardware (workstations, actual rack hardware)
  * Resources like [ServeTheHome](https://www.servethehome.com/)
* Compute providers (DigitalOcean, Hetzner, etc)
* Full cloud providers (AWS/GCP/Azure/Oracle/etc)
  * Should focus on free tiers, affordability, simplicity

Related question: How much compute does one need to run a bunch of services? Answer: usually not much.

## What applications to run?

* Lists like [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)
* My personal examples ([anylist](https://github.com/bcspragu/anylist), stronk (still need to open-source), etc)
* Ideas on how to figure out areas where software can help

## How to modify popular and/or small software for one's own use?

* Vetting open-source software
  * Star counts, forks, organization-backing, donors/supporters, recent activity, number of contributors, OSS vuln scanning, etc
* Making simple changes
  * Configuration changes, styling changes, using build tools, etc

## How to do security in-depth?

* Using infrastructure like [Tailscale](https://tailscale.com/)/[Headscale](https://github.com/juanfont/headscale/)
* Using platforms like [Sandstorm](https://sandstorm.io/)
* For hosting public applications from home, tradeoffs + how to tunnel traffic in?
  * E.g. with [Cloudflare Tunnels](https://www.cloudflare.com/products/tunnel/), proxies like [ngrok](https://ngrok.com/) + [frp](https://github.com/fatedier/frp), or directly with Tailscale
  * Dealing with firewalls
  * Understanding risks + ISP limitations
* Using tools like [Caddy](https://caddyserver.com/) for auto-HTTPS
