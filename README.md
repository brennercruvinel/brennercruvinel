# Independent Researcher 

I transform complex problems into elegant products. Make it simple, but significant!

--------
[![urna](https://raw.githubusercontent.com/hoffresearch/urna/main/docs/img/urna-tui.svg)](https://github.com/hoffresearch/urna)

# urna

A vector db you can carry around as a binary file.

A `.urna` file packs embeddings, HNSW/BM25 indexes and the contract needed to verify and search them. The Rust runtime uses `mmap`, SHA checks and native AVX2/NEON dispatch. HNSW and BM25 find candidates, then every hit gets an exact cosine rerank.

The CLI and TUI are intentionally small: `build`, `ask`, `retrieve`.

Urna isn't meant to become a cloud service or another general purpose database, much less compete with mature projects like Qdrant or Chroma. It's just my small retrieval lab, focused on exactness, compression, binary formats, and keeping the database useful wherever the file goes.

**Experiments**

[Fact-check](https://github.com/brennercruvinel/fakenews-ptbr-urna-benchmark), 7 public pt-BR datasets deduplicated into 23k documents, with 2.6k queries for retrieval evaluation. [Hugging Face](https://huggingface.co/datasets/brennercruvinel/fakenews-ptbr-urna-benchmark)

[Image compression](https://github.com/brennercruvinel/mtg-urna-benchmark), 38k Magic cards packed using AV1. [Hugging Face](https://huggingface.co/datasets/brennercruvinel/mtg-urna-benchmark)

If you're into retrieval, compression, binary formats or compilers, feel free to contribute.

## Install

```bash
npm install -g @urna/cli
# or
cargo install urna
```

<!--
![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Semantic Search](https://img.shields.io/badge/Semantic%20Search-00A98F?style=flat-square&logo=meilisearch&logoColor=white)
![Compression](https://img.shields.io/badge/Compression-8E44AD?style=flat-square&logo=apachekafka&logoColor=white)
![Product Design](https://img.shields.io/badge/Product%20Design-F24E1E?style=flat-square&logo=figma&logoColor=white)
![VUI / STT / TTS](https://img.shields.io/badge/STT%20%2F%20TTS-4285F4?style=flat-square&logo=googleassistant&logoColor=white)
![Mental Health](https://img.shields.io/badge/Mental%20Health-00C7B7?style=flat-square&logo=iheartradio&logoColor=white)

[Cryptocontrol](https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1)\
V2 of a crypto portfolio manager for professional investors in LatAm. I took over a weak MVP and shipped analytics and trading tools on top of it.

[![cryptocontrol](https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/crypto.png)](https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1)

Flashed\
Study app for Gen Z that adapts content to how each student learns (video, image, diagram, quiz). I was CPO and did the design system and all the UI, and [Bernardo Rodrigues](https://apps.apple.com/us/developer/bernardo-rodrigues/id1702056610) built and published it. The store listings came down in 2026.

![flashed](https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/flashed.png)

[Alexa skill, Porto Seguro "Reppara! Casa"](https://www.amazon.com.br/Porto-Seguro-Reppara-Casa/dp/B09V88BJGP)\
Ask Alexa for a plumber or an electrician through your home insurance. I ran the voice squad (VUX designers, UX writers, PDs) at the largest insurer in LatAm.

[![alexa skill porto seguro](https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/porto.png)](https://www.amazon.com.br/Porto-Seguro-Reppara-Casa/dp/B09V88BJGP)

[Alexa skill, Zenklub](https://www.amazon.com.br/dp/B0BBP49XM3)\
Guided meditation, anxiety tools and booking a therapist by voice. My concept, and I led the team.

[![alexa skill zenklub](https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/zenklub.png)](https://www.amazon.com.br/dp/B0BBP49XM3)

[Clari, Zenklub assistant](https://zenklub.com.br/site/para-voce)\
I started it from zero. It matches patients to therapists by behavioral profile and flags severe cases for immediate care. Later it got nutrition (photo analysis), emotional support and CBT exercises, wired into every Zenklub service.

[![clari](https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/clari.png)](https://zenklub.com.br/site/para-voce)

[Hash design system](https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1)\
70+ components, WCAG 2.1 AA, documented in Figma and implemented in Next.js. I built it and led the front-end on the handoff.

[![hash design system](https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/hash.png)](https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1)
-->

Brenner Cruvinel, [Hoff Research](https://hoffresearch.com)
