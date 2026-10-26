# Awesome Voice AI

**A reading list for people building conversations with a voice.**

Speech synthesis, recognition, conversation frameworks, datasets, memory and research. Maintained by [Mirror AI](https://github.com/Mirror-Corporation).

Entries link to the projects' own pages. Inclusion does not identify Mirror's suppliers or imply an endorsement. Descriptions are intentionally factual; availability and licences can change.

[Speech synthesis](#speech-synthesis) · [Recognition](#speech-recognition) · [Agents](#conversation-frameworks-and-platforms) · [Datasets](#datasets) · [Memory](#memory-and-retrieval) · [Research](#research) · [Safety](#ethics-and-provenance)

> **Link checks:** see [the per-link report](./LINK_CHECK.md). “Not verified” means the checker could not establish the destination's content; it does not mean the link is broken.

## Speech synthesis

Text-to-speech (TTS) turns text into spoken audio.

| Project | What to explore |
| :--- | :--- |
| [ElevenLabs](https://elevenlabs.io/) | Speech synthesis and voice tools. |
| [PlayHT](https://play.ht/) | Hosted speech synthesis. **Not verified:** the check returned a gateway error. |
| [Cartesia](https://www.cartesia.ai/sonic) | Sonic speech synthesis. |
| [Coqui TTS](https://github.com/coqui-ai/TTS) | A speech synthesis toolkit; check the repository's maintenance status and licence. |
| [XTTS-v2](https://huggingface.co/coqui/XTTS-v2) | A multilingual speech model; review the model licence before use. |
| [F5-TTS](https://github.com/SWivid/F5-TTS) | Speech synthesis based on flow matching. |
| [OpenVoice](https://github.com/myshell-ai/OpenVoice) | Voice conversion and style control. |

## Speech recognition

Automatic speech recognition (ASR) turns audio into text.

| Project | What to explore |
| :--- | :--- |
| [Whisper](https://github.com/openai/whisper) | Speech recognition models and reference implementation. |
| [whisper.cpp](https://github.com/ggml-org/whisper.cpp) | A C/C++ implementation of Whisper. |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | Whisper inference using CTranslate2. |
| [Distil-Whisper](https://github.com/huggingface/distil-whisper) | Distilled speech recognition models. |
| [Deepgram](https://deepgram.com/) | Hosted speech recognition. |
| [AssemblyAI](https://www.assemblyai.com/) | Speech recognition and audio analysis. |

## Conversation frameworks and platforms

| Project | What to explore |
| :--- | :--- |
| [LiveKit Agents](https://docs.livekit.io/agents/) | A framework for real-time agents. |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | A framework for voice and multimodal conversation. |
| [Daily](https://www.daily.co/) | Real-time communication tools and the team behind Pipecat. |
| [Vapi](https://vapi.ai/) | A hosted voice agent platform. |
| [Retell AI](https://www.retellai.com/) | A platform for voice agents and phone conversations. |
| [Bland AI](https://www.bland.ai/) | A platform for phone-based AI agents. |

## Datasets

Check the source's terms and the rights associated with the recordings before using a dataset.

| Dataset | Material |
| :--- | :--- |
| [LibriTTS](https://www.openslr.org/60/) | Audiobook speech for synthesis research. |
| [Common Voice](https://commonvoice.mozilla.org/) | Contributed speech recordings. **Not verified:** only a JavaScript shell was readable. |
| [VoxCeleb](https://www.robots.ox.ac.uk/~vgg/data/voxceleb/) | Speech data for speaker recognition research. |
| [VCTK](https://datashare.ed.ac.uk/items/30e7453c-9ea8-48b4-8e18-f96d0dc62928) | A corpus of speakers reading text. |
| [LJ Speech](https://keithito.com/LJ-Speech-Dataset/) | A speech corpus with transcripts. |

## Voice and audio products

| Product | What to explore |
| :--- | :--- |
| [Mirror AI](https://mirror-ai.app) | Our product: historical personalities as AI reconstructions, real-time voice, free letters and memory. Characters speak Russian and can make mistakes. |
| [Suno](https://suno.com/) | Music generation with vocals. |
| [Udio](https://www.udio.com/) | Music generation. **Not verified:** no readable page content was returned. |
| [Pi](https://pi.ai/) | A conversational assistant. **Not verified:** the destination returned a minimal interface; voice availability was not established. |

## Memory and retrieval

These are general tools that can support a conversational application.

- [Mem0](https://github.com/mem0ai/mem0) — memory for AI applications.
- [Zep](https://github.com/getzep/zep) — context and memory tools.
- [LangMem](https://github.com/langchain-ai/langmem) — tools for long-term memory.
- [Chroma](https://www.trychroma.com/) — embeddings and retrieval.
- [LanceDB](https://www.lancedb.com/) — vector search and data storage.

## Research

Foundational reading, rather than a ranking of current systems. Links go to the authors' papers.

- [NaturalSpeech 3](https://arxiv.org/abs/2403.03100) — speech synthesis with a factorized codec and diffusion.
- [StyleTTS 2](https://arxiv.org/abs/2306.07691) — style diffusion for speech synthesis.
- [Voicebox](https://arxiv.org/abs/2306.15687) — text-guided speech generation.
- [AudioLM](https://arxiv.org/abs/2209.03143) — language modelling for audio generation.
- [NaturalSpeech 2](https://arxiv.org/abs/2304.09116) — latent diffusion for speech and singing synthesis.
- [SoundStream](https://arxiv.org/abs/2107.03312) — a neural audio codec.

## Ethics and provenance

- [Partnership on AI — Responsible Practices for Synthetic Media](https://syntheticmedia.partnershiponai.org/) — guidance on consent, disclosure and transparency.
- [C2PA](https://c2pa.org/) — content provenance specifications.
- [DeepMedia](https://www.deepmedia.ai/) — synthetic media detection. **Not verified:** the checker could not read the site.
- [Mirror Manifesto](https://github.com/Mirror-Corporation/manifesto) — our approach to research, reconstruction and honest limits.

## Communities

- [Hugging Face Audio](https://huggingface.co/audio) — **not verified** by the checker.
- [LAION Discord](https://discord.gg/laion) — **not verified** by the checker.
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) — discussion of local models, including audio projects.

## Contributing

Suggest a project with an official source and a short explanation of its relevance to voice. Disclose your affiliation. Avoid rankings, unsupported performance numbers and claims about which services Mirror uses.

[Mirror on GitHub →](https://github.com/Mirror-Corporation) · [Open Mirror AI](https://mirror-ai.app/app/)
