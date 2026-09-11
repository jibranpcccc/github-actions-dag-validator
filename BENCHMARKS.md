# CIPipelineGraph CI/CD Pipeline Optimization & DAG Benchmarks

Job dependency graph parallelization, Docker Buildx cache benchmarks, and GitHub Actions vs GitLab CI pricing metrics.

⚡ **Visualize CI/CD DAGs Live:** [https://site-18-chi.vercel.app/](https://site-18-chi.vercel.app/)

## 1. Docker Build Times in GitHub Actions Runners

| Caching Strategy | Cold Build Duration | Warm Layer Cache Duration | Runner Minutes Consumed |
| :--- | :--- | :--- | :--- |
| GHA Cache (`type=gha,mode=max`) | 8 min 45 sec | 41 seconds | 1 minute |
| Registry Cache (`type=registry`) | 8 min 45 sec | 1 min 15 sec | 2 minutes |
| No Cache | 8 min 45 sec | 8 min 30 sec | 9 minutes |

---
Maintained by [CIPipelineGraph](https://site-18-chi.vercel.app/).

## 📚 In-Depth Technical Implementation Guides

| Target Engineering Query | Production Reference & Guide URL |
| :--- | :--- |
| **Github Actions Vs Gitlab Ci Cost Syntax** | [https://site-18-chi.vercel.app/github-actions-vs-gitlab-ci-syntax-execution-cost-comparison/](https://site-18-chi.vercel.app/github-actions-vs-gitlab-ci-syntax-execution-cost-comparison/) |
| **Matrix Build Optimization Github Actions Cache** | [https://site-18-chi.vercel.app/matrix-build-optimization-github-actions-cache-speed/](https://site-18-chi.vercel.app/matrix-build-optimization-github-actions-cache-speed/) |
| **Github Actions Matrix Include Exclude Syntax** | [https://site-18-chi.vercel.app/github-actions-matrix-syntax/](https://site-18-chi.vercel.app/github-actions-matrix-syntax/) |
| **Act Run Github Actions Local Secrets File** | [https://site-18-chi.vercel.app/act-local-secrets-guide/](https://site-18-chi.vercel.app/act-local-secrets-guide/) |

