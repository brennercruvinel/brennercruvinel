**Systems engineer (Rust/Python)** — built [nest](https://github.com/hoffresearch/nest), an embedded vector database. Previously Head of Product Design at [Zenklub](https://zenklub.com.br/).

# nest

<a href="https://github.com/hoffresearch/nest" target="_blank"><img src="https://raw.githubusercontent.com/hoffresearch/nest/bbad86c51ae92937deca03948553b2fb9500683b/doc/nest-hoff-research-db.png" alt="nest"></a>

**[hoffresearch/nest](https://github.com/hoffresearch/nest)** — sovereign embedded vector database. one `.nest` file carries chunks, embeddings, source spans, HNSW and BM25 indices, and a search contract. hash-verified, memory-mapped, reproducible, offline.

python builds. rust serves. nest ships. agents/llms read, that's it.

- **21k lines of Rust, 346 tests.** Principal author: 100 of 104 commits (`git shortlog -sn`).
- **Own binary format** ([`nest-format`](https://github.com/hoffresearch/nest/tree/main/crates/nest-format)), mmap runtime, [SIMD dispatch (AVX2/NEON)](https://github.com/hoffresearch/nest/tree/main/crates/nest-runtime/src/simd), HNSW + BM25 with a mandatory exact-cosine rerank.
- **ML in practice:** [int4 quantization](https://github.com/hoffresearch/nest/blob/main/crates/nest-runtime/src/dtype.rs) of stored embeddings and [FSST compression](https://github.com/hoffresearch/nest/blob/main/crates/nest-format/src/encoding/fsst_table.rs) of text streams.
- [Hoff Research](https://hoffresearch.com) is my own org for AI + mental-health work; nest is its retrieval layer, which is why it lives there and not under my handle.

![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Semantic Search](https://img.shields.io/badge/Semantic%20Search-00A98F?style=flat-square&logo=meilisearch&logoColor=white)
![Compression](https://img.shields.io/badge/Compression-8E44AD?style=flat-square&logo=apachekafka&logoColor=white)
![Product Design](https://img.shields.io/badge/Product%20Design-F24E1E?style=flat-square&logo=figma&logoColor=white)
![VUI / STT / TTS](https://img.shields.io/badge/STT%20%2F%20TTS-4285F4?style=flat-square&logo=googleassistant&logoColor=white)
![Mental Health](https://img.shields.io/badge/Mental%20Health-00C7B7?style=flat-square&logo=iheartradio&logoColor=white)

# Product work

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank">CryptoControl</a>
Led product for V2 of Latin America's largest cryptocurrency portfolio management platform. Took over a weak MVP and shipped AI-powered analytics and trading tools for professional investors.

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/crypto.png" alt="CryptoControl"></a>

Flashed - AI Learning Platform
CPO and product design lead, alongside <a href="https://apps.apple.com/us/developer/bernardo-rodrigues/id1702056610" target="_blank">Bernardo Rodrigues</a>, who developed and published the app. Built the design system and the UI for every interface. AI-powered study assistant for Gen Z students that adapts content to how each user learns best: video, images, diagrams, or interactive questions. The store listings were taken down in 2026.

<img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/flashed.png" alt="Flashed AI Assistant">

<a href="https://www.amazon.com.br/Porto-Seguro-Reppara-Casa/dp/B09V88BJGP" target="_blank">Alexa Skill - Porto Seguro "Reppara! Casa"</a>
Led the Voice / AI squad (voice UX designers, UX writers, product designers) for Latin America's largest insurer. Users request plumbing, electrical, and maintenance services through natural conversation. Amazon-certified and published on the Alexa Skills Store.

<a href="https://www.amazon.com.br/Porto-Seguro-Reppara-Casa/dp/B09V88BJGP" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/porto.png" alt="Alexa Skill Porto Seguro"></a>

<a href="https://www.amazon.com.br/dp/B0BBP49XM3" target="_blank">Alexa Skill - Zenklub Mental Health</a>
Created the concept and led the team building a voice interface for mental health support: guided meditations, anxiety management tools, and voice-activated appointment scheduling with licensed therapists. Published on the Alexa Skills Store.

<a href="https://www.amazon.com.br/dp/B0BBP49XM3" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/zenklub.png" alt="Alexa Skill Zenklub"></a>

<a href="https://zenklub.com.br/site/para-voce" target="_blank">Clari AI - Zenklub Assistant</a>
Started and led this AI project from zero. Built the MVP for matching patients with therapists using behavioral profiling, then added nutritional counseling with photo analysis, emotional support, and CBT techniques. Flags severe cases for immediate care. Integrated across all platform services.

<a href="https://zenklub.com.br/site/para-voce" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/clari.png" alt="Clari Mental Health Assistant"></a>

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank">Hash - Design System</a>
As Product Design Specialist, built the complete design system for the cryptocurrency platform: 70+ components, WCAG 2.1 AA throughout, Figma documentation and a Next.js component library. Led the front-end implementation and handoff.

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/hash.png" alt="Hash Design System"></a>
