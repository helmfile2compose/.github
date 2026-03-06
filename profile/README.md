# dekube

**Convert Kubernetes manifests, Helm charts, and helmfiles to Docker Compose** — one source of truth, no second stack to maintain.

O traveler, you who have arrived at these gates — know that the path behind you remains open. You may still turn back. None shall judge the wise who flee.

**[Documentation](https://docs.dekube.io/)** — for those who choose to proceed.

### The concept

You deploy with Helm charts or helmfiles. Your users, your dev setup, or your NAS just need `docker compose up`. dekube generates `compose.yml` from your Kubernetes manifests — no second stack to maintain, just regrets.

Three components: **dekube-engine** (*the mad scribe*) converts the manifests, **extensions** (*the monks and the damned*) extend it beyond built-in kinds — CRD providers, converters, transforms, tomorrow whatever Yog Sa'rath demands — and **dekube-manager** (*the dark priest*) downloads and orchestrates everything.

> *"Abandon all hope, yee who enter here"* — Semple (allegedly)

### Repositories

| Repo | Purpose |
|------|---------|
| [dekube-engine](https://github.com/dekubeio/dekube-engine) | Bare conversion engine — empty registries, no opinions |
| [helmfile2compose](https://github.com/dekubeio/helmfile2compose) | The distribution — core + 8 monks. Patient zero. |
| [kubernetes2simple](https://github.com/dekubeio/kubernetes2simple) | Turnkey distribution — all extensions + bootstrap script |
| [dekube-manager](https://github.com/dekubeio/dekube-manager) | Package manager + extension registry |
| [dekube-docs](https://github.com/dekubeio/dekube-docs) | Documentation site |
| [dekube-testsuite](https://github.com/dekubeio/dekube-testsuite) | Regression & performance test suite |

### Get started

| Site | What it is |
|------|------------|
| [helmfile2compose.dekube.io](https://helmfile2compose.dekube.io) | Distribution docs — getting started, config, workarounds |
| [k2s.dekube.io](https://k2s.dekube.io) | One-command installer — `curl -fsSL k2s.dekube.io/get \| bash` |
| [docs.dekube.io](https://docs.dekube.io) | Engine docs — architecture, extensions, catalogue |

Monks, extensions, rewriters, transforms — see the **[extension catalogue](https://docs.dekube.io/catalogue/)**.
