
<!-- Profile README for @Princu1999 -->
<p align="center">
  <!-- Replace assets/hero.png with your own banner (prefer 840–960 px wide, dark-mode friendly) -->
  <img src="assets/hero.png" alt="Princu — AI/ML Engineer" width="860">
</p>

<h1 align="center">Hi, I'm <a href="https://github.com/Princu1999">Princu</a> 👋</h1>
<p align="center">
  <b>MTech (AI) • Computer Vision & Vision‑Language • Generative Modeling • MLOps</b>
</p>

<p align="center">
  <a href="#-featured-projects">Projects</a> •
  <a href="#-project-snapshots">Snapshots</a> •
  <a href="#-tech-stack--skills-matrix">Tech</a> •
  <a href="#-how-i-work">Process</a> •
  <a href="#-contact">Contact</a>
</p>

<p align="center">
  <a href="mailto:princusingh252@gmail.com"><img src="https://img.shields.io/badge/Email-princusingh252%40gmail.com-blue" /></a>
  <a href="https://www.linkedin.com/in/princu1999/"><img src="https://img.shields.io/badge/LinkedIn-@princu1999-0A66C2?logo=linkedin&logoColor=white" /></a>
  <a href="https://huggingface.co/Princu1999"><img src="https://img.shields.io/badge/HuggingFace-Princu1999-FFD21E?logo=huggingface&logoColor=000" /></a>
</p>

---

## 🚀 About me
I design and ship **CV/VL systems** end‑to‑end: data → training → evaluation → demo.  
Recent work includes **data‑free knowledge distillation** for compact models and **NIR deepfake detection**.  
Open to **AI/ML Engineer** roles where model quality, reliability, and time‑to‑impact matter.

### What I’m good at
- **Hands‑on ML engineering**: clean data pipelines, reproducible training, robust evaluation, CI for model code.
- **DL for vision & VL**: BLIP/CLIP/SigLIP, CNNs, ConvLSTMs, attention, contrastive / KD objectives.
- **MLOps & delivery**: Dockerized training/inference, experiment tracking, model packaging, Gradio/Spaces demos.
- **Product lens**: translate goals into metrics (AUROC/AUPRC/EER, SMAPE), demo fast, iterate with evidence.

---

## 🔥 Featured projects
> Each card focuses on a real problem, the results, and why it matters.

### 1) Adversarial Knowledge Distillation (AKD) — PyTorch
Distills a **ResNet‑34 teacher** into **compact ResNet‑18 students** using a lightweight generator (no original training data). Clean modules (models/engine/utils), scripts for training/eval, and run tracking.
- **Why it matters:** privacy‑preserving model shrinking for **edge deployment** (latency/VRAM constraints).  
- **Focus:** KD scheduling, generator‑driven synthesis, reproducibility (config logs & checkpoints).  
- **Links:** <a href="https://github.com/Princu1999/Data-Free-Knowledge-Distillation">Repository</a>

### 2) VisionNarrate — BLIP‑based Image Narration (Accessibility)
Generates **context‑aware, emotion‑sensitive** descriptions for visually‑impaired users; modular fine‑tuning + eval.
- **Impact:** METEOR **0.42** (vs 0.28 baseline), BLEU‑4 **0.18** (vs 0.12).  
- **Stack:** PyTorch + BLIP; Gradio for demo; reproducible scripts.  
- **Links:** <a href="https://github.com/Princu1999/VisionNarrate">Repository</a> • <a href="https://huggingface.co/Princu1999">Hugging Face</a>

### 3) NIR‑FAKE — Deepfake Detection Dataset (Research)
Curating a near‑infrared dataset with **face‑swap** and **complete‑body‑removal** forgeries; standardized **eval protocol** (AccR/AccF/OvA, **AUROC**, **AUPRC**, **EER**, **FPR@TPR**).
- **Why it matters:** extends detection to **low‑light/surveillance** contexts beyond RGB.  
- **Links:** <a href="https://github.com/Princu1999/NIR-FAKE">Repository</a>

### 4) Cloud Movement Prediction — ConvLSTM Nowcasting (contrib.)
End‑to‑end pipeline with **Stacked ConvLSTM** + optical flow for cloud detection/motion.
- **Use cases:** weather risk, solar energy planning, aviation.  
- **Links:** <a href="https://github.com/Vimal9900/Satellite-Imagery-Based-Cloud-Detection-and-Movement-Prediction">Upstream repo</a> • <a href="https://huggingface.co/spaces/Princu1999/Cloud_Predictor_App">HF Space</a>

### 5) Credit‑Card Customer Segmentation — Unsupervised ML
Clustering via **K‑Means / GMM / DBSCAN**, profiling customer behavior to drive targeted campaigns.
- **Business lens:** cohort insights, churn risk flags, and cross‑sell strategies.  
- **Links:** <a href="https://github.com/Princu1999/Credit-Card-Customer-Segmentation">Repository</a>

> I keep coursework repos public for transparency. The above five are the best entry points for quality and impact.

