README — GOI Criterion-Validity Study

Repository Overview

This repository contains the supplementary research materials for the study titled “Does an Integrity-Gated Governance Observability Index Measure Reconstructability? A Criterion-Validity Study of Agent Telemetry under Out-of-Specification Faults.”

The study investigates whether a Governance Observability Index (GOI) reliably reflects the reconstructability of agent execution histories under telemetry degradation, integrity faults, and other out-of-specification conditions.

Study Design

The research uses a controlled, deterministic synthetic simulation testbed. It does not constitute a live evaluation of a large language model, a production AI agent, or a deployed governance system.

The experimental programme comprises 3,520 simulation runs:

E1: 2,520 single-fault or single-perturbation runs.

E2: 1,000 mixed-fault runs.

The master random seed is 20261029. The experiments evaluate the relationship between GOI measurements and reconstruction accuracy under specified fault conditions.

Repository Contents

The supplementary archive (Online_Resource_1_Supplementary.zip) contains the simulation code, analysis scripts, generated run-level data, summary results, and associated reproducibility materials.

Please consult the files and manifest included in the archive for the precise file inventory, version information, execution instructions, and integrity checks.

Reproducibility

The experiments were executed using the supplied simulation and analysis scripts. The archived results were independently regenerated, and the resulting run-level dataset and summary results matched the archived outputs exactly.

The master seed, code version, and SHA-256 hashes are provided in the accompanying reproducibility materials where applicable.

Exact computational reproduction establishes consistency of the supplied implementation and outputs; it does not independently establish the validity of the study's conceptual assumptions, fault model, evaluation criteria, or generalisability to real-world AI systems.

Data and Access

The datasets are synthetically generated for this research. No real-world operational data or personal data were used.

The supplementary archive is made available to support inspection, verification, and reproduction of the reported simulation analyses. Please cite the associated research article and this repository when using these materials.

Limitations

The findings should be interpreted within the boundaries of the synthetic testbed and the specified fault scenarios. The experiments do not establish performance under all possible telemetry failures, adversarial conditions, production workloads, or live AI-agent deployments.

Citation

Please cite the associated manuscript:

NRK, R. S. Does an Integrity-Gated Governance Observability Index Measure Reconstructability? A Criterion-Validity Study of Agent Telemetry under Out-of-Specification Faults. Submitted to the UAEU Journal of Engineering.

Repository DOI: Add the DOI assigned to this repository version by Zenodo or the relevant DOI registration service.

Licence

Refer to the licence specified in this repository before reusing, modifying, or redistributing the code and data.
