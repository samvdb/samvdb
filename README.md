# Sam Van der Borght

Platform engineer and architect from Belgium. I work freelance through [Silverfern](https://silverfern.be), currently as lead platform engineer for a European B2B distributor: more than 90 Go microservices on Kubernetes, serving customers in over 20 countries.

## What I work on

- **Delivery.** Shared GitLab CI templates build and version every service. The pipeline writes the image tag to a deployments repository, and ArgoCD rolls it out from Helm charts and Jsonnet. Production is a separate, explicit promotion.
- **Kubernetes.** Talos clusters with Cilium, plus MySQL group replication and PostgreSQL run by operators.
- **Observability.** Prometheus, Mimir, Loki, Grafana and Alertmanager. Alerts with hysteresis, runbooks behind them, and an external probe for what internal checks miss.
- **Security.** Secrets in Vault through External Secrets, short-lived tokens with refresh-token rotation.
- **AI in operations.** An LLM gateway with a key and budget per service, internal metrics exposed as tools for AI agents, and runbooks that state which fixes an agent may apply on its own.

Go is my main language. I started out in PHP and Java.

## Why this profile looks quiet

Client work lives in private, self-hosted repositories. The public repositories here are older side projects, mostly home automation (Loxone, Modbus, Yamaha MusicCast).

## Contact

- Website: [silverfern.be](https://silverfern.be)
- LinkedIn: [Sam Van der Borght](https://www.linkedin.com/in/sam-van-der-borght-61853a51/)
- Email: hello@silverfern.be
