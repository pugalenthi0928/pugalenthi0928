# Pugalenthi Magendran

**Applied AI Engineer · Forward Deployed Engineer · AI Solutions Engineer**  
Melbourne, Australia

I turn ambiguous technical problems into inspectable AI systems, secure backend services and rigorous model evaluations. My work is designed around explicit failure boundaries: what the software proves, what remains unknown and how another engineer can verify the difference.

[Portfolio](https://pugalenthimagendran.com) · [Selected work](https://pugalenthimagendran.com/work) · [Résumé](https://pugalenthimagendran.com/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/pugalenthi-magendran-a64912143/)

## Start here

| System | Engineering signal | Inspect |
| --- | --- | --- |
| **SpectraShift** | Hyperspectral transfer, wavelength-aware foundation models, calibration and failure analysis | [Case study](https://pugalenthimagendran.com/projects/spectrashift) · [Source](https://github.com/pugalenthi0928/spectrashift) · [Real-data evidence](https://github.com/pugalenthi0928/spectrashift/tree/main/results/oxhyper-mini) |
| **Forge** | Applied AI, governed data pipelines, release integrity | [Live system](https://training-data-factory-production.up.railway.app/) · [Case study](https://pugalenthimagendran.com/projects/forge) · [Source](https://github.com/pugalenthi0928/training-data-factory) |
| **Adaptive Planning Lab** | Algorithms, simulation, deterministic recovery | [Live lab](https://adaptive-planning-lab.pugalenthi2000.chatgpt.site) · [Case study](https://pugalenthimagendran.com/projects/adaptive-planning-lab) · [Source](https://github.com/pugalenthi0928/adaptive-planning-lab) |
| **AI Change Evidence Engine** | Secure event ingestion, exact correlation, evidence systems | [Live system](https://ai-change-evidence-engine.pugalenthi2000.chatgpt.site) · [Case study](https://pugalenthimagendran.com/projects/ai-change-evidence-engine) · [Source](https://github.com/pugalenthi0928/ai-change-evidence-engine) |
| **Retinal Foundation Model Evaluation** | Model evaluation, low-label transfer, research provenance | [Research case](https://pugalenthimagendran.com/projects/retinal-disease-classifier) · [Source](https://github.com/pugalenthi0928/retinal-foundation-model-evaluation) |

## Flagship evidence

### [SpectraShift hyperspectral foundation-model evaluation](https://github.com/pugalenthi0928/spectrashift)

A wavelength-aware benchmark testing whether a pretrained remote-sensing model transfers to 285-band EMIT imagery under limited labels. It uses source-group-safe splits, transparent baselines, calibration metrics, failure preservation and cited evidence retrieval.

**Current evidence:** 27 automated tests, all 285 sensor bands retained, 111.2M frozen parameters and only 2,307 trainable parameters. On the held-out tile, DOFA improved hematite AUPRC from 0.266 to 0.533 versus spectral-angle mapping. Its ECE rose to 0.776 and two threshold maps became all-positive, so this is a representation-transfer result, not a deployment or mineral-deposit claim.

[Read the case study](https://pugalenthimagendran.com/projects/spectrashift) · [Inspect the real-data result](https://github.com/pugalenthi0928/spectrashift/tree/main/results/oxhyper-mini) · [View CI](https://github.com/pugalenthi0928/spectrashift/actions)

### [Forge training-data engine](https://github.com/pugalenthi0928/training-data-factory)

A source-to-release pipeline with source governance, layered deduplication, contamination controls, source-isolated splits and content-addressed evidence artifacts.

**Current evidence:** 12 declared stages, 7 enforced release gates and 242 automated tests. The hosted smoke release proves the declared controls execute; it does not establish model quality, production safety or genuine human preference.

[Run Forge](https://training-data-factory-production.up.railway.app/) · [Read the case study](https://pugalenthimagendran.com/projects/forge) · [Inspect the controls](https://pugalenthi0928.github.io/training-data-factory/technical.html) · [View CI](https://github.com/pugalenthi0928/training-data-factory/actions)

### [Adaptive Planning Lab](https://github.com/pugalenthi0928/adaptive-planning-lab)

A deterministic multi-agent planning laboratory that shows how a delay breaks a collision-free plan, identifies the affected agents and validates selective recovery independently.

**Current evidence:** three bounded planning strategies, 70 automated tests, 1,200 seeded oracle cases, committed benchmark records and zero conflicts in the reference post-recovery plan. These results apply to the committed bounded scenarios, not production robotics or railway control.

[Run the lab](https://adaptive-planning-lab.pugalenthi2000.chatgpt.site) · [Read the case study](https://pugalenthimagendran.com/projects/adaptive-planning-lab) · [Read the verification record](https://github.com/pugalenthi0928/adaptive-planning-lab/blob/main/docs/evidence/milestone-6-verification.md) · [View CI](https://github.com/pugalenthi0928/adaptive-planning-lab/actions)

### [AI Change Evidence Engine](https://github.com/pugalenthi0928/ai-change-evidence-engine)

A webhook-driven evidence engine that verifies and correlates GitHub change events before evaluating eleven explicit requirements. Merge state, scope, approval and workflow results remain separate facts.

**Current evidence:** 21 automated tests, HMAC-authenticated ingress, retry-safe D1 persistence, exact repository-and-commit correlation and deterministic evidence snapshots. A bounded 100-release local Miniflare benchmark processed 400 operations at 14.67 operations/second; it is not a production load test. The public environment demonstrates the implementation, not production adoption or APRA compliance.

[Open the system](https://ai-change-evidence-engine.pugalenthi2000.chatgpt.site) · [Read the case study](https://pugalenthimagendran.com/projects/ai-change-evidence-engine) · [Inspect the benchmark](https://github.com/pugalenthi0928/ai-change-evidence-engine/blob/main/docs/benchmarks/2026-08-17-local-d1.md) · [Read the threat model](https://github.com/pugalenthi0928/ai-change-evidence-engine/blob/main/docs/threat-model.md) · [View CI](https://github.com/pugalenthi0928/ai-change-evidence-engine/actions)

### [Retinal foundation-model evaluation](https://github.com/pugalenthi0928/retinal-foundation-model-evaluation)

An evidence-aware evaluation companion for zero-shot and limited-label retinal disease classification, developed from my Monash University AI thesis.

**Current evidence:** four model families, three retinal benchmarks and a best reported zero-shot AUROC of 0.921. The headline tables were recovered from the thesis and have not been rerun in this repository; no result is labelled reproduced.

[Read the research case](https://pugalenthimagendran.com/projects/retinal-disease-classifier) · [Inspect the evidence ledger](https://github.com/pugalenthi0928/retinal-foundation-model-evaluation/blob/main/docs/EVIDENCE_LEDGER.md) · [Read the thesis](https://pugalenthimagendran.com/Pugalenthi-Magendran-FLAIR-Thesis.pdf) · [View CI](https://github.com/pugalenthi0928/retinal-foundation-model-evaluation/actions)

### [ClearCurrent water evidence](https://pugalenthimagendran.com/projects/clearcurrent-water-quality)

Evidence-first water-quality decision support for Victoria that preserves authority, freshness, missing evidence and conflicts instead of turning incomplete inputs into a reassuring status.

**Current evidence:** 9,656 attributed EPA Victoria historical records, 35 automated tests and six deterministic failure replays. The operational replay inputs are explicitly synthetic; the system is not an EPA forecast or safety certification.

[Read the case study](https://pugalenthimagendran.com/projects/clearcurrent-water-quality) · [Inspect the public dataset](https://discover.data.vic.gov.au/dataset/beach-report-enterococci-data)

## How I engineer

- Start with the failure mode and define the correctness or evidence contract.
- Keep source facts, derived evidence and human decisions separate.
- Use tests, benchmarks and deterministic replay where they genuinely answer the question.
- Document provenance, limitations and unsupported claims beside the result.
- Build interfaces that let another engineer inspect the system instead of trusting a screenshot.

## Background

Master of Artificial Intelligence from Monash University, with foundation-model research in retinal imaging and an earlier background in finance.
