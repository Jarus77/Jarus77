# Hi, I'm Suraj Prasad 👋

**AI Researcher at [Actioneer](https://actioneer.com/)** · **IIT Bombay** graduate (B.Tech Mechanical Engineering, minor in Computer Science)

I build the infrastructure around LLM post-training: reward functions grounded in execution, rigorous baselines and ablations, and pre-registered go/no-go experiments. Two threads right now — **relational foundation models** (learning over a database schema instead of hand-built features) and **speech** (code-switched ASR, on-device inference).

Across text-to-SQL RL and Hindi–English ASR fine-tuning, the hard problem has consistently turned out to be **data and evaluation, not architecture**.

📍 **Portfolio and writing → [jarus77.github.io](https://jarus77.github.io)**

---

### Research and shipped work

| | |
|---|---|
| **SCRIBE** — a Spec → Executor → Planner agent for data analysis across PostgreSQL, SQLite, DuckDB and MongoDB | **#1 on DataAgentBench**, 81.85% stratified pass@1, verified via a merged upstream PR · [code](https://github.com/Suraj-gameramp/scribe-dab) |
| **Full-parameter RL for text-to-SQL** on BIRD-bench — GRPO plus a custom max-entropy difficulty-weighting estimator, FSDP with CPU offload to fit 7B RL on one node | Reproduced OmniSQL-7B's published baseline within **0.5pp**, RL model at **68.12% maj@8**. Two research bets killed on pre-registered evidence · [code](https://github.com/Suraj-gameramp/bird-factory) |
| **Srota ASR** — open-source code-switched Hindi–English speech recognition, fine-tuned from Qwen3-ASR-0.6B | A 3-variant ablation produced a **21.79pp swing** from training-data composition alone; script steering gave a **36% relative WER reduction** · [models](https://huggingface.co/moorlee/qwen3-asr-0.6b-hinglish) · [code](https://github.com/Suraj-gameramp/qwen-0.6b-hinglish) |
| **[Srota](https://www.susrota.com/)** — privacy-first macOS voice dictation, built solo in Swift/SwiftUI/AppKit | **100+ active users**, fully on-device at sub-130 ms end to end. No audio ever leaves the machine |
| **[Markdrop](https://pypi.org/project/markdrop/)** — PDF to Markdown/HTML with tables, figures and LLM-written descriptions | **210+ stars, 25,000+ downloads.** Featured in [Japanese tech press](https://kachibito.net/useful-resource/markdrop) and [AINews](https://buttondown.com/ainews/archive/ainews-not-much-happened-today-3076/) |
| **KuralGPT** — built with BharatGen | [thirukural.ai](https://thirukural.ai) |

### Papers

- **SynthPID: P&ID Digitization from Topology-Preserving Synthetic Data** — CVPR 2026 Workshop (AI4RWC). 63.8±3.1% edge mAP with **zero real training data**, within 8pp of the real-data oracle.
- **Speech-Synchronized Whiteboard Generation via VLM-Driven Structured Drawing Representations** — CVPR 2026 Workshop (CV4Edu).
- **[Federated Cross-Modal Style-Aware Prompt Generation](https://arxiv.org/abs/2508.12399)** — AAAI 2026 Workshop (SAPP). SOTA on 9 benchmarks (+4.3% unseen classes).

### Writing

I work through papers by rebuilding every idea in them from scratch. That is my test for whether I actually understood something.

- [RelGNN: reading a database as a set of atomic routes](https://jarus77.github.io/writing/relgnn.html)
- [The Relational Transformer: what survives when the schema changes](https://jarus77.github.io/writing/relational-transformer.html)
- [The Jacobian lens: reading the thoughts a model hasn't said](https://jarus77.github.io/writing/jacobian-lens.html)

### Also

Co-founded **Latent Space**, an eight-person AI lab at IIT Bombay (CVPR and AAAI publications within a year of founding) · **Entrepreneur First** founder cohort, Bengaluru · **1st nationwide**, Smart India Hackathon 2024 (real-time speech ↔ Indian Sign Language) · **4th worldwide**, ICRA 2024 RoboDrive Challenge · Undergraduate Research Award (URA01), IIT Bombay

> Most of my code lives with companies, so this account is quiet. Research and product repos are split across [@Jarus77](https://github.com/Jarus77?tab=repositories) and [@Suraj-gameramp](https://github.com/Suraj-gameramp?tab=repositories).

📫 surajprasad8977@gmail.com · [LinkedIn](https://www.linkedin.com/in/surajprasad7/) · [Google Scholar](https://scholar.google.com/citations?user=YhFFM9AAAAAJ&hl=en) · [X](https://x.com/SurajPrasad527)

_Always learning. Always building. Open to collaborations._
