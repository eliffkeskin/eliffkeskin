# Hi, I'm Elif 👋

☸️ **DevOps & Platform Engineer** with five years of production Kubernetes:OpenShift, RKE2, EKS operating identity and security infrastructure used by financial institutions. These days I'm extending that foundation into **LLM infrastructure**: model serving, evaluation, and agent tooling. 🚀

## 🛠️ Selected work

🧭 **[lodestar](https://github.com/eliffkeskin/lodestar)** Documentation-grounded RAG support assistant, instrumented with Langfuse tracing. Its evaluation layer combines an LLM-as-judge with deterministic URL-grounding checks, and was built around a real production failure: a hallucinated API endpoint that the deterministic check now catches automatically.

⚙️ **[llm-serving-platform](https://github.com/eliffkeskin/llm-serving-platform)**  Self-hosted LLM inference on Kubernetes. KServe with a custom Ollama ServingRuntime, written because the stock Hugging Face runtime publishes no ARM64 image. Deployed and reconciled through ArgoCD; no resource is applied by hand.

🔎 **[k8s-ops-mcp](https://github.com/eliffkeskin/k8s-ops-mcp)**  Kubernetes diagnostics exposed as MCP tools, with a minimal host that connects a fully local model (Ollama) to them. Read-only by design: the boundary is enforced with RBAC, not prompts.

✨ The three projects form one stack the assistant is evaluated, the platform serving its models is operated through GitOps, and the agent tooling inspects the cluster both run on.

## 🌱 Currently

- Going deeper on KServe & inference operations, LLM evaluation, and MCP tool design
- Writing up each project's engineering story.

## 🧰 Stack

Kubernetes (OpenShift, RKE2, EKS) · Istio · ArgoCD · HashiCorp Vault · Kafka · Keycloak · Python · KServe · MCP · Langfuse

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/eliffkeskin/)
