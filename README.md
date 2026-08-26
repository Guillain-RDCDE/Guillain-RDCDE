# Guillain d'Erceville

_I take apart what's locked, and I ship what's billed._

`Whisper → LLM pipelines running unattended in production` · `a dictation codec nobody had decoded, cracked and sent to ffmpeg-devel` · `ex-$9B/mo systematic fund, built end to end`

[guillain@poulpe.us](mailto:guillain@poulpe.us) · [LinkedIn](https://www.linkedin.com/in/guillain-d-erceville) · FR / EN · remote from France

---

## What I am

Two careers that weren't supposed to coexist — and ran simultaneously for five years. Microsoft France by day: a nine-person data team, a $47M quota, the P&L of a $540M division. The paid security press by night: protocol internals, copy protections, working proofs-of-concept.

That combination is the whole point. I can read the bytes *and* sit in the room where the decision gets signed. When a vendor claims 99% accuracy, I can tell you whether it's true, how they produced the number, and what it costs you when it isn't — in the language of the person holding the budget.

---

## What I do now

I build and operate AI systems a business actually invoices on — legal-grade, on call, in production every day. The flagship is a transcription platform for court officers: a Whisper → GPT-4o → Claude pipeline with anti-hallucination guardrails, running ~70% of billable output unattended across a nine-server fleet.

Agent orchestration is the daily tool, not the demo — CLI agents driving deployment across a multi-VM fleet, MCP servers, a 90KB rule base and a 700-entry structured memory: the scaffolding that makes agents reliable enough to leave unattended in the first place. I own the whole chain, including the part most engineers never touch: invoicing, SEPA, dunning, bank reconciliation, fraud detection.

That platform is client-confidential, so it isn't on this profile. I'll walk the architecture, the eval methodology and the failure modes under NDA. Everything below is public, and it's the same engineering.

---

## Selected work

| Project | What it does | Stack |
|---------|-------------|-------|
| **[DS2-Anywhere](https://github.com/Guillain-RDCDE/DS2-Anywhere)** | Opened the Olympus DS2/DSS dictation format after 30 years locked — pure CLI, in production (~3,200 cron runs). Patch series [sent to ffmpeg-devel](https://lists.ffmpeg.org/lore/ffmpeg-devel/20260525193532.1845986-1-guillain@poulpe.us/T/#u); the Grundig DSS-SP decoder in it was cracked out of the vendor DLL and written from scratch | Python · Rust · C |
| **[FLAC Detective](https://github.com/Guillain-RDCDE/FLAC_Detective)** | Catches lossy transcodes hiding inside lossless files — spectral analysis + CNN classifier, 11K files validated, zero false positives | Python · PyTorch |
| **[Open-Alpha-Lab](https://github.com/Guillain-RDCDE/Open-Alpha-Lab)** | Quantitative research desk in public — 301 trading ideas stress-tested with reproducible, cost-aware methodology. Most are mirages. | Python · Jupyter |
| **[dss-codec](https://github.com/Guillain-RDCDE/dss-codec)** | The Rust decoder at the heart of DS2-Anywhere — byte-level reverse-engineering of a proprietary codec | Rust |
| **[Prometheus-Station](https://github.com/Guillain-RDCDE/Prometheus-Station)** | Solar-powered Raspberry Pi serving offline Wikipedia via LoRa mesh — infrastructure that works when everything else fails | Hardware · Linux |
| **[PocketRoll](https://github.com/Guillain-RDCDE/PocketRoll)** | Custom openFPGA core giving the 1998 Game Boy Camera an infinite film roll on the Analogue Pocket | Verilog · FPGA |

---

## Track record

**2023 – now** · **Founder & AI Systems Architect** — Legal-grade transcription platform. Whisper + LLM pipeline, nine-server fleet, iOS/Android apps, full billing stack. ~70% AI-automated output, billed daily to court officers.

**2011 – 2017** · **Founder & CEO, Algorithmic Trading Fund** — Built the entire stack: tick-level ingestion across 60+ instruments, 500–3,500 strategies running 24/5, FIX connector to LMAX. Monthly volume from <$100M to $9B, AUM peak $51M. Covered in Les Échos.

**2006 – 2011** · **Business Manager, Microsoft France** — Led a 9-person data team (SQL, SAP BO) for the $540M SMB division. Carried a $47M quota, +30%. Ranked 1st of 78 on customer satisfaction.

**1999 – 2010** · **Security Writer & Reverse Engineer** *(in parallel with the above)* — a decade in the paid security press. Real attacks, protocol internals, proofs-of-concept. Same reflex, now pointed at production systems.

---

## I publish the busts

Judgement you only see the wins of is worth nothing. So:

- [Four failed ML approaches and an "AUC 0.99" false discovery I caught before it fooled me](https://github.com/Guillain-RDCDE/FLAC_Detective/blob/main/ml/README.md) — the write-up that makes the working classifier believable.
- [Open-Alpha-Lab](https://github.com/Guillain-RDCDE/Open-Alpha-Lab) publishes the mirages next to the survivors, same methodology, same page.
- The FFmpeg submission is [an open workbench](https://github.com/Guillain-RDCDE/DS2-Anywhere/tree/main/ffmpeg-upstream) — cover letter, validation campaign, attribution chain, published *before* sending, so reviewers can find my mistakes while they're still cheap to fix.

---

## Let's talk

Available for full-time engagement from October 2026. Production AI systems, agent orchestration, LLM pipelines, reverse-engineering, infrastructure.

→ **[guillain@poulpe.us](mailto:guillain@poulpe.us)** — architecture walkthrough of the production platform available under NDA.
