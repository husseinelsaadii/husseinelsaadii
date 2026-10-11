<h1 align="center">Hussein El Saadi</h1>

<p align="center">
  <b>AI Engineer</b> — Computer Vision &amp; LLM Agents
</p>

<p align="center">
  <a href="mailto:huseinelsaadi@gmail.com"><img src="https://img.shields.io/badge/Email-huseinelsaadi%40gmail.com-informational?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/husseinelsaadi"><img src="https://img.shields.io/badge/LinkedIn-husseinelsaadi-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <img src="https://img.shields.io/badge/Beirut-Lebanon-success?style=flat-square&logo=googlemaps&logoColor=white" alt="Beirut, Lebanon">
</p>

---

I build AI systems that run in production, not just in notebooks. Day to day that means vision
models over engineering plans — YOLO, OCR, Vision-Language Models and ViT — plus the LLM agents,
data pipelines and tests that keep the whole thing reliable as models and data change.

I started on the data side, building scraping and extraction pipelines, and moved into AI
engineering from there. That background is the reason I care as much about the pipeline feeding a
model as about the model itself.

## What I do

🔍 **Computer vision** — detection and recognition on engineering plans with YOLO, OCR,
Vision-Language Models and ViT. When a trained model is the wrong tool, I write geometry-based
detection with classical algorithms instead.

🤖 **LLMs & agents** — RAG pipelines, LangGraph agents, and speech-driven systems with Whisper
and Bark. Built an AI interviewer that runs full voice conversations end to end.

🗄️ **Data engineering** — ingestion pipelines that collect documents at scale and pull structured
data out of PDFs and web pages while preserving document hierarchy.

🛠️ **Making it hold up** — automated testing so AI behaviour stays consistent as models and data
change, plus Docker, Terraform, CI/CD and AWS to ship it and keep it running.

## Selected projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/husseinelsaadii/Codingo">Codingo</a></h3>
      <p>AI-powered HR interviewer that runs live voice interviews from a job description and a candidate's CV.</p>
      <p><sub><b>Faster Whisper · Bark · Mistral · RAG · Hugging Face Spaces</b></sub></p>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/husseinelsaadii/wrc-decisions-pipeline">WRC Decisions Pipeline</a></h3>
      <p>Scrapes employment-law decisions, stores them exactly as downloaded, then cleans them into a tidy second copy.</p>
      <p><sub><b>Scrapy · Dagster · MongoDB · MinIO · 42 tests</b></sub></p>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/husseinelsaadii/finger-count-prediction">Finger Count Recognition</a></h3>
      <p>Real-time 0–5 finger counting from a webcam, with hand cropping before inference.</p>
      <p><sub><b>EfficientNet-B3 · TorchScript · OpenCV · Gradio</b></sub></p>
    </td>
  </tr>
</table>

<details>
<summary><b>More detail on each project</b></summary>

<br>

**[Codingo](https://github.com/husseinelsaadii/Codingo)** — an AI interviewer that runs end-to-end
interviews in live voice sessions, built from the recruiter's requirements and the candidate's
resume. Faster Whisper for speech-to-text, Bark for text-to-speech, and Mistral for context-aware
questions, with a RAG pipeline that retrieves relevant questions in real time. Deployed on Hugging
Face Spaces.

**[WRC Decisions Pipeline](https://github.com/husseinelsaadii/wrc-decisions-pipeline)** — a two-stage
Scrapy pipeline orchestrated by Dagster: `landing_documents` scrapes into MinIO and MongoDB exactly
as downloaded, then `processed_documents` strips site navigation and writes a clean copy. Monthly
partitions, hash-based duplicate detection, document versioning, and a middleware that honours the
server's `Retry-After` on a 429. The suite is 42 tests that run in under a second with no Docker and
no network.

**[Finger Count Recognition](https://github.com/husseinelsaadii/finger-count-prediction)** — a
six-class image classifier (0–5) trained on real hand photos, exported to TorchScript for inference
and served through a Gradio webcam interface. OpenCV detects and crops the hand region before the
model sees it.

</details>

## Tech

<details open>
<summary><b>Tools I work with</b></summary>

<br>

| | |
| --- | --- |
| **Languages** | Python · Java · SQL |
| **AI / ML** | PyTorch · Deep Learning · NLP · RAG · LangGraph · AI Agents · Mistral |
| **Computer Vision** | YOLO · OCR · Vision-Language Models · ViT · OpenCV · TorchScript |
| **Data** | Scrapy · Dagster · PostgreSQL · MongoDB · MinIO · PDF extraction · Label Studio · Power BI |
| **Cloud & DevOps** | AWS (Lambda) · Docker · Terraform · Git/GitHub · CI/CD · Hugging Face Spaces |

</details>

## Background

<details>
<summary><b>Education &amp; languages</b></summary>

<br>

**MSc Computer Science** — Modern University for Business and Science (MUBS) · *in progress*
Focused on artificial intelligence and agentic systems.

**BSc Data Science** — University of Science and Arts in Lebanon (USAL)
Focused on deep learning and natural language processing.

**Spoken languages** — English (fluent) · Arabic (native) · French (proficient) · Portuguese (conversational)

</details>

---

<p align="center">
  <sub>Open to work on AI systems that make it to production. <a href="mailto:huseinelsaadi@gmail.com">Get in touch →</a></sub>
</p>
