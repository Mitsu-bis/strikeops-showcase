# ⚔️ STRIKE OPS — PenTest Command Center

**A purpose-built command center for running professional penetration-testing
engagements end to end — one disciplined surface from kickoff to client deliverable.**

StrikeOps replaces scattered notes, terminal scrollback, and half-finished report
templates with a single operational cockpit. It drives the full engagement lifecycle
— Pre-Engagement → Recon → Enumeration → Exploitation → Reporting → Cleanup — while
capturing evidence at every step and producing a polished, client-ready report on the
way out.

It runs **fully local**: no cloud account, no telemetry, no third-party tracking. Built
for real engagements, red-team labs, and serious skills development alike.

> This repository is a **project showcase** that accompanies a written article about the
> tool. The application source is **not published here** — see
> [About this repository](#-about-this-repository).

---

## 🎯 Why it exists

Professional testing lives or dies on **discipline and evidence**. The hard part is
rarely a single exploit — it is running a repeatable methodology, capturing proof as you
go, tying findings into a coherent attack narrative, and turning all of it into a report
a client will actually act on. StrikeOps makes that the path of least resistance.

---

## 🚀 Core capabilities

### Engagement methodology, operationalized
A complete, structured methodology spanning the full engagement lifecycle. Every step
carries tooling guidance, **MITRE ATT&CK** technique mapping, **CVSS 3.1** scoring, and
inline evidence capture — commands, output, findings, and remediation — so the record is
built as the work happens, not reconstructed afterward.

### Relevance / Focus engine
Findings are not inert notes. Log one and StrikeOps **lights up the downstream steps it
makes relevant** across every later phase, with a reversible "relevant only" view. It
surfaces the path that actually matters for *this* target while keeping the full
methodology one click away.

### Attack Chain Builder
Link individual findings into **kill-chain narratives** — the initial-access →
escalation → impact story that turns a list of issues into a demonstrated business risk.
This is the difference between a vulnerability dump and a report that lands with
leadership.

### Client-ready reporting
One-click export to:
- **HTML / print-to-PDF** — cover page, executive summary, structured findings.
- **Markdown** — drops straight into Ghostwriter, Pwndoc, or your own pipeline.
- **JSON** — for data pipelines and tooling integration.

Findings, severities, CVSS scores, and ATT&CK mappings flow into the deliverable
automatically.

### Armory — scope-aware command reference
Copy-ready, **scope-aware** commands and references per phase. Target details flow into
the commands so what you copy is ready to run, not a placeholder you have to hand-edit.

### Tactical AI advisor (optional)
An optional, streaming, **agentic** advisor that can read the live engagement context and
help drive it forward. It runs in a **reviewed** mode (every change staged for your
approval) or a hands-off **co-pilot** mode, and it treats captured target output as
untrusted data — it will not follow instructions embedded in a target's responses.
Disable it entirely and every other capability still works.

### Engagement persistence & portability
Engagements autosave locally and export / import as JSON — hand off, archive, or move a
live engagement between machines without losing state.

### Built-in skills development
A training range and an optional guided **learn mode** turn the same cockpit into a
practice environment — hands-on tool drills mapped to free practice rooms, plus
step-level explanations and after-action review. Useful for onboarding and for keeping an
edge sharp between engagements, without ever getting in a working operator's way.

---

## 🔒 Local-first and OPSEC-conscious by design

- **Local only.** The server binds to localhost and is never exposed on the network.
- **No CDN, no beaconing.** No third-party requests during normal operation.
- **Secrets stay put.** Any API key lives in local config that is never committed.
- **Prompt-injection hardened.** The AI treats captured engagement output as untrusted.
- **Data-handling aware.** When an AI feature is used, only the relevant context is sent
  to the model provider — and an offline flow exists for engagements under strict
  data-handling rules.

---

## ⚖️ Authorized use only

StrikeOps is an engagement **workflow and reporting** tool, not an exploitation framework.
Any active tooling requires written authorization or ownership of the target. Practice
against your own lab, intentionally-vulnerable VMs, or scoped platforms only.

> Scope is the difference between a pentester and a defendant.

---

## 📖 About this repository

This is a **public showcase**, not the product.

- The application **source code is not published here** and is kept in a private
  repository. This page and any accompanying article describe the tool's design and
  capabilities at a high level only.
- Nothing in this repository is licensed for reuse. **All rights reserved.** The content
  here may not be copied, redistributed, or repackaged.
- StrikeOps is an independent project, shared for discussion and reference — not as a
  downloadable or deployable release.

---

<!--
  MAINTAINER NOTES (not rendered on GitHub):
  - Positioning: professional-services / engagement-delivery FIRST. Skills-development
    (training range + learn mode) is one capability, not the headline. (Skyler, 2026-09-21)
  - Screenshots intentionally omitted. The private repo's mockups/ images are NOT product
    screenshots (one was an internal network map, one an unrelated design reference) and
    must not be published. Add only vetted StrikeOps UI captures, cropped to avoid exposing
    any real engagement/target data.
  - Keep feature-level. No file layout, model IDs, server internals, or anything that
    discloses how the tool is built.
-->
