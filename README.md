[![Master Index](https://img.shields.io/badge/Master_Index-GitHub-blue?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Start-Here) [![Index of Indexes](https://img.shields.io/badge/Index_of_Indexes-Subindices-FF6B6B?style=for-the-badge&logo=github)](https://github.com/danielrosehill/Subindices)

# Hebrew AI Benchmarks

Benchmarks, evaluation sets and leaderboards for AI in modern Hebrew: LLMs, speech recognition, text-to-speech, OCR, retrieval and translation.

Part of the [Hebrew AI](https://github.com/danielrosehill/Hebrew-AI) index. Models are catalogued in [Hebrew-AI-Models](https://github.com/danielrosehill/Hebrew-AI-Models), datasets in [Hebrew-Datasets](https://github.com/danielrosehill/Hebrew-Datasets), people and organisations in [Hebrew-AI-Community](https://github.com/danielrosehill/Hebrew-AI-Community). Scope: [SCOPE.md](SCOPE.md).

Entries marked † are maintained by the curator of this list.

**Last updated:** November 18, 2026

---

## Embeddings and Retrieval

Hebrew retrieval challenges and embedding comparisons.

### BEIR-he

Hebrew versions of BEIR retrieval sets (NQ and others).

*Dataset · biunlp (Bar-Ilan)*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/biunlp/beir-he-nq)

---

### Hebrew Semantic Retrieval Challenge

Hebrew-only semantic retrieval challenge scored by NDCG@20; used in the [NeoDictaBERT paper](https://arxiv.org/abs/2510.20386).

*Leaderboard · Codabench competition*

[![Website](https://img.shields.io/badge/Website-555555?style=flat&logo=googlechrome)](https://www.codabench.org/competitions/9950/)

---

### hebrew-embedding-benchmark

Open-weight embedding models compared on Hebrew retrieval over Kol-Zchut data.

*Eval suite · odedia*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/odedia/hebrew-embedding-benchmark)

---

## LLMs and Language Understanding

Leaderboards, eval suites and datasets for Hebrew LLMs: question answering, inference, summarisation, sentiment, grounding and domain knowledge.

### Abstractive QA for LLM Evaluation

132 Hebrew QA records with claim-level source spans, for testing grounding and hallucination.

*Dataset · HebArabNlpProject*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/HebArabNlpProject/abstractive-qa-llm-eval)

---

### AlephBench

11-task Hebrew LLM benchmark with frozen prompts and per-row outputs: reasoning, classification, QA, math, translation, Israeli trivia.

*Eval suite · HebArabNlpProject*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/HebArabNlpProject/AlephBench)

---

### HebJudge

Hebrew evaluation of LLM agents for prompt injection and data leakage, with a calibrated LLM-as-judge.

*Eval suite · chagitmi*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/chagitmi/HebJudge)

---

### HebNLI

Hebrew natural language inference (entailment, contradiction, neutral).

*Dataset · HebArabNlpProject*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/HebArabNlpProject/HebNLI)

---

### Hebrew Chat Leaderboard V2

Rankings of chat models in Hebrew; results in [chat-results](https://huggingface.co/datasets/hebrew-llm-leaderboard/chat-results).

*Leaderboard · hebrew-llm-leaderboard*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/hebrew-llm-leaderboard/chat-leaderboard)

---

### Hebrew Coreference Benchmark

"Beyond Word Boundaries": a Hebrew coreference benchmark and evaluation protocol for morphologically complex text.

*Paper · See paper*

[![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2604.17108)

---

### Hebrew LLM Eval Suite

Runner comparing LLMs on Hebrew reasoning, comprehension, sentiment, translation and Israeli cultural knowledge.

*Eval suite · peleg-jpg*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/peleg-jpg/hebrew-llm-eval-suite)

---

### Hebrew Sentiment

Hebrew sentiment classification; the sentiment task of the Open Hebrew LLM Leaderboard.

*Dataset · HebArabNlpProject*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/HebArabNlpProject/HebrewSentiment)

---

### HeQ

SQuAD-style Hebrew question answering over Hebrew Wikipedia and Geektime paragraphs, about 30k questions.

*Dataset · NNLP-IL*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/NNLP-IL/Hebrew-Question-Answering-Dataset) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2508.01812)

---

### HeRE

Hebrew relation-extraction benchmark from LLM-denoised Wikidata–Wikipedia alignments.

*Dataset · Ronke21*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/Ronke21/HeRE) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2610.22542)

---

### HeSum

Abstractive Hebrew summarisation, about 10k article–summary pairs.

*Dataset · biunlp (Bar-Ilan)*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/biunlp/HeSum) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2406.03897)

---

### LCHAIM

8,325 long-premise Hebrew NLI pairs testing coreferential, temporal, logical and analytical reasoning.

*Dataset · HebArabNlpProject*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/HebArabNlpProject/LCHAIM) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://aclanthology.org/2025.findings-acl.413/)

---

### Open Hebrew LLM Leaderboard

Ranks open LLMs on Hebrew NLI, HeQ question answering, sentiment, Winograd, he→en translation and Israeli trivia.

*Leaderboard · hebrew-llm-leaderboard*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/hebrew-llm-leaderboard/leaderboard) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2407.07080)

---

### ParaShoot

Few-shot SQuAD-style Hebrew QA, a few thousand crowd-annotated pairs from Wikipedia.

