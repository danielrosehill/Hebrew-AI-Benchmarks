[![Master Index](https://img.shields.io/badge/Master_Index-GitHub-blue?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Start-Here) [![Index of Indexes](https://img.shields.io/badge/Index_of_Indexes-Subindices-FF6B6B?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Subindices)

# Hebrew AI Benchmarks

Benchmarks, evaluation sets and leaderboards for AI in modern Hebrew: LLMs, speech recognition, text-to-speech, OCR, retrieval and translation.

Part of the [Hebrew AI](https://github.com/danielrosehill/Hebrew-AI) index. Models are catalogued in [Hebrew-AI-Models](https://github.com/danielrosehill/Hebrew-AI-Models), datasets in [Hebrew-Datasets](https://github.com/danielrosehill/Hebrew-Datasets), people and organisations in [Hebrew-AI-Community](https://github.com/danielrosehill/Hebrew-AI-Community). Scope: [SCOPE.md](SCOPE.md).

Entries marked † are maintained by the curator of this list.

**Last updated:** November 18, 2026

---

## LLMs and Language Understanding

| Benchmark | Kind | Maintainer | Description |
|-----------|------|------------|-------------|
| [Open Hebrew LLM Leaderboard](https://huggingface.co/spaces/hebrew-llm-leaderboard/leaderboard) ([paper](https://arxiv.org/abs/2407.07080)) | Leaderboard | hebrew-llm-leaderboard | Ranks open LLMs on Hebrew NLI, HeQ question answering, sentiment, Winograd, he→en translation and Israeli trivia |
| [Hebrew Chat Leaderboard V2](https://huggingface.co/spaces/hebrew-llm-leaderboard/chat-leaderboard) | Leaderboard | hebrew-llm-leaderboard | Rankings of chat models in Hebrew; results in [chat-results](https://huggingface.co/datasets/hebrew-llm-leaderboard/chat-results) |
| [AlephBench](https://huggingface.co/datasets/HebArabNlpProject/AlephBench) | Eval suite | HebArabNlpProject | 11-task Hebrew LLM benchmark with frozen prompts and per-row outputs: reasoning, classification, QA, math, translation, Israeli trivia |
| [HeQ](https://github.com/NNLP-IL/Hebrew-Question-Answering-Dataset) ([paper](https://arxiv.org/abs/2508.01812)) | Dataset | NNLP-IL | SQuAD-style Hebrew question answering over Hebrew Wikipedia and Geektime paragraphs, about 30k questions |
| [ParaShoot](https://github.com/omrikeren/ParaShoot) ([paper](https://arxiv.org/abs/2109.11314)) | Dataset | Keren and Levy | Few-shot SQuAD-style Hebrew QA, a few thousand crowd-annotated pairs from Wikipedia |
| [HeSum](https://huggingface.co/datasets/biunlp/HeSum) ([paper](https://arxiv.org/abs/2406.03897)) | Dataset | biunlp (Bar-Ilan) | Abstractive Hebrew summarisation, about 10k article–summary pairs |
| [HebNLI](https://huggingface.co/datasets/HebArabNlpProject/HebNLI) | Dataset | HebArabNlpProject | Hebrew natural language inference (entailment, contradiction, neutral) |
| [LCHAIM](https://huggingface.co/datasets/HebArabNlpProject/LCHAIM) ([paper](https://aclanthology.org/2025.findings-acl.413/)) | Dataset | HebArabNlpProject | 8,325 long-premise Hebrew NLI pairs testing coreferential, temporal, logical and analytical reasoning |
| [Hebrew Sentiment](https://huggingface.co/datasets/HebArabNlpProject/HebrewSentiment) | Dataset | HebArabNlpProject | Hebrew sentiment classification; the sentiment task of the Open Hebrew LLM Leaderboard |
| [Abstractive QA for LLM Evaluation](https://huggingface.co/datasets/HebArabNlpProject/abstractive-qa-llm-eval) | Dataset | HebArabNlpProject | 132 Hebrew QA records with claim-level source spans, for testing grounding and hallucination |
| [Hebrew Coreference Benchmark](https://arxiv.org/abs/2604.17108) | Paper | See paper | "Beyond Word Boundaries": a Hebrew coreference benchmark and evaluation protocol for morphologically complex text |
| [HeRE](https://github.com/Ronke21/HeRE) ([paper](https://arxiv.org/abs/2610.22542)) | Dataset | Ronke21 | Hebrew relation-extraction benchmark from LLM-denoised Wikidata–Wikipedia alignments |
| [RabBench](https://github.com/BobYeger/rabbench) | Dataset | BobYeger | Hebrew rabbinical-knowledge benchmark from Chief Rabbinate exam questions |
| [HebJudge](https://github.com/chagitmi/HebJudge) | Eval suite | chagitmi | Hebrew evaluation of LLM agents for prompt injection and data leakage, with a calibrated LLM-as-judge |
| [Hebrew LLM Eval Suite](https://github.com/peleg-jpg/hebrew-llm-eval-suite) | Eval suite | peleg-jpg | Runner comparing LLMs on Hebrew reasoning, comprehension, sentiment, translation and Israeli cultural knowledge |

## Speech Recognition

| Benchmark | Kind | Maintainer | Description |
|-----------|------|------------|-------------|
| [Hebrew Transcription Leaderboard](https://huggingface.co/spaces/ivrit-ai/hebrew-transcription-leaderboard) | Leaderboard | ivrit-ai | Hebrew speech-to-text models scored on ivrit.ai evaluation sets |
| [ivrit.ai eval sets](https://huggingface.co/datasets/ivrit-ai/eval-d1) | Dataset | ivrit-ai | Held-out Hebrew audio–text sets: [eval-d1](https://huggingface.co/datasets/ivrit-ai/eval-d1), [eval-whatsapp](https://huggingface.co/datasets/ivrit-ai/eval-whatsapp), [eval-forced-alignment](https://huggingface.co/datasets/ivrit-ai/eval-forced-alignment) |
| [Daf Yomi Hebrew Transcription Leaderboard](https://huggingface.co/spaces/portal-daf-yomi/daf-yomi-hebrew-trancription-leaderboard) | Leaderboard | portal-daf-yomi | Speech recognition on Hebrew Talmud lessons |
| [VoxKnesset](https://huggingface.co/datasets/ivrit-ai/VoxKnesset) ([paper](https://arxiv.org/abs/2603.01270)) | Dataset | ivrit-ai | Hebrew parliamentary speech (66.7k rows) for longitudinal speaker modelling |
| [English-Hebrew Code-Switching ASR Benchmark](https://huggingface.co/datasets/Hebrish/English-Hebrew-Codeswitching-ASR-Benchmark) † | Dataset | Hebrish | Frozen test set of 324 clips of English speech containing Hebrew words |
| [English-Hebrew Code-Switching ASR Leaderboard](https://huggingface.co/spaces/danielrosehill/English-Hebrew-Codeswitching-ASR-Leaderboard) † | Leaderboard | danielrosehill | ASR models ranked on English speech containing Hebrew words |

## Text-to-Speech

| Benchmark | Kind | Maintainer | Description |
|-----------|------|------------|-------------|
| [TTS Arena Hebrew](https://huggingface.co/spaces/ivrit-ai/TTS-Arena-Hebrew) | Leaderboard | ivrit-ai | Blind-vote arena for Hebrew TTS; votes in [tts-arena-preferences](https://huggingface.co/datasets/ivrit-ai/tts-arena-preferences) |
| [heb-tts-benchmark](https://github.com/phonikud/heb-tts-benchmark) ([paper](https://arxiv.org/abs/2506.12311)) | Eval suite | phonikud | Scores Hebrew TTS by transcribing output to IPA and comparing with hand-annotated IPA for 100 SASPEECH samples |
| [Hebrew TTS Eval Set](https://huggingface.co/datasets/Hebrish/Hebrew-TTS-Eval-Set) † | Dataset | Hebrish | 20 Hebrew sentences for TTS evaluation; side-by-side comparison in the [Bake-off 11/26 Space](https://huggingface.co/spaces/Hebrish/Hebrew-TTS-Bakeoff-1126) |

## OCR and Handwriting

| Benchmark | Kind | Maintainer | Description |
|-----------|------|------------|-------------|
| [Hebrew Handwriting OCR Leaderboard](https://huggingface.co/spaces/ivrit-ai/hebrew-handwriting-ocr-leaderboard) | Leaderboard | ivrit-ai | Ranks models on reading Hebrew handwriting, line-by-line and full page |
| [Hebrew Handwriting OCR Benchmark](https://huggingface.co/datasets/ivrit-ai/hebrew-handwriting-ocr-benchmark) | Dataset | ivrit-ai | 235 Hebrew handwriting image–text pairs, the test set behind the leaderboard |

## Embeddings and Retrieval

| Benchmark | Kind | Maintainer | Description |
|-----------|------|------------|-------------|
| [Hebrew Semantic Retrieval Challenge](https://www.codabench.org/competitions/9950/) | Leaderboard | Codabench competition | Hebrew-only semantic retrieval challenge scored by NDCG@20; used in the [NeoDictaBERT paper](https://arxiv.org/abs/2510.20386) |
| [hebrew-embedding-benchmark](https://github.com/odedia/hebrew-embedding-benchmark) | Eval suite | odedia | Open-weight embedding models compared on Hebrew retrieval over Kol-Zchut data |
| [BEIR-he](https://huggingface.co/datasets/biunlp/beir-he-nq) | Dataset | biunlp (Bar-Ilan) | Hebrew versions of BEIR retrieval sets (NQ and others) |

## Translation

| Benchmark | Kind | Maintainer | Description |
|-----------|------|------------|-------------|
| [MTQE.en-he](https://arxiv.org/abs/2602.06546) | Paper | See paper | English→Hebrew machine translation quality estimation: WMT24++ segments with expert Direct Assessment scores |

---

## Multilingual Benchmarks with a Hebrew Split

Not Hebrew benchmarks, but their Hebrew portion is a common reference point.

| Benchmark | Task | Hebrew config | Description |
|-----------|------|---------------|-------------|
| [FLEURS](https://huggingface.co/datasets/google/fleurs) | Speech recognition | `he_il` | Multilingual read-speech benchmark |
| [Belebele](https://huggingface.co/datasets/facebook/belebele) | Reading comprehension | `heb_Hebr` | Multiple-choice reading comprehension in 100+ languages |
| [Global-MMLU](https://huggingface.co/datasets/CohereLabs/Global-MMLU) | Knowledge | `he` | MMLU translated into many languages |
| [MTEB / MMTEB](https://huggingface.co/spaces/mteb/leaderboard) ([paper](https://arxiv.org/abs/2502.13595)) | Embeddings | Hebrew tasks, e.g. [HebrewSentimentAnalysisV4](https://huggingface.co/datasets/mteb/HebrewSentimentAnalysisV4) | Multilingual embedding leaderboard; no Hebrew-only board |

---

## Contributing

Maintained on a best-effort basis by [Daniel Rosehill](https://github.com/danielrosehill). To be included, or to send a correction, open a pull request or email public@danielrosehill.com.

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
