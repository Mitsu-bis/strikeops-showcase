# ⚔️ STRIKE OPS — PenTest Command Center

**A local, single-purpose penetration-testing engagement cockpit.**

StrikeOps walks an operator through a complete offensive-security methodology —
Pre-Engagement → Recon → Enumeration → Exploitation → Reporting → Cleanup — keeps
evidence organized at every step, and pairs the workflow with an AI advisor, a
hands-on training range, and client-ready report export.

It is built for local labs, TryHackMe / HackTheBox rooms, and **authorized**
engagements. It runs fully local: no cloud account, no telemetry, no third-party
tracking.

> This repository is a **project showcase**. It exists to describe the tool and to
> accompany a written article about it. The application source is **not published
> here** — see [About this repository](#-about-this-repository) below.

---

## ✨ What it does

- **Full methodology checklist** — six missions covering the engagement lifecycle,
  each step carrying tool hints, ATT&CK technique mapping, CVSS 3.1 scoring, and
  per-step evidence capture (commands, output, findings, remediation).
- **Keyword quick-find** — cut through the methodology instantly with a search that
  is non-destructive and clears straight back to the full checklist.
- **Relevance / Focus engine** — a finding lights up the steps it makes relevant
  across every later phase, with a reversible "relevant only" view. It surfaces the
  path that matters without ever permanently hiding the rest.
- **Tactical AI advisor** — an optional, streaming advisor with two independent
  modes: a *reviewed* vs *co-pilot* write mode, and an *operator* (terse, tactical)
  vs *learn* (Socratic mentor) tone.
- **Learning layer** — turn any step into a micro-lesson, get coached on what you
  actually logged, and receive an engagement-wide after-action review that grades
  your work as a lesson rather than just a checklist.
- **Learner mode** — a gentler on-ramp that calms the interface and foregrounds the
  teaching tools, toggleable off for the dense operator cockpit.
- **Training range** — an OSINT recon armory plus hands-on drills across multiple
  tool modules, each mapped to a free practice room, reachable directly from the
  matching methodology step.
- **Armory** — copy-ready, scope-aware commands and references per section.
- **Attack chain builder** — link findings into kill-chain narratives.
- **Report export** — professional HTML (print-to-PDF, cover page, executive
  summary), Markdown, or JSON.
- **Engagement persistence** — autosaves locally; export and import as JSON.

---

## 🎯 Who it is for

StrikeOps is aimed at operators studying for or working toward OSCP / CEH / red-team
skill sets, and at anyone who wants a single, organized surface to run a methodical
engagement instead of scattered notes and terminal scrollback. It leans deliberately
**teach-heavy**: the goal is to help the operator learn the *why*, not just tick boxes.

---

## 🔒 Authorized use only

StrikeOps is a workflow and learning tool, not an exploitation framework. Passive
OSINT on public data is fair game for learning, but the moment any tooling sends
traffic *at* a target, written authorization or ownership of the system is required.
Practice active tooling only against your own lab, intentionally-vulnerable VMs, or
scoped platforms such as TryHackMe / HackTheBox.

> Scope is the difference between a pentester and a defendant.

---

## 📖 About this repository

This is a **public showcase**, not the product.

- The application **source code is not published here** and is kept in a private
  repository. This page and any accompanying article describe the tool's design and
  capabilities at a high level only.
- Nothing in this repository is licensed for reuse. **All rights reserved.** The
  content here may not be copied, redistributed, or repackaged.
- StrikeOps is a personal project. It is shared for discussion and reference, not as
  a downloadable or deployable release.

---

<!--
  MAINTAINER NOTES (not rendered on GitHub):
  - Screenshots were intentionally omitted. The images in the private repo's mockups/
    folder are NOT product screenshots (one was an internal network map, one an
    unrelated design reference) and must not be published. Add only vetted StrikeOps
    UI captures here, cropped to avoid exposing any real engagement/target data.
  - Keep this page feature-level. Do not add file layout, model IDs, server internals,
    or any content that discloses how the tool is built.
-->
