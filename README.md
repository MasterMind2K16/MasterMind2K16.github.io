# momenmedhat — Portfolio

Personal portfolio site: CV, LinkedIn, and the ARGUS project infographic.

**Live:** https://mastermind2k16.github.io

## Stack

Static HTML/CSS/JS in a single file. No build step, no dependencies, no framework.
Served by GitHub Pages from `main` / root.

## Structure

```
index.html                       # entire page (markup + styles + script)
assets/
  cv.pdf                         # résumé
  argus-infographic.jpg          # project infographic (2600px, web)
  argus-infographic.pdf          # project infographic (A2, full resolution)
```

## Featured project

**ARGUS — Autonomous AI Penetration Testing**
Locally hosted AI agent running the full pentest pipeline: recon → analysis → RAG CVE
enrichment → reflective exploit verification → structured reporting. LangGraph ReAct loop,
Pydantic structured decoding, Windows + WSL2 Kali bridge.
Built during the DigiLians 9-Month Professional Diploma (Round 1).

## Editing

Edit `index.html` directly and push — GitHub Pages redeploys automatically.
