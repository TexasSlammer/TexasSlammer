## Hi, I'm Mark 👋

Graduate candidate at **The University of Texas at Austin**, focused on detection engineering, threat intelligence, and securing AI agent tooling.

I engineer detections and prove they work. Cloud identity attack-path analysis, Sigma/SIEM detection engineering, and upstream security research. Every number below is reproducible from the linked repo.

![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3776AB) ![Linux](https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=FCC624) ![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=009688) ![Semgrep](https://img.shields.io/badge/Semgrep-0D1117?style=flat-square) ![Sigma](https://img.shields.io/badge/Sigma-0D1117?style=flat-square) ![Wazuh](https://img.shields.io/badge/Wazuh-0D1117?style=flat-square) ![MITRE%20ATT%26CK](https://img.shields.io/badge/MITRE_ATT%26CK-0D1117?style=flat-square) ![SIEM](https://img.shields.io/badge/SIEM-0D1117?style=flat-square)

### Featured work

| Project | What it is | Result |
| --- | --- | --- |
| [**upstream-semgrep-contribution**](https://github.com/TexasSlammer/upstream-semgrep-contribution) | Found and fixed false negatives in Semgrep's `avoid-pyyaml-load` rule (CWE-502), with full evidence package; filed upstream as [issue #4135](https://github.com/semgrep/semgrep-rules/issues/4135) | 7 → 17 probe detections · 0 new false positives across 3,578 files · 8 positive + 6 negative regression tests |
| [**specter-x**](https://github.com/TexasSlammer/specter-x) | Cloud identity attack-path analysis: permission graphs, explainable risk scoring, FastAPI + RBAC, investigation workflows | 94 backend tests · 7/7 reachable paths, 5/5 denials · 1M-event ingestion at 5,797 events/sec |
| [**detection-range**](https://github.com/TexasSlammer/detection-range) | Segmented AD lab validating Sigma detections with Atomic Red Team and real captured EVTX telemetry | 7/11 → 11/11 labeled detections · 768 captured Windows events evaluated |
| [**mcp-testbed**](https://github.com/TexasSlammer/mcp-testbed) | Harmless malicious AI-agent tool-behavior testbed with Sigma/Wazuh detections | 8/8 behaviors exercised · 11/12 malicious cases detected · 0/7 benign alerted |
| [**ct-watcher**](https://github.com/TexasSlammer/ct-watcher) | Certificate Transparency phishing-domain detection with homoglyph/typosquat scoring, auto-block in OPNsense | 28/29 malicious lookalikes detected · 0/19 benign flagged |


📫 [LinkedIn](https://www.linkedin.com/in/mark-lambert-7121a1208/)
