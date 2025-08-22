# ML Research Lab 🚀
![CI](https://github.com/Prabingiri/ml-research-lab/actions/workflows/ci.yml/badge.svg)
![Python](https://img.shields.io/badge/python-3.10-blue)
![License](https://img.shields.io/badge/license-MIT-green)

A public journey: daily/weekly math/stats/ML experiments with reproducible infra.

This repo is our **daily research journal**:  
- 🏗️ Infrastructure setup
- 📓 Math, Stats & ML experiments  
- ⚡ Automated pipelines (GitHub Actions, Docker, Terraform)  
- 📊 Weekly reports auto-generated  

## Structure
- `src/` source code modules, utils models
- `experiments/` daily experiments
- `tests/` unit and integration tests
- `docs/` research notes (Markdown)
- `slides/` weekly summaries
- `artifacts/` plots/saved models /datasets/logs (gitignored)
- `notebooks/` scratch only
- `.github/workflows/` CICD workflows

## 🚀 CI/CD
- GitHub Actions runs tests on every push.  
- Dockerfile ensures reproducible environment.  
- Terraform (future) will help us deploy infra.  

---

### ✅ Day 1 Deliverables
- Project structure  
- GitHub Actions CI setup  
- Dockerfile scaffold  

## 🔭 Future Roadmap
- Week 1: Infra setup (CI/CD, Docker, Terraform basics)
- Week 2: Math + Stats refreshers with reproducible experiments
- Week 3: Classic ML (Regression, Trees, SVM)
- Week 4+: Deep Learning mini-projects
- Final: End-to-end capstone pojects 🚀

## 📊 Repo Structure (High Level)

```mermaid
graph TD
    A[ml-research-lab] --> B[src]
    A --> C[experiments]
    A --> D[tests]
    A --> E[docs]
    A --> F[slides]
    A --> G[artifacts]
    A --> H[notebooks]
    A --> I[.github/workflows]
