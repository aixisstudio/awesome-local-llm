# Awesome Local Llm

[English](README.md) | [Français](README.fr.md) | **Español** | [中文](README.zh-CN.md) | [日本語](README.ja.md) | [Русский](README.ru.md)

Ejecuta LLMs en local — herramientas, modelos, IA privada

_El contenido detallado (listas, enlaces, descripciones) está en inglés por mantenibilidad — las secciones siguientes te guían._

## 🏃 Runners
| Tool | What |
|---|---|
| [Ollama](https://github.com/ollama/ollama) | The Docker of local LLMs |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | The engine underneath everything |
| [LM Studio](https://lmstudio.ai/) | Friendly GUI for local models |
| [Jan](https://github.com/janhq/jan) | Open-source ChatGPT desktop alternative |
| [GPT4All](https://github.com/nomic-ai/gpt4all) | Easy desktop runner + local RAG |
| [koboldcpp](https://github.com/LostRuins/koboldcpp) | Feature-rich single-binary server |
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput production serving |
| [MLX](https://github.com/ml-explore/mlx) | Apple's ML framework — fast on M-chips |

## 🧠 Models worth running
| Model | Sweet spot |
|---|---|
| Llama 3.x (8B/70B) | General chat, Meta's workhorse |
| Qwen 2.5/3 | Best multilingual + coding per GB |
| Mistral / Mixtral | Efficient MoE, French 🇫🇷 |
| DeepSeek-V3/R1 | Reasoning monster |
| Gemma 2/3 | Google's compact open weights |
| Phi-4 | Microsoft's small-but-smart |

## 🔌 Integrations
| Tool | What |
|---|---|
| [Open WebUI](https://github.com/open-webui/open-webui) | Self-hosted ChatGPT-like UI |
| [LocalAI](https://github.com/mudler/LocalAI) | OpenAI-compatible local API |
| [LiteLLM](https://github.com/BerriAI/litellm) | One API → 100+ providers |

> 🔒 Why local? Privacy-first, offline, zero cost per token. Pairs well with [Snitch](https://github.com/aixisstudio/Snitch) to *prove* nothing leaves your machine.

## 📦 Models by size & use

| Model | Size | Best for |
|---|---|---|
| Llama 3.3 70B | 40GB+ | Best open quality |
| Qwen 2.5 72B | 45GB+ | Multilingual/coding |
| Mistral Small 3 | 14GB | Sweet spot 24B |
| Phi-4 | 9GB | Microsoft's 14B — great reasoning |
| Gemma 2 9B | 6GB | Fast + good |
| Qwen 2.5 3B | 2GB | Laptop-friendly |
| Llama 3.2 1B | <1GB | Phone-class |

## ⚙️ Serving & tuning

| Tool | What |
|---|---|
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | CPU/GPU inference everywhere |
| [llama-swap](https://github.com/mostlygeek/llama-swap) | Hot-swap models on one port |
| [text-generation-webui](https://github.com/oobabooga/text-generation-webui) | Feature-dense UI |
| [KoboldCpp](https://github.com/LostRuins/koboldcpp) | Storytelling-oriented |
| [Unsloth](https://github.com/unslothai/unsloth) | 2-5× faster finetuning |
| [Axolotl](https://github.com/axolotl-ai-cloud/axolotl) | YAML-driven finetunes |

## 🧪 Hardware guide

| Setup | Runs |
|---|---|
| 8GB RAM laptop | 3B-4B quantized |
| 16GB Mac / gaming PC | 7-9B fast, 14B ok |
| 24GB VRAM | 24-32B quantized |
| 64GB+ | 70B quantized |

---
## Contribuir

Los pull requests son bienvenidos: abre una PR y será revisada y fusionada. Mantenido por [aixisstudio](https://github.com/aixisstudio), autor de [Snitch](https://github.com/aixisstudio/Snitch), firewall de aplicaciones open source.

## Licencia: MIT
