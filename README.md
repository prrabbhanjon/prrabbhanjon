# Hi, I'm P Sakinala 👋

**Subject Matter Expert in Cloud** · United States of America
![Profile views](https://komarev.com/ghpvc/?username=prrabbhanjon&color=brightgreen&style=flat&label=Profile+views)
💡 Passionate about automation, AI, and creative coding — Creating, Automating, and Innovating every day.

---

## 🚀 What I'm building

I explore the intersection of **AI**, **Kubernetes**, and **open-source tooling** — turning complex infrastructure into simple one-command experiences.

> *"If you have to do it twice, automate it. If you have to explain it twice, document it."*

---

## 🤖 Featured Project — Headroom Telemetry GUI

> Live token savings dashboard for [Headroom AI](https://github.com/chopratejas/headroom) — deployed on Kubernetes via Podman Desktop.

[![Build](https://github.com/prrabbhanjon/headroom-telemetry-gui/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/prrabbhanjon/headroom-telemetry-gui/actions/workflows/docker-publish.yml)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/prrabbhanjon/headroom-telemetry-gui/blob/main/LICENSE)
[![ghcr.io proxy](https://img.shields.io/badge/ghcr.io-headroom--proxy-teal)](https://ghcr.io/prrabbhanjon/headroom-proxy)
[![ghcr.io gui](https://img.shields.io/badge/ghcr.io-headroom--gui-orange)](https://ghcr.io/prrabbhanjon/headroom-gui)

Every AI agent call burns tokens on noise — log files, boilerplate, repeated context. **Headroom** compresses it before it hits the LLM. I built a live Kubernetes dashboard to visualise exactly how much is being saved — every second, automatically.

```
Host machine → kubectl port-forward → Kind cluster (Podman Desktop)
                                        ├── headroom-proxy  :8787  (compresses prompts)
                                        └── headroom-gui    :80    (live dashboard)
                                                    ↓
                                        Anthropic API (api.anthropic.com)
```

**One command to run it:**
```bash
git clone https://github.com/prrabbhanjon/headroom-telemetry-gui.git
cd headroom-telemetry-gui && ./setup.sh install
```

→ **[View the project](https://github.com/prrabbhanjon/headroom-telemetry-gui)**

---

## 🛠 Tech stack

### AI & Automation
![Anthropic](https://img.shields.io/badge/Anthropic-Claude-E67E22?style=flat&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-CLI-8E44AD?style=flat&logo=anthropic&logoColor=white)
![Headroom AI](https://img.shields.io/badge/Headroom_AI-token_compression-1ABC9C?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

### Cloud & Infrastructure
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat&logo=podman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Shell](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

### Frontend & Visualisation
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)

---

## 📦 Repositories

| Project | Description | Stack |
|---------|-------------|-------|
| [headroom-telemetry-gui](https://github.com/prrabbhanjon/headroom-telemetry-gui) | Live AI token savings dashboard on Kubernetes | Python · nginx · K8s · Chart.js |
| [Complete-Python-3-Bootcamp](https://github.com/prrabbhanjon/Complete-Python-3-Bootcamp) | Python 3 course files | Python |
| [python_learning_stuff](https://github.com/prrabbhanjon/python_learning_stuff) | Python learning projects | Python |
| [dotfiles](https://github.com/prrabbhanjon/dotfiles) | Personal dotfiles and shell preferences | Shell |

---

## 💭 What drives me

```python
while True:
    learn()
    build()
    automate()
    share()
    # repeat
```

I believe the best tools are the ones that get out of your way. Whether it's a one-command Kubernetes deployment, a self-healing setup script, or a dashboard that just works — I'm always looking for ways to reduce friction between idea and execution.

Currently exploring: **AI agents · LLM cost optimisation · Kubernetes observability**

---

## 📫 Connect & collaborate

[![GitHub](https://img.shields.io/badge/GitHub-prrabbhanjon-181717?style=flat&logo=github)](https://github.com/prrabbhanjon)

Have an idea, a project, or just want to talk cloud and AI? Open an issue on any of my repos — I read every one.

---

<sub>Subject Matter Expert in Cloud · he/him · United States of America · Creating · Automating · Innovating</sub>
