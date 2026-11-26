# Hi, I'm Izza 👋

I'm an AI engineer from Islamabad, Pakistan. I like building AI that people can actually trust: the kind that tells you where its answer came from instead of guessing.

## What I've built

**[MediSafe AI](https://github.com/izza-m1/medisafeAI-app)**
You take one photo of a supplement label and it tells you if it's safe for *you*: your dose, what to avoid, and whether the brand is real. You can also ask it questions, and it answers from official NIH health sources and shows you the exact passage it used.

How it works, in short:
- reads the label with EasyOCR and checks the photo with CLIP
- dose limits and safety rules come from NIH and USDA data, not guesses
- RAG over 24 NIH fact sheets with hybrid search (embeddings + BM25)
- a Claude agent with tool use writes the report, and every claim has a source
- FastAPI backend, React Native app, 68 tests plus retrieval evals

**Sentinel**: scans a website for security issues and writes a plain-English report on each one using a local LLM.

## What I work with

Python · FastAPI · Claude API · RAG · AI agents · embeddings · CLIP · EasyOCR · React Native · Firebase · Docker · Git

## What I'm learning right now

MCP, deploying FastAPI apps properly, and how models are fine-tuned and evaluated.

## Let's talk

I'm open to AI engineering roles: remote, on-site in Islamabad, or relocation.
[LinkedIn](https://linkedin.com/in/izza-maryam-5b0119234) · maryamizza1@gmail.com
