# I transform `complex problems` into `elegant products`

**`AI Researcher`** Building something new in stealth mode (AI + Mental Health)

**`Previously`** Led Brazil’s largest digital health platforms [(Zenklub/Conexa)](https://zenklub.com.br/busca/)

**`Philosophy`** Make it simple, but significant

# nest

<a href="https://github.com/hoffresearch/nest" target="_blank"><img src="https://raw.githubusercontent.com/hoffresearch/nest/bbad86c51ae92937deca03948553b2fb9500683b/doc/nest-hoff-research-db.png" alt="nest"></a>

one `.nest` file carries chunks, embeddings, source spans, hnsw and bm25 indices, and a search contract. hash-verified, mmap'd, reproducible, offline.

python builds. rust serves. nest ships. agents/llms read, that's it.

own binary format in [nest-format](https://github.com/hoffresearch/nest/tree/main/crates/nest-format). mmap runtime with [avx2/neon dispatch](https://github.com/hoffresearch/nest/tree/main/crates/nest-runtime/src/simd). hnsw and bm25 as candidate generators, exact cosine rerank always. int4 storage in [dtype.rs](https://github.com/hoffresearch/nest/blob/main/crates/nest-runtime/src/dtype.rs), fsst text compression in [fsst_table.rs](https://github.com/hoffresearch/nest/blob/main/crates/nest-format/src/encoding/fsst_table.rs).

[hoff research](https://hoffresearch.com) is my org for ai + mental health. nest is the retrieval layer, so it lives there.

![Rust](https://img.shields.io/badge/Rust-DEA584?style=flat-square&logo=rust&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Semantic Search](https://img.shields.io/badge/Semantic%20Search-00A98F?style=flat-square&logo=meilisearch&logoColor=white)
![Compression](https://img.shields.io/badge/Compression-8E44AD?style=flat-square&logo=apachekafka&logoColor=white)
![Product Design](https://img.shields.io/badge/Product%20Design-F24E1E?style=flat-square&logo=figma&logoColor=white)
![VUI / STT / TTS](https://img.shields.io/badge/STT%20%2F%20TTS-4285F4?style=flat-square&logo=googleassistant&logoColor=white)
![Mental Health](https://img.shields.io/badge/Mental%20Health-00C7B7?style=flat-square&logo=iheartradio&logoColor=white)

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank">cryptocontrol</a>
v2 of a crypto portfolio manager for professional investors in latam. took over a weak mvp, shipped analytics and trading tools on top of it.

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/crypto.png" alt="cryptocontrol"></a>

flashed
study app for gen z, adapts content to how each student learns (video, image, diagram, quiz). i was cpo and did the design system and all the ui. <a href="https://apps.apple.com/us/developer/bernardo-rodrigues/id1702056610" target="_blank">bernardo rodrigues</a> built and published it. the store listings came down in 2026.

<img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/flashed.png" alt="flashed">

<a href="https://www.amazon.com.br/Porto-Seguro-Reppara-Casa/dp/B09V88BJGP" target="_blank">alexa skill, porto seguro "reppara! casa"</a>
ask alexa for a plumber or an electrician through your home insurance. i ran the voice squad (vux designers, ux writers, pds) for the largest insurer in latam. on the alexa store.

<a href="https://www.amazon.com.br/Porto-Seguro-Reppara-Casa/dp/B09V88BJGP" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/porto.png" alt="alexa skill porto seguro"></a>

<a href="https://www.amazon.com.br/dp/B0BBP49XM3" target="_blank">alexa skill, zenklub</a>
guided meditation, anxiety tools, booking a therapist by voice. my concept, i led the team. on the alexa store.

<a href="https://www.amazon.com.br/dp/B0BBP49XM3" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/zenklub.png" alt="alexa skill zenklub"></a>

<a href="https://zenklub.com.br/site/para-voce" target="_blank">clari, zenklub assistant</a>
started it from zero. matches patients to therapists by behavioral profile, flags severe cases for immediate care. later got nutrition (photo analysis), emotional support and cbt exercises. wired into every zenklub service.

<a href="https://zenklub.com.br/site/para-voce" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/clari.png" alt="clari"></a>

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank">hash design system</a>
70+ components, wcag 2.1 aa, documented in figma, implemented in next.js. i built it and led the front-end on the handoff.

<a href="https://www.figma.com/design/USx5XDTlpPsabJSZoyWLYV/Hash-Design-System---Cryptocontrol-V1?node-id=553-14956&t=iE4gYUPCSrXTR94X-1" target="_blank"><img src="https://raw.githubusercontent.com/brennercruvinel/brennercruvinel/main/hash.png" alt="hash design system"></a>
