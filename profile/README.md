<div align="center">

# Neurogica

**Research code from Neurogica Inc., Tokyo.**
Generative and sequence models for the physical world: weather radar, satellite imagery, vision-language grounding, time series and physiological signals.

[![Website](https://img.shields.io/badge/neurogica.com-1e3a5f?logo=googlechrome&logoColor=white)](https://neurogica.com)

</div>

## Publications with code

### ACCV 2026

| Paper | Links |
| :-- | :-- |
| **PG-FMM: Physics-Guided Flow-Map Matching for Precipitation Nowcasting**<br>A frozen Lagrangian advection prior carries the motion; a few-step flow-map generator renders the detail. Best on 18 of 24 metrics across four radar benchmarks. | [![Code](https://img.shields.io/github/stars/Neurogica/PG-FMM?style=flat&label=PG-FMM&logo=github)](https://github.com/Neurogica/PG-FMM) [![Project page](https://img.shields.io/badge/Project_page-1e3a5f)](https://neurogica.github.io/PG-FMM/) |
| **FORUM: Frozen Outputs Reconciled Using Model Agreement for Visual Grounding**<br>Training-free test-time fusion of frozen MLLMs: agreement-based selection plus medoid localization. Three open models surpass a 397B single model on adversarial Ref-Adv-s. | [![Code](https://img.shields.io/github/stars/Neurogica/FORUM?style=flat&label=FORUM&logo=github)](https://github.com/Neurogica/FORUM) |
| **PoE-Fuse: Precision-Weighted Expert Fusion for Bi-Temporal Change Understanding**<br>Frozen geometry, grounding and language experts fused by learned per-cell precision; one trunk solves change detection, building localization and damage classification. | [![Code](https://img.shields.io/github/stars/Neurogica/PoE-Fuse?style=flat&label=PoE-Fuse&logo=github)](https://github.com/Neurogica/PoE-Fuse) |

### ICASSP 2026

| Paper | Links |
| :-- | :-- |
| **A Decomposition-Based State Space Model for Multivariate Time-Series Forecasting** (oral)<br>Three parallel deep state-space branches for trend, seasonal and residual components with adaptive temporal scales. | [![arXiv](https://img.shields.io/badge/arXiv-2602.05389-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.05389) [![Code](https://img.shields.io/github/stars/Neurogica/DecompSSM?style=flat&label=DecompSSM&logo=github)](https://github.com/Neurogica/DecompSSM) |
| **PENGUIN: General Vital Sign Reconstruction from PPG with Flow Matching State Space Model**<br>Reconstructs heart rate, respiration and related vital signs from PPG with a flow-matching state-space model. | [![arXiv](https://img.shields.io/badge/arXiv-2602.03858-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2602.03858) [![Code](https://img.shields.io/github/stars/Neurogica/PENGUIN?style=flat&label=PENGUIN&logo=github)](https://github.com/Neurogica/PENGUIN) |

### Preprints

| Paper | Links |
| :-- | :-- |
| **Learning Where to Look: A Shared Relative-Alignment Module for Time-Series Forecasting and PPG-to-Vital-Sign Reconstruction**<br>ROOSTER, a periodic-comb attention bias that learns whether to read the same position or one season back, shared by forecasting and reconstruction. | [![arXiv](https://img.shields.io/badge/arXiv-2609.27473-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2609.27473) [![Code](https://img.shields.io/github/stars/Neurogica/ROOSTER?style=flat&label=ROOSTER&logo=github)](https://github.com/Neurogica/ROOSTER) |
| **Forecast Workflow Bench: Evaluating Language-Model Decisions with Budgeted Forecast Tools**<br>FWBench scores how language models select and use paid time-series forecasts to make capacity decisions under a budget. | [![arXiv](https://img.shields.io/badge/arXiv-2609.27385-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2609.27385) |
| **TERN: A Delta-Rule Memory with a Seasonal Reference and Online Adaptation for Epidemic Forecasting**<br>An erase-then-delta fast-weight memory gated by epidemic-phase features, with a seasonal reference and online adaptation, for weekly surveillance counts. | [![arXiv](https://img.shields.io/badge/arXiv-2609.18407-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2609.18407) [![Code](https://img.shields.io/github/stars/Neurogica/TERN?style=flat&label=TERN&logo=github)](https://github.com/Neurogica/TERN) |

## Research areas

- **Physical-world generation**: precipitation nowcasting with physics-guided flow-map matching; bi-temporal change understanding from satellite imagery.
- **Frozen-model composition**: test-time fusion of multimodal LLMs and precision-weighted fusion of foundation experts, with no fine-tuning.
- **Time series and physiological signals**: state-space and relative-alignment models for forecasting, PPG-to-vital-sign reconstruction, epidemic forecasting, and benchmarks for forecast-driven decisions.

Joint work with the Media Dynamics Laboratory at Hokkaido University, LTS, Inc. and ME-Lab Japan, Inc. appears under the respective papers.

## Using our code

Each repository has a README with installation and the commands that reproduce the paper's results; the license is stated in each repository. Issues and pull requests are welcome.
