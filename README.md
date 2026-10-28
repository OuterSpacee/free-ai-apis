<!--lint disable awesome-heading awesome-toc-->

<div align="center">

# Free AI APIs

**A collective list of free AI APIs for developers.**

No credit card required. Build AI apps for $0.

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![APIs Listed](https://img.shields.io/badge/APIs-100+-brightgreen)
![Last Updated](https://img.shields.io/badge/updated-March_2026-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

**[Submit an API](../../issues/new)** | **[Contributing Guide](CONTRIBUTING.md)**

*If this saves you money, give it a star.*

</div>

---

## Contents

- [LLM / Text Generation](#llm--text-generation)
- [Image Generation](#image-generation)
- [Speech-to-Text](#speech-to-text)
- [Text-to-Speech](#text-to-speech)
- [Embeddings](#embeddings)
- [Image Recognition / Vision](#image-recognition--vision)
- [Video Generation](#video-generation)
- [Music / Audio Generation](#music--audio-generation)
- [Translation](#translation)
- [Summarization / Extraction](#summarization--extraction)
- [Code Generation](#code-generation)
- [Search / RAG](#search--rag)
- [Moderation / Safety](#moderation--safety)
- [Model Hosting / Inference](#model-hosting--inference)
- [Multi-Modal Aggregators](#multi-modal-aggregators)

---

## Legend

| Column | Description |
|--------|-------------|
| **API** | Name and link to the API |
| **Description** | What it does |
| **Free Tier** | What you get for free |
| **Auth** | Authentication method: `apiKey`, `OAuth`, `None` |
| **Docs** | Link to API documentation |

---

## LLM / Text Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google AI Studio](https://aistudio.google.com) | Gemini 2.5 Pro/Flash | 1,500 req/day, 2M context | `apiKey` | [Docs](https://ai.google.dev/docs) |
| [Groq](https://groq.com) | Ultra-fast inference (Llama, Mixtral) | 1,000 req/day, 6K tokens/min | `apiKey` | [Docs](https://console.groq.com/docs) |
| [Cerebras](https://cerebras.ai) | Fastest inference available | Free tier included | `apiKey` | [Docs](https://docs.cerebras.ai) |
| [OpenRouter](https://openrouter.ai) | 100+ models, some free | Several models at $0 | `apiKey` | [Docs](https://openrouter.ai/docs) |
| [Hugging Face](https://huggingface.co) | 500K+ open-source models | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Mistral AI](https://mistral.ai) | Mistral/Mixtral models | Daily free token quota | `apiKey` | [Docs](https://docs.mistral.ai) |
| [Cohere](https://cohere.com) | Command R models | Trial API keys, rate limited | `apiKey` | [Docs](https://docs.cohere.com) |
| [Together AI](https://together.ai) | 100+ open-source models | $5 free credits | `apiKey` | [Docs](https://docs.together.ai) |
| [Fireworks AI](https://fireworks.ai) | Fast open-source inference | $1 free credits | `apiKey` | [Docs](https://docs.fireworks.ai) |
| [DeepInfra](https://deepinfra.com) | Serverless model inference | Free credits on signup | `apiKey` | [Docs](https://deepinfra.com/docs) |
| [Ollama](https://ollama.com) | Run LLMs locally | Unlimited (local) | `None` | [Docs](https://github.com/ollama/ollama/blob/main/docs/api.md) |
| [LM Studio](https://lmstudio.ai) | Local model server | Unlimited (local) | `None` | [Docs](https://lmstudio.ai/docs) |
| [Puter](https://puter.com) | Free LLM API in browser | Free, no signup | `None` | [Docs](https://developer.puter.com/tutorials/free-llm-api/) |
| [AIML API](https://aimlapi.com) | 200+ models unified API | Free tier included | `apiKey` | [Docs](https://docs.aimlapi.com) |
| [SambaNova](https://sambanova.ai) | Fast inference platform | Free tier available | `apiKey` | [Docs](https://docs.sambanova.ai) |
| [Novita AI](https://novita.ai) | LLM and image APIs | $0.50 free credits | `apiKey` | [Docs](https://novita.ai/docs) |
| [Hyperbolic](https://hyperbolic.xyz) | Open-source model hosting | Free tier available | `apiKey` | [Docs](https://docs.hyperbolic.xyz) |

<div align="right"><a href="#contents">Back to top</a></div>

## Image Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Stability AI](https://stability.ai) | Stable Diffusion models | 25 free credits/month | `apiKey` | [Docs](https://platform.stability.ai/docs) |
| [Replicate](https://replicate.com) | Run any ML model | $5 free credits (no CC) | `apiKey` | [Docs](https://replicate.com/docs) |
| [Leonardo AI](https://leonardo.ai) | Image generation + editing | 150 tokens/day | `apiKey` | [Docs](https://docs.leonardo.ai) |
| [Hugging Face](https://huggingface.co) | Stable Diffusion via API | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Pollinations](https://pollinations.ai) | Free image generation | Unlimited, no auth | `None` | [Docs](https://github.com/pollinations/pollinations) |
| [Craiyon](https://craiyon.com) | Free AI image generation | Free with watermark | `None` | [Docs](https://docs.craiyon.com) |
| [Clipdrop](https://clipdrop.co) | Image editing APIs | 100 calls/day | `apiKey` | [Docs](https://clipdrop.co/apis/docs) |
| [Flux (via Replicate)](https://replicate.com/black-forest-labs/flux-schnell) | High-quality image gen | Included in Replicate free tier | `apiKey` | [Docs](https://replicate.com/docs) |
| [Together AI](https://together.ai) | FLUX, SD models | Included in free credits | `apiKey` | [Docs](https://docs.together.ai) |

<div align="right"><a href="#contents">Back to top</a></div>

## Speech-to-Text

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Deepgram](https://deepgram.com) | Fast, accurate transcription | $200 free credits | `apiKey` | [Docs](https://developers.deepgram.com) |
| [AssemblyAI](https://assemblyai.com) | Transcription + analysis | ~330 hours free | `apiKey` | [Docs](https://www.assemblyai.com/docs) |
| [Google Cloud Speech](https://cloud.google.com/speech-to-text) | Google's speech recognition | 60 min/month free | `apiKey` | [Docs](https://cloud.google.com/speech-to-text/docs) |
| [Whisper (OpenAI)](https://platform.openai.com) | Multilingual recognition | Via Hugging Face (free) | `apiKey` | [Docs](https://platform.openai.com/docs/guides/speech-to-text) |
| [Whisper (Local)](https://github.com/openai/whisper) | Self-hosted Whisper | Unlimited (local) | `None` | [Docs](https://github.com/openai/whisper) |
| [Vosk](https://alphacephei.com/vosk/) | Offline speech recognition | Unlimited (local) | `None` | [Docs](https://alphacephei.com/vosk/server) |
| [SpeechBrain](https://speechbrain.github.io) | Open-source speech toolkit | Unlimited (local) | `None` | [Docs](https://speechbrain.github.io) |

<div align="right"><a href="#contents">Back to top</a></div>

## Text-to-Speech

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [ElevenLabs](https://elevenlabs.io) | Ultra-realistic voice synthesis | 10K chars/month | `apiKey` | [Docs](https://elevenlabs.io/docs) |
| [Google Cloud TTS](https://cloud.google.com/text-to-speech) | Google's text-to-speech | 4M chars/month free | `apiKey` | [Docs](https://cloud.google.com/text-to-speech/docs) |
| [Amazon Polly](https://aws.amazon.com/polly/) | AWS text-to-speech | 5M chars/month (12 months) | `apiKey` | [Docs](https://docs.aws.amazon.com/polly/) |
| [Coqui TTS (Local)](https://github.com/coqui-ai/TTS) | Open-source TTS | Unlimited (local) | `None` | [Docs](https://tts.readthedocs.io) |
| [Piper (Local)](https://github.com/rhasspy/piper) | Fast local TTS | Unlimited (local) | `None` | [Docs](https://github.com/rhasspy/piper) |
| [Bark (Local)](https://github.com/suno-ai/bark) | Multilingual TTS | Unlimited (local) | `None` | [Docs](https://github.com/suno-ai/bark) |

<div align="right"><a href="#contents">Back to top</a></div>

## Embeddings

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google AI Studio](https://aistudio.google.com) | Gemini embeddings | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/docs/embeddings_guide) |
| [Voyage AI](https://voyageai.com) | High-quality embeddings | 50M tokens free | `apiKey` | [Docs](https://docs.voyageai.com) |
| [Cohere](https://cohere.com) | Embed v4 (multilingual) | Rate-limited free tier | `apiKey` | [Docs](https://docs.cohere.com/reference/embed) |
| [Hugging Face](https://huggingface.co) | 1000s of embedding models | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Jina AI](https://jina.ai) | Embeddings API | 1M tokens free | `apiKey` | [Docs](https://jina.ai/embeddings/) |
| [Nomic](https://nomic.ai) | Open-source embeddings | Free API tier | `apiKey` | [Docs](https://docs.nomic.ai) |
| [Ollama](https://ollama.com) | Local embedding models | Unlimited (local) | `None` | [Docs](https://github.com/ollama/ollama/blob/main/docs/api.md) |

<div align="right"><a href="#contents">Back to top</a></div>

## Image Recognition / Vision

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google Cloud Vision](https://cloud.google.com/vision) | Object detection, OCR | 1,000 units/month | `apiKey` | [Docs](https://cloud.google.com/vision/docs) |
| [Google AI Studio](https://aistudio.google.com) | Gemini vision (multimodal) | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/docs) |
| [Clarifai](https://clarifai.com) | Image/video recognition | 1,000 ops/month | `apiKey` | [Docs](https://docs.clarifai.com) |
| [Roboflow](https://roboflow.com) | Custom vision models | 1,000 inferences/month | `apiKey` | [Docs](https://docs.roboflow.com) |
| [Hugging Face](https://huggingface.co) | Vision transformers | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Surya (Local)](https://github.com/VikParuchuri/surya) | OCR + layout detection | Unlimited (local) | `None` | [Docs](https://github.com/VikParuchuri/surya) |

<div align="right"><a href="#contents">Back to top</a></div>

## Video Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Kling AI](https://klingai.com) | High-quality video gen | Free daily credits | `apiKey` | [Docs](https://docs.klingai.com) |
| [Replicate](https://replicate.com) | Video models (Wan, CogVideo) | $5 free credits | `apiKey` | [Docs](https://replicate.com/docs) |
| [Hugging Face](https://huggingface.co) | Open-source video models | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |

<div align="right"><a href="#contents">Back to top</a></div>

## Music / Audio Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Suno](https://suno.com) | Full song generation | 5 songs/day | `OAuth` | [Docs](https://suno.com) |
| [Udio](https://udio.com) | AI music generation | Limited free credits | `OAuth` | [Docs](https://udio.com) |
| [Replicate](https://replicate.com) | MusicGen, AudioGen | $5 free credits | `apiKey` | [Docs](https://replicate.com/docs) |
| [AudioCraft (Local)](https://github.com/facebookresearch/audiocraft) | Meta's audio generation | Unlimited (local) | `None` | [Docs](https://github.com/facebookresearch/audiocraft) |

<div align="right"><a href="#contents">Back to top</a></div>

## Translation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [DeepL](https://deepl.com) | High-quality translation | 500K chars/month | `apiKey` | [Docs](https://www.deepl.com/docs-api) |
| [Google Translate](https://cloud.google.com/translate) | Google's translation | 500K chars/month | `apiKey` | [Docs](https://cloud.google.com/translate/docs) |
| [LibreTranslate](https://libretranslate.com) | Open-source translation | Free API (rate limited) | `None` | [Docs](https://github.com/LibreTranslate/LibreTranslate) |
| [MyMemory](https://mymemory.translated.net) | Translation memory API | 5,000 words/day | `None` | [Docs](https://mymemory.translated.net/doc/) |
| [Lingva](https://lingva.ml) | Google Translate alternative | Unlimited (no tracking) | `None` | [Docs](https://github.com/thedaviddelta/lingva-translate) |

<div align="right"><a href="#contents">Back to top</a></div>

## Summarization / Extraction

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google AI Studio](https://aistudio.google.com) | Summarize with Gemini | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/docs) |
| [Hugging Face](https://huggingface.co) | Summarization models | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Firecrawl](https://firecrawl.dev) | Web scraping for LLMs | 500 credits free | `apiKey` | [Docs](https://docs.firecrawl.dev) |
| [Diffbot](https://diffbot.com) | Structured data extraction | 10K pages free trial | `apiKey` | [Docs](https://docs.diffbot.com) |
| [Unstructured](https://unstructured.io) | Document parsing | Free API tier | `apiKey` | [Docs](https://docs.unstructured.io) |

<div align="right"><a href="#contents">Back to top</a></div>

## Code Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google AI Studio](https://aistudio.google.com) | Code with Gemini | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/docs) |
| [Groq](https://groq.com) | Fast code generation | 1,000 req/day | `apiKey` | [Docs](https://console.groq.com/docs) |
| [DeepSeek](https://platform.deepseek.com) | DeepSeek Coder models | Low-cost (~free level) | `apiKey` | [Docs](https://platform.deepseek.com/docs) |
| [Codeium](https://codeium.com) | AI code completion | Free for individuals | `apiKey` | [Docs](https://codeium.com/docs) |
| [Hugging Face](https://huggingface.co) | StarCoder, CodeLlama | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Tabby (Local)](https://github.com/TabbyML/tabby) | Self-hosted code assist | Unlimited (local) | `None` | [Docs](https://tabby.tabbyml.com) |

<div align="right"><a href="#contents">Back to top</a></div>

## Search / RAG

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Tavily](https://tavily.com) | Search API for AI agents | 1,000 searches/month | `apiKey` | [Docs](https://docs.tavily.com) |
| [Exa](https://exa.ai) | AI-native search API | 1,000 searches/month | `apiKey` | [Docs](https://docs.exa.ai) |
| [Brave Search API](https://brave.com/search/api/) | Privacy-focused search | 2,000 queries/month | `apiKey` | [Docs](https://api.search.brave.com/app/documentation/) |
| [SerpApi](https://serpapi.com) | Search engine results | 100 searches/month | `apiKey` | [Docs](https://serpapi.com/docs) |
| [FastAF](https://fastaf.co/compare/free-tier/?utm_source=free-ai-apis&utm_medium=listing&utm_campaign=free-tier-lists) | Web search, SERP and scraping for LLMs | 500 free credits every month after email verification (not on x402) | `apiKey` | [Docs](https://fastaf.co/docs/) |
| [SearXNG (Local)](https://github.com/searxng/searxng) | Self-hosted metasearch | Unlimited (local) | `None` | [Docs](https://docs.searxng.org) |

<div align="right"><a href="#contents">Back to top</a></div>

## Moderation / Safety

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [OpenAI Moderation](https://platform.openai.com) | Content moderation | Free (unlimited) | `apiKey` | [Docs](https://platform.openai.com/docs/guides/moderation) |
| [Perspective API](https://perspectiveapi.com) | Toxicity detection (Google) | Free (rate limited) | `apiKey` | [Docs](https://developers.perspectiveapi.com) |
| [Hugging Face](https://huggingface.co) | Toxicity/sentiment models | Free Inference API | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [LLM Guard (Local)](https://github.com/protectai/llm-guard) | LLM input/output security | Unlimited (local) | `None` | [Docs](https://llm-guard.com) |

<div align="right"><a href="#contents">Back to top</a></div>

## Model Hosting / Inference

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Hugging Face Spaces](https://huggingface.co/spaces) | Host ML apps (Gradio/Streamlit) | Free CPU instances | `None` | [Docs](https://huggingface.co/docs/hub/spaces) |
| [Replicate](https://replicate.com) | Run any model via API | $5 free credits | `apiKey` | [Docs](https://replicate.com/docs) |
| [Google Colab](https://colab.research.google.com) | Free GPU notebooks | Free T4 GPU | `OAuth` | [Docs](https://colab.research.google.com) |
| [Kaggle Notebooks](https://kaggle.com) | Free GPU notebooks | 30h GPU/week | `OAuth` | [Docs](https://www.kaggle.com/docs) |
| [Lightning AI](https://lightning.ai) | GPU-powered dev studios | 22 free GPU hours | `OAuth` | [Docs](https://lightning.ai/docs) |

<div align="right"><a href="#contents">Back to top</a></div>

## Multi-Modal Aggregators

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [OpenRouter](https://openrouter.ai) | Unified API for 100+ models | Free models available | `apiKey` | [Docs](https://openrouter.ai/docs) |
| [AIML API](https://aimlapi.com) | 200+ models, one API | Free tier included | `apiKey` | [Docs](https://docs.aimlapi.com) |
| [LiteLLM](https://github.com/BerriAI/litellm) | Unified proxy for all providers | Unlimited (self-hosted) | `None` | [Docs](https://docs.litellm.ai) |
| [Puter](https://puter.com) | Free AI in browser | Free, no signup | `None` | [Docs](https://developer.puter.com) |

<div align="right"><a href="#contents">Back to top</a></div>

---

## Contributing

Found a free API we missed? See [CONTRIBUTING.md](CONTRIBUTING.md) for how to add it.

## License

[CC0 1.0 Universal](LICENSE) - Public Domain.

---

<div align="center">

**If this saves you money, give it a star.**

</div>

---

## Also By OuterSpacee

| Project | Description |
|---------|-------------|
| [Awesome AI Tools](https://github.com/OuterSpacee/awesome-ai-tools) | 200+ AI tools across 22 categories |
| [Build Your Own AI](https://github.com/OuterSpacee/build-your-own-ai) | 150+ tutorials for building AI projects from scratch |
| [AI Engineering Handbook](https://github.com/OuterSpacee/ai-engineering-handbook) | Everything you need to build production AI apps |
| [aimsg](https://github.com/OuterSpacee/aimsg) | AI-powered git commit messages — free with Ollama |
