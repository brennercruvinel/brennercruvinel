# Independent Researcher 

I transform complex problems into elegant products. Make it simple, but significant!

--------
[![urna](https://raw.githubusercontent.com/hoffresearch/urna/v0.5.4/assets/image/urna-hoff-research-db-iage-thumb-git.png)](https://github.com/hoffresearch/urna)

# urna

One `.urna` file carries chunks, embeddings, source spans, HNSW and BM25 indices, and a search contract. Hash-verified, memory-mapped, reproducible, offline.

Python builds. Rust serves. Urna ships. Agents/LLMs read, that's it.

It has its own binary format and an mmap runtime with AVX2/NEON dispatch. HNSW and BM25 only pick candidates, every hit gets an exact cosine rerank, and storage goes down to int4 with FSST for the text ([the crates](https://github.com/hoffresearch/urna/tree/v0.5.4/crates)).

I packed [38k Magic card scans](https://github.com/brennercruvinel/mtg-urna-benchmark) into single-file corpora to find where compression starts breaking search. 4 GB of JPEG went down to 533 MB, and search survives a lot more compression than the eye does. The text side is [pt-BR fake news](https://github.com/brennercruvinel/fakenews-ptbr-urna-benchmark), searched with real queries.

```
npm install -g @urna/cli
```

```
cargo install urna
```

It was called nest until v0.4.0, and a `.nest` from back then still opens.

# plev

[plev](https://github.com/brennercruvinel/plev) is an experimental GPU-first compositing engine in Rust. One codebase draws the same pixel-identical frame on every target: macOS and iOS on Metal, the browser on WebGPU, Android on Vulkan.

The scene is rebuilt every frame and the compositor resolves only the layers that changed, so no change means no frame. Glass, backdrop blur, analytic shadows, real text shaping, HiDPI at native scale.

I started it six years ago as the engine for a children's education app for my daughter, all Rust. Today it also ships the urna explorer GUI (`crates/urnaui`), and the children's app is next.

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

Brenner Cruvinel, [Hoff Research](https://hoffresearch.com)
