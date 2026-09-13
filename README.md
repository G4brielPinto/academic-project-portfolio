# Academic Project Portfolio — Private Registry

This private repository is the control point for a safe academic-project portfolio. It records what
has been prepared, what is deliberately documentation-only and what must not be published until a
specific safety condition is met.

All repositories listed here are private. Nothing is made public from this registry without an
explicit final review.

## Prepared repositories

| Project | Repository | Material included | Status |
| --- | --- | --- | --- |
| DermaMNIST Classification | [repository](https://github.com/G4brielPinto/dermamnist-classification) | Sanitised PyTorch notebooks | Private, ready for review |
| BloodMNIST Generative Models | [repository](https://github.com/G4brielPinto/bloodmnist-generative-models) | cGAN, DCGAN, DDPM and VAE source | Private, ready for review |
| ArtBench Generative Models | [repository](https://github.com/G4brielPinto/artbench-generative-models) | Four model notebooks and a local loader | Private, ready for review |
| Bayesian Insurance Dashboard | [repository](https://github.com/G4brielPinto/bayesian-insurance-dashboard) | Streamlit source, no data | Private, ready for review |
| Visual Analytics Dashboard | [repository](https://github.com/G4brielPinto/visual-analytics-dashboard) | Dash source, no CSV files | Private, ready for review |
| Robot Sensor Fusion | [repository](https://github.com/G4brielPinto/robot-sensor-fusion) | EKF/UKF simulation notebook | Private, ready for review |
| Rolling in the Hill | [repository](https://github.com/G4brielPinto/rolling-hill-evolution) | Unity/GeneticSharp C# scripts only | Private, source-only snapshot |
| BTLNews | [repository](https://github.com/G4brielPinto/btlnews-case-study) | Safe high-level case study only | Private, implementation remains private |
| Global Conflict Analytics | [repository](https://github.com/G4brielPinto/global-conflict-analytics-case-study) | Safe high-level BI case study only | Private, PBIX excluded |
| Pacman-Inspired Game AI | [repository](https://github.com/G4brielPinto/pacman-ai-case-study) | Safe high-level case study only | Private, Unity package excluded |

## Projects queued for a dedicated cleaning pass

| Project | Why it is not yet staged | Next safe action |
| --- | --- | --- |
| Speech-command analysis | Several overlapping scripts, audio data, trained models and personal local paths | Select the canonical final version, move paths to configuration and exclude audio/models |
| Climate Analytics Platform | Raw data, environment configuration and documentation need alignment with the runnable stack | Create a fresh code-only copy after a complete environment and data audit |
| Image-to-Prompt experiments | Large archive with multiple intermediate rounds and platform metadata | Select the final implementation and create a concise reproducible source edition |
| Homomorphic-encryption exercise | Local paths and a large serialised cryptographic context | Publish code only after removing the context and documenting how to regenerate it |
| C++ city graphics exercise | Build outputs and possibly third-party assets are mixed with source | Extract a clean source-and-build-instructions edition |
| RaceEngineerAI | Application code is deliberately outside the portfolio scope | Prepare a high-level case study only, after a separate content review |

## Explicit publication blocks

| Project | Blocking condition | Required action before any repository copy |
| --- | --- | --- |
| Googol distributed search engine | A Google/Gemini API key is present in the source and historical material | Revoke or rotate the key, then create a fresh history-free copy with environment-variable configuration |
| Loan Processing application | AWS credentials were found in a local configuration file | Revoke or rotate the credentials, remove them from the source copy and create a fresh history-free repository |

## Portfolio safety rules

Every prepared repository follows these rules:

1. fresh Git history, never copied academic history;
2. private visibility by default;
3. no datasets, database exports, model weights, generated outputs or reports;
4. no credentials, private links, local machine paths, personal contact details or student identifiers;
5. no individual contribution claim where authorship is uncertain;
6. a README that states the data boundary and limitations;
7. a security scan before the first private push;
8. a second review before any public release.

## Recommended next phase

1. Review the prepared private repositories for technical accuracy and presentation.
2. Decide which two or three code repositories best represent the portfolio publicly.
3. Perform a public-release review on only those chosen repositories.
4. Prepare an account-profile README only after the public selection is approved.
