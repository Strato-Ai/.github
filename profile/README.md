# Strato.AI

Open-source infrastructure for self-hosted AI inference.

We build the tools that let teams run large language models on their own hardware — routing requests across GPU backends, monitoring health, and scaling without vendor lock-in.

## Projects

| Repository | Description |
|-----------|-------------|
| [Spectre](https://github.com/Strato-Ai/Spectre-ai-inference-loadbalancer) | NGINX-based load balancer for AI inference with model-aware routing, GPU health monitoring, and multi-platform support (NVIDIA / Apple Silicon / CPU) |

## What We Focus On

- **Self-hosted AI inference** — run models on your own GPUs, not someone else's cloud
- **Model-aware routing** — direct requests to the right backend based on model name and GPU load
- **Multi-platform GPU support** — NVIDIA (nvidia-smi), Apple Silicon (macmon), and CPU fallback
- **Infrastructure as code** — Terraform modules for reproducible deployments

## Tech Stack

`NGINX` · `FastAPI` · `Terraform` · `LM Studio` · `Python` · `Bash` · `systemd`

## License

All projects are released under the [MIT License](https://opensource.org/licenses/MIT).
