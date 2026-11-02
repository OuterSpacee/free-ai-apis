<!--lint disable awesome-heading awesome-toc-->

<div align="center">

# Free AI APIs

**A collective list of free AI APIs for developers.**

No credit card required. Build AI apps for $0.

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
![APIs Listed](https://img.shields.io/badge/APIs-100+-brightgreen)
![Last Updated](https://img.shields.io/badge/updated-October_2026-blue)
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
| [Google AI Studio](https://aistudio.google.com) | Gemini models via Gemini API | Free tier, limits vary by model (see AI Studio) | `apiKey` | [Docs](https://ai.google.dev/gemini-api/docs) |
| [Groq](https://groq.com) | Ultra-fast inference (Llama, Mixtral) | Free plan, e.g. gpt-oss-120b: 30 req/min, 1K req/day | `apiKey` | [Docs](https://console.groq.com/docs) |
| [Cerebras](https://cerebras.ai) | Fastest inference available | Free tier: 1M tokens/day per model, 5 req/min | `apiKey` | [Docs](https://docs.cerebras.ai) |
| [OpenRouter](https://openrouter.ai) | 100+ models, some free | `:free` models: 20 req/min, 50 req/day (1,000 with $10+ credits) | `apiKey` | [Docs](https://openrouter.ai/docs) |
| [Hugging Face](https://huggingface.co) | 500K+ open-source models | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Mistral AI](https://mistral.ai) | Mistral/Mixtral models | Daily free token quota | `apiKey` | [Docs](https://docs.mistral.ai) |
| [Cohere](https://cohere.com) | Command R models | Trial keys: 1,000 calls/month, 20 req/min | `apiKey` | [Docs](https://docs.cohere.com) |
| [Together AI](https://together.ai) | 100+ open-source models | $5 free credits | `apiKey` | [Docs](https://docs.together.ai) |
| [Fireworks AI](https://fireworks.ai) | Fast open-source inference | $1 free credits | `apiKey` | [Docs](https://docs.fireworks.ai) |
| [DeepInfra](https://deepinfra.com) | Serverless model inference | Free credits on signup | `apiKey` | [Docs](https://docs.deepinfra.com) |
| [Ollama](https://ollama.com) | Run LLMs locally | Unlimited (local) | `None` | [Docs](https://github.com/ollama/ollama/blob/main/docs/api.md) |
| [LM Studio](https://lmstudio.ai) | Local model server | Unlimited (local) | `None` | [Docs](https://lmstudio.ai/docs) |
| [Puter](https://puter.com) | Free LLM API in browser | Free, no signup | `None` | [Docs](https://developer.puter.com/tutorials/free-llm-api/) |
| [AIML API](https://aimlapi.com) | 200+ models unified API | Free tier included | `apiKey` | [Docs](https://docs.aimlapi.com) |
| [SambaNova](https://sambanova.ai) | Fast inference platform | Free tier available | `apiKey` | [Docs](https://docs.sambanova.ai) |
| [Novita AI](https://novita.ai) | LLM and image APIs | $0.50 free credits | `apiKey` | [Docs](https://docs.novita.ai/guides/introduction) |
| [Hyperbolic](https://www.hyperbolic.ai) | Open-source model hosting | Free tier available | `apiKey` | [Docs](https://www.hyperbolic.ai/docs/overview/overview) |
| [NVIDIA NIM](https://build.nvidia.com) | Hosted Llama, DeepSeek, Qwen, Nemotron and more, OpenAI-compatible | Free prototyping access via NVIDIA Developer Program, rate limited | `apiKey` | [Docs](https://docs.api.nvidia.com) |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/) | Serverless open-source LLMs, image and speech models | 10,000 Neurons/day free | `apiKey` | [Docs](https://developers.cloudflare.com/workers-ai/) |
| [Z.ai (Zhipu)](https://z.ai) | GLM models via API | GLM-4.7-Flash, GLM-4.5-Flash and GLM-4.6V-Flash are free | `apiKey` | [Docs](https://docs.z.ai) |

<div align="right"><a href="#contents">Back to top</a></div>

## Image Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Stability AI](https://stability.ai) | Stable Diffusion models | 25 free credits/month | `apiKey` | [Docs](https://docs.stability.ai) |
| [Replicate](https://replicate.com) | Run any ML model | $5 free credits (no CC) | `apiKey` | [Docs](https://replicate.com/docs) |
| [Leonardo AI](https://leonardo.ai) | Image generation + editing | 150 tokens/day | `apiKey` | [Docs](https://docs.leonardo.ai) |
| [Hugging Face](https://huggingface.co) | Stable Diffusion via API | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Pollinations](https://pollinations.ai) | Free image generation | Unlimited, no auth | `None` | [Docs](https://github.com/pollinations/pollinations) |
| [Clipdrop](https://clipdrop.co) | Image editing APIs | 100 calls/day | `apiKey` | [Docs](https://clipdrop.co/apis/docs) |
| [Flux (via Replicate)](https://replicate.com/black-forest-labs/flux-schnell) | High-quality image gen | Included in Replicate free tier | `apiKey` | [Docs](https://replicate.com/docs) |
| [Together AI](https://together.ai) | FLUX, SD models | Included in free credits | `apiKey` | [Docs](https://docs.together.ai) |

<div align="right"><a href="#contents">Back to top</a></div>

## Speech-to-Text

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Deepgram](https://deepgram.com) | Fast, accurate transcription | $200 free credits | `apiKey` | [Docs](https://developers.deepgram.com) |
| [AssemblyAI](https://assemblyai.com) | Transcription + analysis | $50 free credits on signup, no card | `apiKey` | [Docs](https://www.assemblyai.com/docs) |
| [Google Cloud Speech](https://cloud.google.com/speech-to-text) | Google's speech recognition | 60 min/month free | `apiKey` | [Docs](https://docs.cloud.google.com/speech-to-text/docs) |
| [Whisper (OpenAI)](https://platform.openai.com) | Multilingual recognition | Via Hugging Face (free) | `apiKey` | [Docs](https://developers.openai.com/api/docs/guides/speech-to-text) |
| [Whisper (Local)](https://github.com/openai/whisper) | Self-hosted Whisper | Unlimited (local) | `None` | [Docs](https://github.com/openai/whisper) |
| [Vosk](https://alphacephei.com/vosk/) | Offline speech recognition | Unlimited (local) | `None` | [Docs](https://alphacephei.com/vosk/server) |
| [SpeechBrain](https://speechbrain.github.io) | Open-source speech toolkit | Unlimited (local) | `None` | [Docs](https://speechbrain.github.io) |

<div align="right"><a href="#contents">Back to top</a></div>

## Text-to-Speech

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [ElevenLabs](https://elevenlabs.io) | Ultra-realistic voice synthesis | 10K chars/month | `apiKey` | [Docs](https://elevenlabs.io/docs) |
| [Google Cloud TTS](https://cloud.google.com/text-to-speech) | Google's text-to-speech | 4M chars/month free | `apiKey` | [Docs](https://docs.cloud.google.com/text-to-speech/docs) |
| [Amazon Polly](https://aws.amazon.com/polly/) | AWS text-to-speech | 5M chars/month (12 months) | `apiKey` | [Docs](https://docs.aws.amazon.com/polly/) |
| [Cartesia](https://cartesia.ai) | Low-latency voice synthesis | 20K credits/month | `apiKey` | [Docs](https://docs.cartesia.ai) |
| [Coqui TTS (Local)](https://github.com/coqui-ai/TTS) | Open-source TTS | Unlimited (local) | `None` | [Docs](https://docs.coqui.ai/en/latest/) |
| [Piper (Local)](https://github.com/OHF-Voice/piper1-gpl) | Fast local TTS | Unlimited (local) | `None` | [Docs](https://github.com/OHF-Voice/piper1-gpl) |
| [Bark (Local)](https://github.com/suno-ai/bark) | Multilingual TTS | Unlimited (local) | `None` | [Docs](https://github.com/suno-ai/bark) |

<div align="right"><a href="#contents">Back to top</a></div>

## Embeddings

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google AI Studio](https://aistudio.google.com) | Gemini embeddings | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/gemini-api/docs/embeddings) |
| [Voyage AI](https://voyageai.com) | High-quality embeddings | 200M free tokens (current models) | `apiKey` | [Docs](https://docs.voyageai.com) |
| [Cohere](https://cohere.com) | Embed v4 (multilingual) | Rate-limited free tier | `apiKey` | [Docs](https://docs.cohere.com/reference/embed) |
| [Hugging Face](https://huggingface.co) | 1000s of embedding models | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Jina AI](https://jina.ai) | Embeddings API | 1M tokens free | `apiKey` | [Docs](https://jina.ai/embeddings/) |
| [Nomic](https://nomic.ai) | Open-source embeddings | Free API tier | `apiKey` | [Docs](https://docs.nomic.ai) |
| [Mixedbread](https://www.mixedbread.com) | Embeddings and rerankers | $5 one-time credits, no card | `apiKey` | [Docs](https://www.mixedbread.com/docs) |
| [Ollama](https://ollama.com) | Local embedding models | Unlimited (local) | `None` | [Docs](https://github.com/ollama/ollama/blob/main/docs/api.md) |

<div align="right"><a href="#contents">Back to top</a></div>

## Image Recognition / Vision

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google Cloud Vision](https://cloud.google.com/vision) | Object detection, OCR | 1,000 units/month | `apiKey` | [Docs](https://docs.cloud.google.com/vision/docs) |
| [Google AI Studio](https://aistudio.google.com) | Gemini vision (multimodal) | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/gemini-api/docs) |
| [Clarifai](https://clarifai.com) | Image/video recognition | 1,000 ops/month | `apiKey` | [Docs](https://docs.clarifai.com) |
| [Roboflow](https://roboflow.com) | Custom vision models | 1,000 inferences/month | `apiKey` | [Docs](https://docs.roboflow.com) |
| [Hugging Face](https://huggingface.co) | Vision transformers | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Surya (Local)](https://github.com/datalab-to/surya) | OCR + layout detection | Unlimited (local) | `None` | [Docs](https://github.com/datalab-to/surya) |
| [OCR.space](https://ocr.space/ocrapi) | OCR API for images and PDFs | 25,000 req/month, 500/day per IP | `apiKey` | [Docs](https://ocr.space/ocrapi) |

<div align="right"><a href="#contents">Back to top</a></div>

## Video Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Kling AI](https://kling.ai) | High-quality video gen | Free daily credits | `apiKey` | [Docs](https://kling.ai/dev) |
| [Replicate](https://replicate.com) | Video models (Wan, CogVideo) | $5 free credits | `apiKey` | [Docs](https://replicate.com/docs) |
| [Hugging Face](https://huggingface.co) | Open-source video models | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |

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
| [DeepL](https://deepl.com) | High-quality translation | 500K chars/month | `apiKey` | [Docs](https://developers.deepl.com/docs/getting-started/quickstart) |
| [Google Translate](https://cloud.google.com/translate) | Google's translation | 500K chars/month | `apiKey` | [Docs](https://docs.cloud.google.com/translate/docs) |
| [LibreTranslate](https://libretranslate.com) | Open-source translation | Free API (rate limited) | `None` | [Docs](https://github.com/LibreTranslate/LibreTranslate) |
| [MyMemory](https://mymemory.translated.net) | Translation memory API | 5,000 words/day | `None` | [Docs](https://mymemory.translated.net/doc/) |
| [Lingva](https://lingva.ml) | Google Translate alternative | Unlimited (no tracking) | `None` | [Docs](https://github.com/thedaviddelta/lingva-translate) |

<div align="right"><a href="#contents">Back to top</a></div>

## Summarization / Extraction

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google AI Studio](https://aistudio.google.com) | Summarize with Gemini | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/gemini-api/docs) |
| [Hugging Face](https://huggingface.co) | Summarization models | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Firecrawl](https://firecrawl.dev) | Web scraping for LLMs | 1,000 free credits/month | `apiKey` | [Docs](https://docs.firecrawl.dev) |
| [Diffbot](https://diffbot.com) | Structured data extraction | 10K pages free trial | `apiKey` | [Docs](https://www.diffbot.com/docs/) |
| [Unstructured](https://unstructured.io) | Document parsing | Free API tier | `apiKey` | [Docs](https://docs.unstructured.io) |
| [LlamaParse](https://www.llamaindex.ai/llamaparse) | Document parsing for LLMs | 10K credits/month | `apiKey` | [Docs](https://docs.cloud.llamaindex.ai) |

<div align="right"><a href="#contents">Back to top</a></div>

## Code Generation

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Google AI Studio](https://aistudio.google.com) | Code with Gemini | Included in free tier | `apiKey` | [Docs](https://ai.google.dev/gemini-api/docs) |
| [Groq](https://groq.com) | Fast code generation | 1,000 req/day | `apiKey` | [Docs](https://console.groq.com/docs) |
| [DeepSeek](https://platform.deepseek.com) | DeepSeek Coder models | Low-cost (~free level) | `apiKey` | [Docs](https://platform.deepseek.com/docs) |
| [Hugging Face](https://huggingface.co) | StarCoder, CodeLlama | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [Tabby (Local)](https://github.com/TabbyML/tabby) | Self-hosted code assist | Unlimited (local) | `None` | [Docs](https://www.tabbyml.com) |

<div align="right"><a href="#contents">Back to top</a></div>

## Search / RAG

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Tavily](https://tavily.com) | Search API for AI agents | 1,000 searches/month | `apiKey` | [Docs](https://docs.tavily.com) |
| [Exa](https://exa.ai) | AI-native search API | $10 free credits/month (~2,500 Lite searches) | `apiKey` | [Docs](https://exa.ai/docs) |
| [Brave Search API](https://brave.com/search/api/) | Privacy-focused search | $5 free credits/month (~1,000 queries); card required for verification | `apiKey` | [Docs](https://api.search.brave.com/app/documentation/) |
| [SerpApi](https://serpapi.com) | Search engine results | 100 searches/month | `apiKey` | [Docs](https://serpapi.com/search-api) |
| [Pinecone](https://www.pinecone.io) | Managed vector database + hosted embeddings | Starter plan: 2 GB storage, 5M embedding tokens/month | `apiKey` | [Docs](https://docs.pinecone.io) |
| [Qdrant Cloud](https://qdrant.tech/cloud/) | Managed vector database | Free cluster: 1 GB RAM, 4 GB disk | `apiKey` | [Docs](https://qdrant.tech/documentation/) |
| [Supabase](https://supabase.com) | Postgres with pgvector for embeddings | Free plan: 500 MB DB, 2 projects | `apiKey` | [Docs](https://supabase.com/docs/guides/ai) |
| [SearXNG (Local)](https://github.com/searxng/searxng) | Self-hosted metasearch | Unlimited (local) | `None` | [Docs](https://docs.searxng.org) |

<div align="right"><a href="#contents">Back to top</a></div>

## Moderation / Safety

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [OpenAI Moderation](https://platform.openai.com) | Content moderation | Free (unlimited) | `apiKey` | [Docs](https://developers.openai.com/api/docs/guides/moderation) |
| [Perspective API](https://perspectiveapi.com) | Toxicity detection (Google) | Free (rate limited) | `apiKey` | [Docs](https://developers.perspectiveapi.com) |
| [Hugging Face](https://huggingface.co) | Toxicity/sentiment models | Pay-as-you-go credits (PRO includes $2/month) | `apiKey` | [Docs](https://huggingface.co/docs/api-inference) |
| [LLM Guard (Local)](https://github.com/protectai/llm-guard) | LLM input/output security | Unlimited (local) | `None` | [Docs](https://protectai.github.io/llm-guard/) |

<div align="right"><a href="#contents">Back to top</a></div>

## Model Hosting / Inference

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [Hugging Face Spaces](https://huggingface.co/spaces) | Host ML apps (Gradio/Streamlit) | Free CPU instances | `None` | [Docs](https://huggingface.co/docs/hub/spaces) |
| [Replicate](https://replicate.com) | Run any model via API | $5 free credits | `apiKey` | [Docs](https://replicate.com/docs) |
| [Google Colab](https://colab.research.google.com) | Free GPU notebooks | Free T4 GPU | `OAuth` | [Docs](https://colab.research.google.com) |
| [Kaggle Notebooks](https://kaggle.com) | Free GPU notebooks | 30h GPU/week | `OAuth` | [Docs](https://www.kaggle.com/docs) |
| [Modal](https://modal.com) | Serverless GPU compute for inference | $30 free compute/month | `apiKey` | [Docs](https://modal.com/docs) |
| [Lightning AI](https://lightning.ai) | GPU-powered dev studios | 22 free GPU hours | `OAuth` | [Docs](https://lightning.ai/docs) |

<div align="right"><a href="#contents">Back to top</a></div>

## Multi-Modal Aggregators

| API | Description | Free Tier | Auth | Docs |
|-----|-------------|-----------|------|------|
| [OpenRouter](https://openrouter.ai) | Unified API for 100+ models | Free models available | `apiKey` | [Docs](https://openrouter.ai/docs) |
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
