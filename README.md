# Mazin Omar Alehiassat

### Junior AI Engineer: LLM applications, retrieval, and computer vision

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mazaenalheasat-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/mazaenalheasat)
[![Email](https://img.shields.io/badge/Email-malheasa0t%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:malheasa0t@gmail.com)
[![Website](https://img.shields.io/badge/Website-serva--s.com-555555?style=flat)](https://serva-s.com)
[![Location](https://img.shields.io/badge/Location-Zarqa%2C%20Jordan-2E8B57?style=flat)](#)

B.Sc. in Artificial Intelligence (June 2026). I build AI features end to end,
from data and prompts to backend, deployment, and the user interface.

## Serva

[serva-s.com](https://serva-s.com) is a digital services platform I built:
460+ services, 3,700+ completed orders, and a 4.6/5 rating from 190+
reviews. It also has an
[Android app on Google Play](https://play.google.com/store/apps/details?id=com.serva.platform).

The site has a live customer-support AI assistant that handles 30+
conversations a day.

- Current design: an LLM router picks the relevant catalog category, then a
  second LLM call answers using only that category's services and
  owner-approved knowledge. Built with Python on Cloudflare Workers, Supabase
  Postgres, and the Gemini API.
- Version 1 was a hybrid RAG pipeline (Gemini embeddings, chunking with
  overlap, pgvector HNSW semantic search plus trigram search). I replaced it
  because it confused near-identical plans (for example monthly vs. yearly)
  and served stale content after catalog edits.
- An 80+ scenario regression question set is reviewed after prompt changes.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [tensar](https://github.com/malheasa0t-prog/tensar) | E-commerce single-page app ([tensr.systems](https://tensr.systems)) with a Groq-powered chat and CI/CD. | React, Vite, Supabase, Cloudflare Pages Functions, Groq, GitHub Actions |
| [phone-damage-detection](https://github.com/malheasa0t-prog/phone-damage-detection) | YOLOv11 object detection for phone damage, 6 classes. Built during my internship at RAID. | Python, PyTorch, YOLOv11, OpenCV |
| [car-and-food-clip-model](https://github.com/malheasa0t-prog/car-and-food-clip-model) | CLIP fine-tuned on a curated 200-image dataset, with a Gradio demo. Built during my internship at RAID. | Python, PyTorch, CLIP, Hugging Face, Gradio |
| [RAG-System](https://github.com/malheasa0t-prog/RAG-System) | An early standalone RAG prototype for Serva support questions (not the live assistant). Keyword and pgvector retrieval, several LLM providers, output guardrails, and rule-based evaluation scripts. | Python, Supabase pgvector, Gemini embeddings, LangChain, Gradio |

## Experience

**AI & Computer Vision Intern, RAID** (Oct 2025 – Jan 2026): built the phone
damage detection and CLIP projects above.

## Skills

**AI / ML:** Python, PyTorch, LLM integration, prompt engineering, RAG and
retrieval design, embeddings, computer vision, YOLOv11, CLIP, fine-tuning,
Hugging Face, OpenCV, Gradio

**Backend and data:** SQL, FastAPI, Supabase, pgvector, Gemini API, Groq

**Frontend and mobile:** JavaScript, React, Android

**Infrastructure:** Cloudflare, Docker, GitHub Actions

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=malheasa0t-prog&show_icons=true&theme=default)
