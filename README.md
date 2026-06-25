<h1 align="center">Guillain d'Erceville</h1>

<p align="center">I build production systems that handle real money, and I publish the dead ends as openly as the wins.</p>

<p align="center">
  <a href="https://guillain-rdcde.github.io/Open-Alpha-Lab/">Open-Alpha-Lab (live)</a> ·
  <a href="mailto:guillain@poulpe.us">guillain@poulpe.us</a> ·
  FR / EN / ES · near Venice
</p>

---

I'm a contract engineer with three fairly different careers behind me. I built and ran a
systematic global-macro fund, spent about ten years reverse-engineering closed protocols for
the security press, and today I run a legal-grade transcription platform on my own. The thread
through all of it is the same: systems that have to work once they're in production, and a
healthy suspicion of clever ideas that don't survive a test.

Everything below has a repository you can open and read. If you only have a minute, the quant
work is the best showcase.

## Open-Alpha-Lab

[Open-Alpha-Lab](https://github.com/Guillain-RDCDE/Open-Alpha-Lab) is a quant research desk I
run in public. I take trading ideas apart and publish a plain verdict on each one: a real edge,
or a mirage. Market folklore, well-known factors, viral "90% win-rate" threads — they all go
through the same reproducible, tested engine, with no cherry-picking.

There are hundreds of studies now, each one a short working paper with notebooks and a
backtest you can re-run. The scorecard is deliberately honest: most ideas turn out to be
mirages, a handful are real but fragile, and only three hold up as genuinely investable. The
busts get published alongside the rest. It's the view of someone who actually ran the fund
rather than read about it.

The results are browsable as a [live, interactive map](https://guillain-rdcde.github.io/Open-Alpha-Lab/):
zoom in, filter by verdict, open any study.

## The Game Boy Camera, on real hardware

A full-stack revival of a 1998 toy. I wrote a custom openFPGA core that runs the original Game
Boy Camera on the Analogue Pocket with the sensor live, so you can shoot new photos with no
cartridge limit.

- [PocketRoll](https://github.com/Guillain-RDCDE/PocketRoll) holds the whole thing in one
  place: the FPGA core, plus the research that made it possible (the SRAM format, the checksum
  fix, decoding the `.sta` save format, sensor passthrough). It's documented twice over, once
  for newcomers and once for people who want the byte-level detail.
- [MugDump](https://github.com/Guillain-RDCDE/MugDump) pulls the photos back off the Pocket and
  develops them into real images.

## Background

**Now.** I run a legal-grade transcription platform end to end, on my own. That covers the
product (a Whisper and LLM pipeline with guardrails against hallucination), the nine-server
fleet it runs on, and the entire money chain most engineers never touch: invoicing, SEPA,
dunning, reconciliation, fraud. I'm on call, and the invoices are real.

**Before that.** I built and ran a fully systematic global-macro fund. I engineered the whole
trading stack and took monthly volume from under \$100M to more than \$9B, on a low-latency FIX
path into LMAX.

**Before that.** Roughly ten years reverse-engineering protocols and copy protections for the
paid security press.

I'm production-first, honest about what I don't know, and I read FIX logs and old Pascal with
about equal pleasure.

## Other projects

- [DS2-Anywhere](https://github.com/Guillain-RDCDE/DS2-Anywhere) — an open decoder for the
  Olympus DS2/DSS dictation format, closed for ten years. It retired a paid license in
  production, and I'm working it upstream into FFmpeg (ticket #6091, open since 2017).
- [FLAC Detective](https://github.com/Guillain-RDCDE/FLAC_Detective) — catches MP3s smuggled
  into lossless files. The interesting part isn't the detector; it's the
  [honest ML write-up](https://github.com/Guillain-RDCDE/FLAC_Detective/blob/main/ml/README.md):
  four approaches that didn't work, and an "AUC 0.99" false discovery I caught and killed
  before it fooled me.
- [Prometheus-Station](https://github.com/Guillain-RDCDE/Prometheus-Station) — a solar
  Raspberry Pi serving offline Wikipedia over a long-range LoRa mesh, for when there's no grid.
- [HAP-Revival](https://github.com/Guillain-RDCDE/HAP-Revival) — keeping Sony's HAP-Z1ES and
  HAP-S1 audiophile players alive after Sony stepped away in 2021.

## Working together

I take on a few contract engagements a year, the kind of systems that have to work rather than
demo well: production LLM and Whisper pipelines (including the billing infrastructure most
people skip), file-format and legacy reverse-engineering, and trading and market-data plumbing
(FIX, low latency, getting a backtest into production).

The best way to reach me is **[guillain@poulpe.us](mailto:guillain@poulpe.us)**.
