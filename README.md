# Awesome Open Source AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Awesome Open Source AI is a curated list of useful open-source AI resources, including inference engines, LLMs, and tools. Specifically, this list aims to link to resources that meet the [Open Source Initiative® (OSI) definition of open source](https://opensource.org/osd) as much as possible.

# Table of Contents

- [Inference Engines](#inference-engines)
- [Language Models](#language-models)
- [Embedding Models](#embedding-models)
- [Image Models](#image-models)
- [Video Models](#video-models)
- [Tools](#tools)

# Inference Engines

- [koboldcpp](https://github.com/LostRuins/koboldcpp) - Is the swiss army knife of LLM inference engines that supports multiple API endpoints such as Ollama.
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - Barebones LLM inference engine with additional options to control LLM output beyond those of Ollama.
- [Ollama](https://ollama.com/) - Easy-to-use LLM inference engine offering an OpenAI-compatible API server.
- [OpenedAI Speech](https://github.com/matatonic/openedai-speech) - Great OpenAI-compatible API TTS server that works with Piper TTS, which runs fast on the CPU.

# Language Models

- [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1) - Great language model that's suited for reasoning & logic related tasks.
- [Granite 3.1](https://www.ibm.com/granite/docs/) - Great for RAG and suited for deployment on low-end consumer hardware.
- [InternVL 2.5](https://github.com/OpenGVLab/InternVL)[^1] - Great language model for vision-related tasks and scores better on benchmarks compared to Qwen2-VL.
- [OLMo 2](https://allenai.org/blog/olmo2) - Completely open language model with all parts of the model training process open-source and scores well on benchmarks.
- [Phi-4](https://huggingface.co/microsoft/phi-4) - Great language model that is SOTA in various benchmarks for a medium-sized language model that's great for instruction-following and logical tasks (Note: Phi models typically underform outside benchmarks).
- [Qwen 2.5](https://qwenlm.github.io/blog/qwen2.5/)[^2] - Best in-class language models that excel in benchmarks for math, etc., but may have censorship on certain topics (i.e. Tiananmen Square).
- [Qwen 2.5 Coder](https://qwenlm.github.io/blog/qwen2.5-coder-family/)[^3] - Best in-class language models that excel in coding related tasks.
- [Qwen 2.5-1M](https://qwenlm.github.io/blog/qwen2.5-1m/) - Similar to Qwen 2.5 but supports a context length of up to 1M tokens, making it suitable for long-context tasks such as podcast generation.
- [Qwen2-VL](https://qwenlm.github.io/blog/qwen2-vl/)[^4] - Great LLM that supports vision understanding (image & video) and is supported by llama.cpp.
- [SmolLM2](https://github.com/huggingface/smollm) - A series of tiny language models that is great for tinkering around and summarizing content (not so great for finetuning).

[^1]: Only 1B and 38B are open-source.
[^2]: The 3B and 72B models are not open-source.
[^3]: The 3B model is not open-source.
[^4]: The 72B model is not open-source.

# Embedding Models

- [BGE-EN-ICL](https://huggingface.co/BAAI/bge-en-icl) - SOTA embedding model that scores great on the [MTEB leaderboard](https://huggingface.co/spaces/mteb/leaderboard).
- [all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) - Great small embedding model perfectly suited for deployment on low-end consumer hardware.

# Image Models
Coming soon...

# Video Models
Coming soon...

# Tools

- [LLM Finetuning Script](https://www.kaggle.com/code/thomasanderson1962/public-llm-finetuning-script) - A script for finetuning language models based on dataset from the [synthetic dataset generation tool](https://www.kaggle.com/code/thomasanderson1962/public-synthetic-dataset-generation-w-internvl2).
- [Open WebUI](https://openwebui.com/) - Provides a ChatGPT-like interface for chatting with local/external language models.
- [Synthetic Dataset Generation w/ InternVL2](https://www.kaggle.com/code/thomasanderson1962/public-synthetic-dataset-generation-w-internvl2) - A script for generating synthetic datasets from PDF files (using vision instead of text extraction).
- [TextCraft](https://github.com/suncloudsmoon/TextCraft) - Add-in for Microsoft Word with tools for proofreading, text generation, etc.