# helmfile2compose

O traveler, you who have arrived at these gates — know that the path behind you remains open. You may still turn back. None shall judge the wise who flee.

**[Documentation](https://helmfile2compose.github.io/)** — for those who choose to proceed.

### The concept

An abomination. Convert Kubernetes manifests to `compose.yml` + `Caddyfile`. Not Kubernetes-in-Docker — no cluster, no kubelet, no shim. Plain `docker compose up`, plain Caddy, plain suffering.

Three components: **h2c-core** (*the mad scribe*) converts the manifests, **extensions** (*the damned*) extend it beyond built-in kinds — CRD providers, converters, transforms, tomorrow whatever Yog Sa'rath demands — and **h2c-manager** (*the dark priest*) downloads and orchestrates everything.

> *"Abandon all hope, yee who enter here"* — Semple (allegedly)

### Repositories

| Repo | Purpose |
|------|---------|
| [h2c-core](https://github.com/helmfile2compose/h2c-core) | The core converter. Patient zero. |
| [h2c-manager](https://github.com/helmfile2compose/h2c-manager) | Package manager + extension registry |
| [helmfile2compose.github.io](https://github.com/helmfile2compose/helmfile2compose.github.io) | Documentation site |
| [h2c-provider-keycloak](https://github.com/helmfile2compose/h2c-provider-keycloak) | Keycloak CRD provider |
| [h2c-converter-cert-manager](https://github.com/helmfile2compose/h2c-converter-cert-manager) | cert-manager CRD converter |
| [h2c-converter-trust-manager](https://github.com/helmfile2compose/h2c-converter-trust-manager) | trust-manager CRD converter |
| [h2c-provider-servicemonitor](https://github.com/helmfile2compose/h2c-provider-servicemonitor) | Prometheus & ServiceMonitor CRD provider |
| [h2c-transform-flatten-internal-urls](https://github.com/helmfile2compose/h2c-transform-flatten-internal-urls) | Transform: strip aliases, rewrite FQDNs to short names |
| [h2c-rewriter-nginx](https://github.com/helmfile2compose/h2c-rewriter-nginx) | Nginx ingress annotation rewriter |
| [h2c-rewriter-traefik](https://github.com/helmfile2compose/h2c-rewriter-traefik) | Traefik ingress annotation rewriter (POC) |
