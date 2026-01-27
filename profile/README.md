# BuildNinja

**Simple CI/CD for teams who'd rather ship code than configure pipelines.**

BuildNinja is a self-hosted CI/CD platform—a simpler alternative to Jenkins for mid-market engineering teams (10-50 engineers). Get enterprise-grade automation without enterprise complexity.

[![Website](https://img.shields.io/badge/Website-buildninja.grapehub.io-blue)](https://buildninja.grapehub.io)
[![Documentation](https://img.shields.io/badge/Docs-buildninja.grapehub.io%2Fdocs-green)](https://buildninja.grapehub.io/docs)
[![Docker Hub](https://img.shields.io/badge/Docker-grapehub%2Fbuildninja--server-blue?logo=docker)](https://hub.docker.com/r/grapehub/buildninja-server)

---

## Get Started in 5 Minutes

```bash
# Pull and run with Docker Compose
git clone https://github.com/BuildNinja-CICD/buildninja-docker-compose-examples.git
cd buildninja-docker-compose-examples/basic
docker-compose up -d
```

Open `http://localhost:8800` → Login with `root` / `root@123` → Create your first build.

---

## Repositories

| Repository | What it's for |
|------------|---------------|
| **[buildninja-quickstart](https://github.com/BuildNinja-CICD/buildninja-quickstart)** | 10 ready-to-use YAML configs for real projects (ripgrep, Lexical, Open WebUI) |
| **[buildninja-docker-compose-examples](https://github.com/BuildNinja-CICD/buildninja-docker-compose-examples)** | Docker Compose files for local and production deployments |
| **[buildninja-kubernetes-manifests](https://github.com/BuildNinja-CICD/buildninja-kubernetes-manifests)** | Kubernetes manifests with Kustomize overlays |
| **[buildninja-yaml-config-examples](https://github.com/BuildNinja-CICD/buildninja-yaml-config-examples)** | Template configs for Node.js, Python, .NET, Java, Go stacks |

---

## Why Teams Choose BuildNinja

| Pain Point | How BuildNinja Helps |
|------------|----------------------|
| Jenkins plugin conflicts | Single binary, no plugins to manage |
| Days of setup and config | Running in minutes with Docker |
| Dedicated DevOps required | Designed for teams with minimal DevOps resources |
| Unpredictable costs | Transparent pricing, free Solo tier forever |

---

## Key Features

- **Declarative YAML pipelines** — Export and reuse configs across projects
- **Cross-platform agents** — Windows, Linux, macOS
- **Built-in runners** — Command Line, MSBuild, VSTest, Config File
- **Git integration** — GitHub, GitLab, Bitbucket
- **SSO support** — Microsoft, GitHub, Google, GitLab, Bitbucket
- **Real-time logs** — Live build output with filtering and search
- **Artifact management** — Automatic collection and download

---

## Pricing

| Solo (Free Forever) | Shogun (Paid) |
|---------------------|---------------|
| Up to 10 users | Unlimited users |
| 100 projects | Unlimited projects |
| 3 concurrent agents | Unlimited concurrent agents |
| 30-day build history | Perpetual history |
| 1 SSO provider | All 5 SSO providers |

[Compare plans →](https://buildninja.grapehub.io/pricing)

---

## Resources

- [Documentation](https://buildninja.grapehub.io/docs) — Setup guides, configuration reference
- [buildninja-server](https://hub.docker.com/r/grapehub/buildninja-server) — Server Docker image
- [buildninja-agent](https://hub.docker.com/r/grapehub/buildninja-agent) — Agent Docker image

---

## Contact

- **Email:** [hello@grapehub.io](mailto:hello@grapehub.io)
- **Issues:** Open an issue in the relevant repository

---

*Built by [GrapeCity India](https://www.grapehub.io/about)*
