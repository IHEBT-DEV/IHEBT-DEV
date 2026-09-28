# Iheb Touati

**Quantitative Researcher — Islamic Finance**  
Tunis, Tunisia · [SSRN](https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=13219468) · [LinkedIn](https://www.linkedin.com/in/iheb-touati/) · iheb.touati27@gmail.com  
ORCID: [0009-0008-6742-5552](https://orcid.org/0009-0008-6742-5552)

---

## Research — Quantitative Islamic Finance

Building a five-paper mathematical infrastructure for AAOIFI-compliant sukuk pricing under the physical probability measure. Pricing under **P** rather than **Q** is a theological requirement: the Islamic principle of *Al-Ghunm bil-Ghurm* (gain accompanies liability) requires investor compensation to be explicitly coupled to genuine risk-bearing.

### Published Working Papers (SSRN)

**Paper 1** · [SSRN 7485362](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7485362)  
*Variance Reduction Methods for Ijāra Sukuk Pricing Under Stochastic Profit Rates, Correlated Asset Dynamics, and AAOIFI-Mandated Jump-to-Default Risk: A Monte Carlo Approach*

- Correlated GBM/OU dynamics via Cholesky decomposition
- Physical default intensity via jump risk premium for incomplete markets
- Girsanov SDF with path-accumulated stochastic integrals
- Exact joint MGF control variate derived via Itô isometry: Cov(ln S_T, I_T) in closed form
- Monte Carlo SE reduction: **−25.34%** on 65,536 paths

**Paper 2** · [SSRN 7485438](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7485438)  
*Multi-Asset Ijāra Sukuk Pricing Under Correlated GBM Dynamics and Stochastic Profit Rates: A Pooled Asset Framework with Analytical Variance Reduction*

- Full (N+1)-dimensional cross-covariance matrix in closed form via Itô isometry under exact P-measure dynamics
- Asset drift r_t + λσ coupled step-by-step to stochastic profit rate (Girsanov triangle of drifts satisfied path-by-path)
- Generalised joint MGF control variate at **100% theoretical efficiency limit** (ρ = −0.635)
- Formal antithetic variance decomposition: default mirroring contributes **27.84%** of 31.52% total SE reduction

### In Progress

| Paper | Topic |
|-------|-------|
| Paper 3 | HJM term structure for multi-period Ijāra sukuk under AAOIFI constraints |
| Paper 4 | Sharīʿah compliance risk as Poisson jump process calibrated from fatwa data |
| Paper 5 | Portfolio VaR/CVaR for Islamic investment funds with correlated defaults |

---

## Public Repositories

### Quantitative Finance

**[Variance_reduction_techniques](https://github.com/IHEBT-DEV/Variance_reduction_techniques)**  
Monte Carlo option pricing with antithetic variates, control variates, and importance sampling. Direct precursor to SSRN Paper 1.

**[Portfolio_management](https://github.com/IHEBT-DEV/Portfolio_management)**  
Production-grade portfolio risk engine: Modern Portfolio Theory, Single-Index Risk Model, VaR/CVaR, Sharpe/Treynor ratios, Maximum Drawdown. MongoDB/Redis storage, Docker, GitHub Actions CI/CD.

**[Portfolio_managementV1](https://github.com/IHEBT-DEV/Portfolio_managementV1)**  
Earlier Jupyter notebook version: portfolio diversification analysis with quantitative and financial methods.

### AI & Agentic Systems

**[crewai-course-generator](https://github.com/IHEBT-DEV/crewai-course-generator)**  
20-agent adaptive learning content generator. FastAPI, YAML-decoupled agent configs, Docker, multi-provider LLM load balancing for zero-cost infrastructure. Built during Vizuara AI bootcamp.

---

## Technical Stack

**Mathematical:** Stochastic calculus (Itô, Girsanov, Cholesky) · OU & GBM processes · Poisson jump processes · MGF · Monte Carlo variance reduction · VaR/CVaR

**Quantitative tools:** Python (NumPy, SciPy, pandas, scipy.optimize) · LaTeX

**Engineering:** TypeScript · NestJS · FastAPI · PostgreSQL · Redis · Docker · WebSocket · AWS · GitHub Actions · LangGraph · CrewAI

---

## Background

- **Master 2** in Quantitative Finance & Actuarial Sciences — Université du Mans, France *(Mention Assez Bien)*
- **Engineering Degree** in Computer Science (Minor: Financial Computing) — ESPRIT Tunisia *(CTI-accredited)*
- **Analytics Team Lead** at Laevitas (Singapore-registered), Dec 2021 – Oct 2023
- Foundational knowledge in **Fiqh al-Muamalat** (Islamic commercial jurisprudence)

---

*All research is conducted under the physical probability measure P, consistent with AAOIFI Sharīʿah standards and the Islamic principle of Al-Ghunm bil-Ghurm.*