---

## 📦 Project snapshots
| Project | What it solves | Key metrics | Links |
|---|---|---|---|
| **VisionNarrate** | Accessible image captions | METEOR **0.42**, BLEU‑4 **0.18** | [Repo](https://github.com/Princu1999/VisionNarrate) • [HF](https://huggingface.co/Princu1999) |
| **AKD (data‑free)** | Shrink models without data | Compact ResNet‑18 variants (~50% / ~20%) | [Repo](https://github.com/Princu1999/Data-Free-Knowledge-Distillation) |
| **NIR‑FAKE** | Deepfake detection (NIR) | AUROC/AUPRC/EER protocol | [Repo](https://github.com/Princu1999/NIR-FAKE) |
| **Cloud Nowcasting** | ConvLSTM + OF motion | Qualitative demo | [Demo](https://huggingface.co/spaces/Princu1999/Cloud_Predictor_App) |
| **Customer Segmentation** | Marketing cohorts | Cluster profiles (K‑Means/GMM/DBSCAN) | [Repo](https://github.com/Princu1999/Credit-Card-Customer-Segmentation) |

---

## 🧰 Tech stack & Skills matrix
**Languages**: Python, C/C++  
**DL/ML**: PyTorch, TensorFlow/Keras, Hugging Face Transformers/PEFT, scikit‑learn, OpenCV  
**Data/Viz**: NumPy, Pandas, Matplotlib/Plotly  
**MLOps/Infra**: Docker, GitHub Actions, MLflow/W&B (workflow‑ready), Gradio/Spaces, Linux

| Area | Strong | Working |
|---|---|---|
| CV/VL | PyTorch, BLIP/CLIP/SigLIP, OpenCV | ONNX, TensorRT |
| Modeling | KD/contrastive, CNNs, ConvLSTM | LoRA/QLoRA |
| MLOps | Docker, GH Actions, packaging | MLflow/W&B |
| Data & Eval | Pandas/NumPy; AUROC/AUPRC/EER, SMAPE | Spark (basic) |

---

## 🛠 How I work
- **Reproducible runs:** fixed seeds, saved configs, deterministic backends.  
- **Clear eval:** task‑appropriate metrics (AUROC/AUPRC/EER, SMAPE) + ablations.  
- **Deployable demos:** Gradio/Spaces for fast stakeholder feedback.  
- **Code quality:** modular design, typed functions (where useful), CI checks.

<!-- Example CI badge you can place on repo READMEs -->
<!-- ![CI](https://github.com/Princu1999/Data-Free-Knowledge-Distillation/actions/workflows/ci.yml/badge.svg) -->

<details>
<summary><b>Minimal CI template (drop into .github/workflows/ci.yml)</b></summary>

```yaml
name: CI
on: [push, pull_request]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-python@v5
        with:
          python-version: '3.11'
      - run: pip install -r requirements.txt || true
      - run: python -m pip install ruff pytest || true
      - run: ruff check .
      - run: pytest -q || true
```
</details>

---

## 📈 GitHub stats
<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Princu1999&show_icons=true&count_private=true&rank_icon=github&cache_seconds=7200" />
  <img height="170" src="https://streak-stats.demolab.com?user=Princu1999&cache_seconds=7200" />
</p>
<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Princu1999&layout=compact&langs_count=8&cache_seconds=7200" />
</p>

---

## 🏅 Top repositories (stable cards)
<p align="center">
  <a href="https://github.com/Princu1999/VisionNarrate">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Princu1999&repo=Vision-Narrate&cache_seconds=7200" />
  </a>
  <a href="https://github.com/Princu1999/NIR-FAKE">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Princu1999&repo=NIR-FAKE&cache_seconds=7200" />
  </a>
</p>
<p align="center">
  <a href="https://github.com/Princu1999/Credit-Card-Customer-Segmentation">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Princu1999&repo=Credit-Card-Customer-Segmentation&cache_seconds=7200" />
  </a>
  <a href="https://github.com/Princu1999/Data-Free-Knowledge-Distillation">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Princu1999&repo=Data-Free-Knowledge-Distillation&cache_seconds=7200" />
  </a>
</p>

---

## 💬 Developer quote
<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=vertical&theme=default&quoteCategory=programming" alt="dev quote"/>
</p>

---

## 📫 Contact
- Email: <a href="mailto:princusingh252@gmail.com">princusingh252@gmail.com</a>  
- LinkedIn: <a href="https://www.linkedin.com/in/princu1999/">@princu1999</a>  
- Hugging Face: <a href="https://huggingface.co/Princu1999">Princu1999</a>  
- GitHub: <a href="https://github.com/Princu1999">@Princu1999</a>

---

<!-- How to use
1) Create a repo named exactly your username: `Princu1999`.
2) Place this file as README.md at the root of that repo (it becomes your profile page).
3) Add assets/hero.png (840–960 px). If you don’t want a banner, remove the <img> tag at the top.
4) Pin the four repos shown under “Top repositories” to match the cards.
-->
