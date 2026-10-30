# Awesome Local Llm

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [中文](README.zh-CN.md) | [日本語](README.ja.md) | **Русский**

Локальные LLM — инструменты, модели, приватность

## s Бегуны
Инструмент Что?
|---|---|
[Ollama] (https://github.com/ollama/ollama) | Докер локальных LLM
[llama.cpp] (https://github.com/ggml-org/llama.cpp) Двигатель под всем этим
LM Studio (https://lmstudio.ai/) - дружественный графический интерфейс для локальных моделей
| [Jan](https://github.com/janhq/jan) | Альтернатива рабочего стола ChatGPT с открытым исходным кодом |
| [GPT4All] (https://github.com/nomic-ai/gpt4all) | Легкий настольный бегун + местный RAG |
| [koboldcpp](https://github.com/LostRuins/koboldcpp) | Многофункциональный однобинарный сервер |
[vLLM] (https://github.com/vllm-project/vllm) | Высокопроизводительное производство
| [MLX] (https://github.com/ml-explore/mlx) | ML фреймворк Apple — быстро на M-чипах |

##  Model Модели, которые стоит использовать
Сладкое место / Sweet spot
|---|---|
| Llama 3.x (8B/70B) | Общий чат, рабочая лошадка Meta |
| Qwen 2.5/3 | Лучший многоязычный + кодирование на ГБ |
Mistral / Mixtral | Efficient MoE, французский язык
DeepSeek-V3/R1 - монстр разума
| Gemma 2/3 | Компактные открытые веса Google
Phi-4 — маленький, но умный Microsoft

## Интеграция
Инструмент Что?
|---|---|
[Открытый WebUI] (https://github.com/open-webui/open-webui) | Пользовательский интерфейс, похожий на ChatGPT
| [LocalAI] (https://github.com/mudler/LocalAI) | OpenAI-совместимый локальный API |
[LiteLLM] (https://github.com/BerriAI/litellm) | Один API → 100+ провайдеров

Почему локально? Конфиденциальность в первую очередь, офлайн, нулевая стоимость за токен. Хорошо сочетается с [Snitch] (https://github.com/aixisstudio/Snitch), чтобы *доказать*, что ничто не покидает вашу машину.

##   Модели по размеру и использованию

Лучший размер / Size - Best for
|---|---|---|
Llama 3.3 70B | 40GB + | Лучшее открытое качество |
Qwen 2.5 72B | 45GB + | Многоязычный / кодирующий
Mistral Small 3 | 14GB | Сладкое пятно 24B
Phi-4 | 9 ГБ | Microsoft 14B — отличная аргументация
| Джемма 2 9B | 6GB | Быстро + хорошо
Qwen 2.5 3B | 2GB | Удобный для ноутбуков
| Llama 3.2 1B | <1GB | Телефонный класс |

##  ️ Обслуживание и настройка

Инструмент Что?
|---|---|
[llama.cpp] (https://github.com/ggml-org/llama.cpp) — вывод CPU/GPU повсюду
| [llama-swap] (https://github.com/mostlygeek/llama-swap) | Модели горячей замены на одном порту |
[text-generation-webui] (https://github.com/oobabooga/text-generation-webui) | Функциональный интерфейс
[KoboldCpp] (https://github.com/LostRuins/koboldcpp) | Ориентированный на рассказы
| [Unsloth](https://github.com/unslothai/unsloth) | 2-5× более быстрая настройка |
[Axolotl] (https://github.com/axolotl-ai-cloud/axolotl) | Настройки, управляемые YAML

###Твердое руководство

Обсуждение Setup | Runs
|---|---|
| 8 ГБ ОЗУ ноутбука | 3B-4B квантованный |
| 16GB Mac / игровой ПК | 7-9B быстро, 14B ok |
| 24GB VRAM | 24-32B квантованный |
| 64GB+ | 70B квантованный |

---
## Участие

Pull request'ы приветствуются — открой PR, он будет проверен и принят. Ведёт [aixisstudio](https://github.com/aixisstudio), автор [Snitch](https://github.com/aixisstudio/Snitch) — open-source application firewall.

## Лицензия: MIT
