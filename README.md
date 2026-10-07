# Independent Researcher 

I transform complex problems into elegant products. Make it simple, but significant!

--------
[![urna](https://raw.githubusercontent.com/hoffresearch/urna/main/docs/img/urna-tui.svg)](https://github.com/hoffresearch/urna)

# urna

Portable binary vector db that fits in your pocket.

A `.urna` file keeps embeddings, HNSW/BM25 indexes and the search contract together. The Rust runtime memory maps it, checks its hashes and reranks every candidate with exact cosine similarity. The CLI and TUI keep things simple: `build`, `ask`, `retrieve`.

Made for those tired of yet another cloud database service.

No ambition to become a cloud service or compete with mature projects like Qdrant or Chroma. My focus is exact cosine scores, byte-for-byte contract validation, compression, portability and verifiable retrieval without depending on cloud infrastructure.

Experiments: [pt-BR fact-check retrieval](https://github.com/brennercruvinel/fakenews-ptbr-urna-benchmark) · [38k Magic cards compressed with AV1](https://github.com/brennercruvinel/mtg-urna-benchmark)

`npm install -g @urna/cli` 

`cargo install urna`

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
