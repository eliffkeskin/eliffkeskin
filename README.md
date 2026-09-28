# Hi, I'm Elif 👋

☸️ **DevOps & Platform & SRE Engineer** with five years of production Kubernetes (OpenShift, RKE2, EKS), operating identity and security infrastructure for banks and central banks. I work on the systems side: clusters, networking, GitOps, incident response, and lately the infrastructure that AI workloads run on. 🚀

## 🛠️ Selected work

🏗️ **[terraform](https://github.com/eliffkeskin/terraform)**  Hands-on Terraform labs on AWS, built from raw resources up: two-tier VPC with ALB and NAT, local modules, and an EKS Auto Mode cluster that scales from zero. Each project's README records what broke and why.

🔎 **[k8s-ops-mcp](https://github.com/eliffkeskin/k8s-ops-mcp)**  Kubernetes diagnostics exposed as MCP tools, with a minimal host that connects a fully local model (Ollama) to them. Read-only by design: the boundary is enforced with RBAC, not prompts.

⚙️ **[llm-serving-platform](https://github.com/eliffkeskin/llm-serving-platform)**  Self-hosted LLM inference on Kubernetes. KServe with a custom Ollama ServingRuntime (the stock Hugging Face runtime publishes no ARM64 image), deployed and reconciled through ArgoCD; nothing is applied by hand.

🧭 **[lodestar](https://github.com/eliffkeskin/lodestar)**  Documentation-grounded RAG support assistant with Langfuse tracing. Its evaluation layer pairs an LLM-as-judge with deterministic URL-grounding checks, written after a real production failure: a hallucinated API endpoint the deterministic check now catches automatically.

✨ Together these form one stack: infrastructure provisioned with Terraform, a platform operated through GitOps, an assistant evaluated on it, and agent tooling that inspects the cluster they all run on.

## 🌱 Currently

- Terraform: remote state and a GitHub Actions plan/apply pipeline for the lab repo
- Go: writing a Kubernetes operator with kubebuilder, to move from operating controllers to building them
- Preparing for AWS Solutions Architect Associate

## 🧰 Stack

Kubernetes (OpenShift, RKE2, EKS) · Terraform · AWS · Istio · ArgoCD · HashiCorp Vault · Keycloak · Kafka · Prometheus · Python · Go · KServe · MCP · Langfuse

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/eliffkeskin/)
