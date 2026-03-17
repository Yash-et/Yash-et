<div align="center">

<!-- HEADER GLITCH BANNER -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0a0a0f,50:00f7ff,100:7b2fff&height=200&section=header&text=YASH%20MEHTA&fontSize=72&fontColor=ffffff&fontAlignY=55&animation=twinkling&stroke=00f7ff&strokeWidth=2&desc=AI%20Engineer%20%7C%20Researcher%20%7C%20Builder&descSize=18&descAlignY=78&descColor=a0f0ff"/>

<!-- LIVE TYPING -->
<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=22&duration=2800&pause=1200&color=00F7FF&center=true&vCenter=true&width=900&height=60&lines=Building+AI+systems+that+actually+ship.;Time+Series+%E2%86%92+Transformers+%E2%86%92+Production.;Legal+AI+%7C+Fog+Vision+%7C+Fake+News+Detection.;Presented+at+IIT+Roorkee+%E2%80%A2+LexHack+Winner.;Open+to+research+%7C+collabs+%7C+good+problems." alt="Typing SVG" />

<!-- QUICK CONNECT STRIP -->
<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yash-mehta-402239163)
[![GitHub](https://img.shields.io/badge/GitHub-161b22?style=for-the-badge&logo=github&logoColor=00f7ff)](https://github.com/YashM-235)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yash34m6@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-0a0a0f?style=for-the-badge&logo=firefox&logoColor=7b2fff)](#)

<br>

![Profile Views](https://komarev.com/ghpvc/?username=YashM-235&color=00f7ff&style=flat-square&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/YashM-235?style=flat-square&color=7b2fff&labelColor=0a0a0f&label=FOLLOWERS)

</div>

---

## `> whoami`

```python
yash = {
    "name"       : "Yash Mehta",
    "role"       : "AI Engineer & Researcher",
    "university" : "Bennett University",
    "location"   : "Greater Noida, India",
    "languages"  : ["Python", "C++", "JavaScript", "SQL"],
    "focus"      : ["Time Series Forecasting", "Computer Vision", "Legal AI", "NLP"],
    "research"   : "Presented @ SocProS 2025 — IIT Roorkee",
    "awards"     : ["LexHack 1.0 Innovation & Impact Award"],
    "certifications": 7,   # NVIDIA · IBM · Google · IIT Delhi
    "currently"  : "Building next-gen ML architectures. Open to collabs."
}
```

> I build AI systems that move from notebook to production — with clean architecture, real benchmarks, and an eye for impact. Currently deep in time series forecasting and fog dehazing research.

---

## `> ls ./projects`

<details>
<summary><b>📈 Amazon Stock Oracle</b> — Time Series Forecasting System</summary>

<br>

**What it does:** A 7-model ensemble forecasting pipeline for Amazon (AMZN) stock prices, anchored by a custom-built `TimeSeriesTransformer` architecture. Trained end-to-end from preprocessing to deployment-ready inference.

| Metric | Value |
|--------|-------|
| Architecture | ARIMA · LSTM · GRU · Transformer · XGBoost · Prophet · Ensemble |
| Best RMSE | **0.03285** |
| Inference | Real-time streaming pipeline |
| Status | ✅ Production-ready |

```python
class TimeSeriesTransformer(nn.Module):
    """
    Custom transformer for financial time series.
    Multi-head attention on temporal sequences with
    positional encoding tuned for market periodicity.
    """
    def __init__(self, d_model=512, n_heads=8, seq_len=60):
        super().__init__()
        self.temporal_embed  = TemporalEmbedding(d_model, seq_len)
        self.attention_stack = nn.TransformerEncoder(
            nn.TransformerEncoderLayer(d_model, n_heads, dropout=0.1),
            num_layers=6
        )
        self.forecast_head   = nn.Linear(d_model, 1)
```

</details>

---

<details>
<summary><b>⚖️ FIR Generator 9000</b> — Legal AI Platform <code>[LexHack 1.0 Winner]</code></summary>

<br>

**What it does:** An AI-powered FIR (First Information Report) drafting and legal advisory platform. Integrates Gemini for natural language legal guidance, live geospatial crime mapping, and quantum-encrypted evidence logs.

| Feature | Detail |
|---------|--------|
| AI Core | Gemini-powered legal language model |
| Mapping | Real-time geospatial crime analytics |
| Impact | 95% reduction in FIR drafting time |
| Recognition | 🏆 LexHack 1.0 — Innovation & Impact Award |

> *"Transforms how citizens and law enforcement interact with the legal system."*

</details>

---

<details>
<summary><b>🌫️ Fog Vision AI</b> — Real-Time Dehazing System</summary>

<br>

**What it does:** A hybrid CNN + Vision Transformer architecture for real-time image dehazing. Benchmarked across 4 major fog datasets, with state-of-the-art improvements on perceptual quality metrics.

| Benchmark | Dataset | Result |
|-----------|---------|--------|
| FRIDA2 | Indoor synthetic fog | **+15% SSIM vs SOTA** |
| HSTS | Homogeneous fog | ✅ Top-tier PSNR |
| SOTS | Outdoor real fog | ✅ Competitive CIEDE2000 |
| NTIRE19 | Dense haze challenge | ✅ Real-time viable |

**Architecture:** Dual-path encoder merging local CNN features with global ViT attention, decoded through adaptive denormalization layers.

</details>

---

<details>
<summary><b>📰 Fake News Terminator</b> — NLP Detection Pipeline</summary>

<br>

**What it does:** A multi-model NLP ensemble for automated fake news detection. Combines transformer-based semantic embeddings with classical ML for high-recall classification.

| Metric | Value |
|--------|-------|
| Accuracy | **87%** |
| Approach | Ensemble: BERT + TF-IDF + XGBoost |
| Dataset | 40k+ labeled articles |
| Status | ✅ Deployed |

</details>

---

## `> cat ./tech_stack.json`

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-0a0a0f?style=for-the-badge&logo=python&logoColor=00f7ff)
![C++](https://img.shields.io/badge/C++-0a0a0f?style=for-the-badge&logo=cplusplus&logoColor=7b2fff)
![JavaScript](https://img.shields.io/badge/JavaScript-0a0a0f?style=for-the-badge&logo=javascript&logoColor=f7c500)
![SQL](https://img.shields.io/badge/SQL-0a0a0f?style=for-the-badge&logo=postgresql&logoColor=00f7ff)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-0a0a0f?style=for-the-badge&logo=pytorch&logoColor=EE4C2C)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0a0a0f?style=for-the-badge&logo=tensorflow&logoColor=FF6F00)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0a0a0f?style=for-the-badge&logo=scikit-learn&logoColor=F7931E)
![OpenCV](https://img.shields.io/badge/OpenCV-0a0a0f?style=for-the-badge&logo=opencv&logoColor=00f7ff)
![HuggingFace](https://img.shields.io/badge/HuggingFace-0a0a0f?style=for-the-badge&logo=huggingface&logoColor=FFD21E)

**Web & APIs**

![Flask](https://img.shields.io/badge/Flask-0a0a0f?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-0a0a0f?style=for-the-badge&logo=react&logoColor=00f7ff)
![FastAPI](https://img.shields.io/badge/FastAPI-0a0a0f?style=for-the-badge&logo=fastapi&logoColor=00d4a4)
![Node.js](https://img.shields.io/badge/Node.js-0a0a0f?style=for-the-badge&logo=nodedotjs&logoColor=3fa84c)

**Tools & Infrastructure**

![Git](https://img.shields.io/badge/Git-0a0a0f?style=for-the-badge&logo=git&logoColor=F05032)
![Docker](https://img.shields.io/badge/Docker-0a0a0f?style=for-the-badge&logo=docker&logoColor=2496ED)
![MongoDB](https://img.shields.io/badge/MongoDB-0a0a0f?style=for-the-badge&logo=mongodb&logoColor=00ED64)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0a0a0f?style=for-the-badge&logo=postgresql&logoColor=336791)

</div>

---

## `> cat ./achievements.log`

```diff
+ [2025]  🏆  Innovation & Impact Award  ——  LexHack 1.0
+ [2025]  📜  Research Paper Presenter   ——  SocProS 2025 @ IIT Roorkee
+ [2025]  ⚛️   Quantum Computing & QKD     ——  IIT Delhi (3-Day Workshop)
+ [2024]  🎓  6× AI Certifications       ——  NVIDIA · IBM · Google
+ [2023]  🚀  Featured — Bennett University Industry Showcase
+ [----]  📦  10+ Production ML Systems  ——  Deployed & Active
+ [----]  👥  500+ Students Impacted     ——  AI Career Platform
+ [----]  📰  87% Detection Accuracy     ——  Fake News Pipeline
+ [----]  ⚙️   95% Workload Reduction     ——  Automated Allocation System
```

---

## `> github --stats`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=YashM-235&show_icons=true&theme=dark&bg_color=0a0a0f&title_color=00f7ff&icon_color=7b2fff&text_color=c0e8ff&border_color=1a1a2e&border_radius=8&include_all_commits=true&count_private=true"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YashM-235&layout=compact&theme=dark&bg_color=0a0a0f&title_color=00f7ff&text_color=c0e8ff&border_color=1a1a2e&border_radius=8&langs_count=8"/>

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com?user=YashM-235&theme=dark&background=0a0a0f&border=1a1a2e&ring=00f7ff&fire=7b2fff&currStreakLabel=00f7ff&sideLabels=c0e8ff&dates=5a7a9a&currStreakNum=ffffff&sideNums=ffffff&border_radius=8" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YashM-235&bg_color=0a0a0f&color=00f7ff&line=7b2fff&point=ffffff&area=true&area_color=00f7ff&hide_border=false&border_color=1a1a2e&radius=8"/>

</div>

---

## `> open --collaborate`

I'm actively looking for:

- 🔬 **Research collaborations** — especially in time series, CV, or applied NLP
- 🛠️ **Open source contributions** — well-scoped ML/AI tools and libraries  
- 🎓 **Student community projects** — if you're building something real, let's talk
- 💼 **Industry opportunities** — internships, roles, or consulting

```bash
# Best way to reach me:
$ echo "yash34m6@gmail.com" | send --subject "Let's build something"

# Or just connect on LinkedIn — I reply fast.
```

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,50:00f7ff20,100:7b2fff&height=100&section=footer&text=&animation=twinkling"/>

*Building systems that ship. One commit at a time.*

</div>
