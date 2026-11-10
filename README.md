# Awesome AI Governance [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for AI governance, algorithmic auditing, AI safety frameworks, bias detection toolkits, model explainability (XAI), compliance monitoring, and ethical AI standards.

AI governance encompasses the frameworks, technical toolkits, policy standards, and operational controls required to ensure artificial intelligence systems are safe, transparent, ethical, and compliant with global regulations. By integrating model explainability engines, algorithmic bias auditors, watermarking standards, and risk assessment methodologies, organizations can mitigate model drift, privacy risks, and automated discrimination. This list is intended for AI compliance officers, ethics researchers, machine learning auditors, policy analysts, and enterprise AI architects.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Regulatory Frameworks & Risk Taxonomies](#regulatory-frameworks--risk-taxonomies)
- [Algorithmic Auditing & Bias Detection](#algorithmic-auditing--bias-detection)
- [Model Explainability & Interpretability (XAI)](#model-explainability--interpretability-xai)
- [AI Safety & Watermarking](#ai-safety--watermarking)
  - [Safety Benchmarks & Guardrails](#safety-benchmarks--guardrails)
  - [Watermarking & Provenance](#watermarking--provenance)
- [Privacy & Federated Governance](#privacy--federated-governance)
- [Related Awesome Lists](#related-awesome-lists)

## Regulatory Frameworks & Risk Taxonomies

Standardized compliance frameworks, risk management taxonomies, and international AI governance guidelines.

- [NIST AI Risk Management Framework (AI RMF)](https://github.com/usnistgov/microservices-airmf) — Voluntary framework developed by NIST to manage risks to individuals, organizations, and society from AI systems.
- [EU AI Act Explorer](https://github.com/european-union) — Structured reference guide and open alignment documentation covering the European Union Artificial Intelligence Act regulations.
- [ISO/IEC 42001 Standard](https://www.iso.org/standard/81230.html) — International management system standard specifying requirements for establishing and continuously improving AI governance.
- [OECD AI Principles Overview](https://oecd.ai/) — Global policy observatory tracking national AI strategies, safety guidelines, and responsible deployment metrics.

## Algorithmic Auditing & Bias Detection

Open-source libraries and assessment suites for identifying algorithmic bias, demographic disparity, and dataset skew.

- [AIF360 (AI Fairness 360)](https://github.com/Trusted-AI/AIF360) — Extensible open-source toolkit developed by IBM containing metrics and algorithms to detect and mitigate bias in machine learning models.
- [Fairlearn](https://github.com/fairlearn/fairlearn) — Python package for assessing machine learning system fairness and mitigating unfair disparities across demographic groups.
- [Aequitas](https://github.com/dssg/aequitas) — Open-source bias audit toolkit developed for data scientists, analysts, and policymakers to test model predictions for discrimination.
- [What-If Tool](https://github.com/pair-code/what-if-tool) — Visual interactive interface for probing machine learning models, inspecting feature importance, and auditing fairness.

## Model Explainability & Interpretability (XAI)

Tools and libraries providing feature attribution, counterfactual explanations, and model interpretability.

- [SHAP (SHapley Additive exPlanations)](https://github.com/shap/shap) — Game-theoretic approach to explain the output of any machine learning model using Shapley values.
- [LIME (Local Interpretable Model-agnostic Explanations)](https://github.com/marcotcr/lime) — Explanation technique that builds surrogate models locally around individual predictions.
- [Captum](https://github.com/pytorch/captum) — Model interpretability library built on PyTorch providing gradient-based attribution algorithms.
- [InterpretML](https://github.com/interpretml/interpret) — Open-source package incorporating glassbox models and blackbox explainability methods.

## AI Safety & Watermarking

Alignment evaluation, red-teaming toolkits, synthetic content provenance, and output watermarking.

### Safety Benchmarks & Guardrails

- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — Open-source toolkit by NVIDIA for adding programmable guardrails to LLM-based conversational applications.
- [Garak](https://github.com/leondz/garak) — Generative AI Red-teaming & Assessment Kit for probing LLMs for vulnerabilities, hallucination, and prompt injection.
- [Inspect AI](https://github.com/UKGovBEIS/inspect_ai) — Framework created for evaluating AI safety, capabilities, and alignment in foundational models.

### Watermarking & Provenance

- [C2PA Standard (Coalition for Content Provenance and Authenticity)](https://github.com/c2pa-org) — Open technical standard providing cryptographic attribution and origin tracking for digital media.
- [SynthID Integration](https://github.com/google-deepmind) — Technology for watermarking and identifying AI-generated media, audio, and text outputs.

## Privacy & Federated Governance

Differential privacy engines, data anonymization toolkits, and privacy-preserving governance frameworks.

- [Diffprivlib](https://github.com/IBM/differential-privacy-library) — General-purpose Python library developed by IBM for experimenting with and deploying differential privacy mechanisms.
- [OpenMined PySyft](https://github.com/OpenMined/PySyft) — Library decoupling data from model training through secure multi-party computation and federated governance.
- [ARX Data Anonymization Tool](https://github.com/arx-deidentifier/arx) — Comprehensive open-source software for anonymizing sensitive personal data using k-anonymity and l-diversity models.

## Related Awesome Lists

- [Awesome Open-Source AI Models](https://github.com/brandonhimpfen/awesome-open-source-ai-models) — Open-weight foundational LLMs, MoE architectures, and local inference engines.
- [Awesome AI Hardware](https://github.com/brandonhimpfen/awesome-ai-hardware) — AI accelerators, NPUs, TPUs, and specialized execution units.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Best practices, licensing standards, and community governance for open repositories.
- [Awesome Open Data](https://github.com/brandonhimpfen/awesome-open-data) — Public datasets, environmental spatial layers, and scientific data portals.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
