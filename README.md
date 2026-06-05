<h1 align="center">Guillain d'Erceville</h1>

<p align="center"><strong>I build production AI that ships and bills — and I publish my dead-ends, not just my wins.</strong></p>

<p align="center">⸻ ❦ ⸻</p>

Today I'm the sole engineer behind a legal-grade transcription platform: a Whisper + Claude LLM pipeline with anti-hallucination guardrails and a daily quality loop, sitting on a nine-server fleet with the whole money chain wired in — invoicing, SEPA, dunning, reconciliation, fraud detection. Production, on-call, real invoices. Not slideware.

That instinct came from somewhere harder. Before this I built and ran a fully systematic global-macro fund — I engineered the entire trading stack myself and took monthly volume from under $100M to more than $9B, on a low-latency FIX path I wired to LMAX in London. And before *that*, ~10 years reverse-engineering protocols and protections for the paid security press — the same byte-level reflexes I still point at locked file formats today.

Between the production systems, I build smaller, more stubborn things — tools that preserve, decode, and keep working when the comfortable infrastructure is gone. One quiet thread runs through all of it: **give people back what was faked, locked, abandoned, or lost.**

### What I'm building

- **[DS2-Anywhere](https://github.com/Guillain-RDCDE/DS2-Anywhere)** — a production integration recipe for the Olympus DS2/DSS dictation format, locked for ten years. I wired an open reverse-engineered Rust decoder into a clean CLI + Docker pipeline — green CI, MIT, 11-chapter docs — that retired a paid license and a Windows-VM chain in production. I'm now driving the decoder upstream into FFmpeg — validation, FATE tests, sample sourcing and the ffmpeg-devel submission — closing ticket #6091, open since 2017.
- **[FLAC Detective](https://github.com/Guillain-RDCDE/FLAC_Detective)** — catches MP3s smuggled into lossless files. The interesting part is the honest [ML write-up](https://github.com/Guillain-RDCDE/FLAC_Detective/blob/main/ml/README.md): four approaches that failed, a self-caught "AUC 0.99" false discovery that cross-validation killed, and a "fundamental limit" that turned out to be me listening in mono.
- **[Prometheus-Station](https://github.com/Guillain-RDCDE/Prometheus-Station)** — a solar-powered Raspberry Pi serving offline Wikipedia over a long-range LoRa mesh. For when the grid and the network aren't there.
- **[HAP-Revival](https://github.com/Guillain-RDCDE/HAP-Revival)** — keeping Sony's HAP-Z1ES / HAP-S1 audiophile players alive after Sony walked away in 2021.
- **[Creabook](https://github.com/Guillain-RDCDE/Creabook)** — a book-generation engine, for when the pen tires before the idea does.

### How I work

Production-first, honest about uncertainty, allergic to cleverness that doesn't survive testing. I read FIX logs and Pascal with about equal pleasure.

### Working together

I take on a small number of contract and consulting engagements — systems that have to *work*, not just demo:

- production LLM / Whisper pipelines — anti-hallucination, quality loops, and the infra and billing around them (the part most people skip)
- file-format and legacy reverse-engineering
- trading & market-data plumbing (FIX, low-latency, backtest-to-production)
- resilient / offline-first infrastructure

If that's your kind of problem → **guillain@poulpe.us**

<p align="center">⸻</p>

<p align="center"><sub>Français de naissance · anglais & espagnol courants · quelques mots de basque</sub></p>

<p align="center"><sub><strong>guillain@poulpe.us</strong> · writing from somewhere near Venice</sub></p>