*Dataset · Keren and Levy*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/omrikeren/ParaShoot) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2109.11314)

---

### RabBench

Hebrew rabbinical-knowledge benchmark from Chief Rabbinate exam questions.

*Dataset · BobYeger*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/BobYeger/rabbench)

---

## OCR and Handwriting

Reading printed and handwritten Hebrew from images.

### Hebrew Handwriting OCR Benchmark

235 Hebrew handwriting image–text pairs, the test set behind the leaderboard.

*Dataset · ivrit-ai*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/ivrit-ai/hebrew-handwriting-ocr-benchmark)

---

### Hebrew Handwriting OCR Leaderboard

Ranks models on reading Hebrew handwriting, line-by-line and full page.

*Leaderboard · ivrit-ai*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/ivrit-ai/hebrew-handwriting-ocr-leaderboard)

---

## Speech Recognition

Hebrew speech-to-text leaderboards and held-out evaluation sets, including English-Hebrew code-switching.

### Daf Yomi Hebrew Transcription Leaderboard

Speech recognition on Hebrew Talmud lessons.

*Leaderboard · portal-daf-yomi*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/portal-daf-yomi/daf-yomi-hebrew-trancription-leaderboard)

---

### English-Hebrew Code-Switching ASR Benchmark †

Frozen test set of 324 clips of English speech containing Hebrew words.

*Dataset · Hebrish*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/English-Hebrew-Codeswitching-ASR-Benchmark)

---

### English-Hebrew Code-Switching ASR Leaderboard †

ASR models ranked on English speech containing Hebrew words.

*Leaderboard · danielrosehill*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/danielrosehill/English-Hebrew-Codeswitching-ASR-Leaderboard)

---

### Hebrew Transcription Leaderboard

Hebrew speech-to-text models scored on ivrit.ai evaluation sets.

*Leaderboard · ivrit-ai*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/ivrit-ai/hebrew-transcription-leaderboard)

---

### ivrit.ai eval sets

Held-out Hebrew audio–text sets: [eval-d1](https://huggingface.co/datasets/ivrit-ai/eval-d1), [eval-whatsapp](https://huggingface.co/datasets/ivrit-ai/eval-whatsapp), [eval-forced-alignment](https://huggingface.co/datasets/ivrit-ai/eval-forced-alignment).

*Dataset · ivrit-ai*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/ivrit-ai/eval-d1)

---

### VoxKnesset

Hebrew parliamentary speech (66.7k rows) for longitudinal speaker modelling.

*Dataset · ivrit-ai*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/ivrit-ai/VoxKnesset) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2603.01270)

---

## Text-to-Speech

Arenas, eval sets and automatic scoring for Hebrew speech synthesis.

### heb-tts-benchmark

Scores Hebrew TTS by transcribing output to IPA and comparing with hand-annotated IPA for 100 SASPEECH samples.

*Eval suite · phonikud*

[![View Repo](https://img.shields.io/badge/View-Repo-blue?style=flat&logo=github)](https://github.com/phonikud/heb-tts-benchmark) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2506.12311)

---

### Hebrew TTS Eval Set †

20 Hebrew sentences for TTS evaluation; side-by-side comparison in the [Bake-off 11/26 Space](https://huggingface.co/spaces/Hebrish/Hebrew-TTS-Bakeoff-1126).

*Dataset · Hebrish*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/Hebrish/Hebrew-TTS-Eval-Set)

---

### TTS Arena Hebrew

Blind-vote arena for Hebrew TTS; votes in [tts-arena-preferences](https://huggingface.co/datasets/ivrit-ai/tts-arena-preferences).

*Leaderboard · ivrit-ai*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/ivrit-ai/TTS-Arena-Hebrew)

---

## Translation

Evaluation of English↔Hebrew machine translation.

### MTQE.en-he

English→Hebrew machine translation quality estimation: WMT24++ segments with expert Direct Assessment scores.

*Paper · See paper*

[![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2602.06546)

---

## Multilingual Benchmarks with a Hebrew Split

Not Hebrew benchmarks, but their Hebrew portion is a common reference point. Kept apart from the Hebrew-specific sections above.

### Belebele

Multiple-choice reading comprehension in 100+ languages.

*Reading comprehension · Hebrew config: `heb_Hebr`*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/facebook/belebele)

---

### FLEURS

Multilingual read-speech benchmark.

*Speech recognition · Hebrew config: `he_il`*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/google/fleurs)

---

### Global-MMLU

MMLU translated into many languages.

*Knowledge · Hebrew config: `he`*

[![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/CohereLabs/Global-MMLU)

---

### MTEB / MMTEB

Multilingual embedding leaderboard; no Hebrew-only board.

*Embeddings · Hebrew config: Hebrew tasks, e.g. HebrewSentimentAnalysisV4*

[![Space](https://img.shields.io/badge/Hugging_Face-Space-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/spaces/mteb/leaderboard) [![Paper](https://img.shields.io/badge/Paper-B31B1B?style=flat&logo=arxiv)](https://arxiv.org/abs/2502.13595) [![Dataset](https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&logo=huggingface)](https://huggingface.co/datasets/mteb/HebrewSentimentAnalysisV4)

---

## Contributing

Maintained on a best-effort basis by [Daniel Rosehill](https://github.com/danielrosehill). To be included, or to send a correction, open a pull request or email public@danielrosehill.com.

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
