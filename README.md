# alpine-unbound
That's an Alpine linux docker image with Unbound DNS preconfigured as forwarding DNS with aggressive caching (plus `serve-expired`) and forwarding to CloudFlare and Google Public DNSes.

There are no configurable environment variables - if you need to tweak, amend the unbound.conf file.
