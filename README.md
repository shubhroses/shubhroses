## Shubhrose Singh

DevSecOps engineer in Palo Alto, California. I build and run Kubernetes platforms, CI/CD pipelines and machine learning infrastructure.

What I work on:

- **Kubernetes platform:** Helm overlays for applications deployed with Argo CD on RKE2 and GKE, and the autoscaling, ingress and Terraform-managed cloud resources around them.
- **CI/CD:** GitLab CI pipelines that build and scan container images and produce an SBOM for each one, and a self-service pipeline for database schema changes.
- **ML infrastructure:** a FastAPI service that runs multi-stage ML pipelines in containers, and automation for serving large language models with vLLM on GPU nodes.

My day-to-day work is in private repositories. The projects here are personal:

- [signed-image-pipeline](https://github.com/shubhroses/signed-image-pipeline): a GitHub Actions pipeline that scans a container image, writes an SBOM, then signs and attests it with keyless cosign, plus a Kyverno policy that admits nothing else. Every release tests nine accept and reject cases on a kind cluster.
- [rocket-telemetry-pipeline](https://github.com/shubhroses/rocket-telemetry-pipeline): a data pipeline over synthetic rocket engine telemetry with a Python generator and cleaner, dbt models for Redshift and a Streamlit dashboard, checked by pytest and `dbt parse` in GitHub Actions.
- [nba-game-prediction](https://github.com/shubhroses/nba-game-prediction): a Prefect flow that lands the live NBA scoreboard in S3, a loader into Snowflake, dbt models over the raw JSON, scikit-learn notebooks that backtest win prediction, and a React app that shows bookmaker favourites.
- [finance-tracker](https://github.com/shubhroses/finance-tracker): a Streamlit dashboard for analysing a stock, comparing tickers and reviewing a portfolio.

Before this I was a data engineer working with Snowflake, dbt and GitLab CI. M.S. Computer Science, Cal Poly Pomona. B.S. Computational Mathematics, UCLA.

[LinkedIn](https://www.linkedin.com/in/shubhrose-s-887abbb4) · [shubhroses.github.io](https://shubhroses.github.io)
