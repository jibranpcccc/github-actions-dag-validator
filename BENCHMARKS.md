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
