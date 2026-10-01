# Awesome-Digital-Forensics-Platform

# Top Digital Forensics Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Disk & Mobile Forensics, Memory Analysis, Evidence Processing, DFIR Workstations & Investigative Platforms*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Forensics**. These systems acquire, preserve, analyze, and report on digital evidence from computers, mobile devices, cloud, and memory for investigations and incident response.

**Examples** include Magnet AXIOM, Cellebrite Inseyets, MSAB XRY, OpenText EnCase, Exterro FTK, Belkasoft X, Oxygen Forensics, Paraben E3, Grayshift GrayKey, Sumuri RECON, Griffeye Analyze DI, and X-Ways Forensics (the category leaders).

**Open-source emphasis**: Digital forensics has one of the strongest open tool ecosystems. **Autopsy**, **The Sleuth Kit**, **Volatility**, **Plaso**, **Velociraptor**, and **Timesketch** are industry-standard. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Magnet AXIOM / Magnet Forensics, Cellebrite, MSAB XRY](https://www.magnetforensics.com/)**  
  Leading commercial platforms for computer, mobile, and cloud forensics with advanced artifact parsing and analytics.

- **[OpenText EnCase, Exterro FTK, X-Ways Forensics](https://www.opentext.com/)**  
  Classic enterprise forensic suites for disk imaging, analysis, and court-ready reporting.

- **[Belkasoft X, Oxygen Forensics, Paraben E3, Sumuri RECON](https://belkasoft.com/)**  
  Comprehensive DFIR tools covering endpoints, mobile, and specialized evidence types.

- **[Grayshift GrayKey, Griffeye Analyze DI](https://www.grayshift.com/)**  
  Specialized mobile unlock/extraction and media analysis platforms used by law enforcement.

- **[Other commercial digital forensics platforms](https://www.magnetforensics.com/)**  
  Additional cloud forensics, eDiscovery-adjacent, and lab management solutions.

## Open-Source GitHub Projects

- **[Autopsy](https://github.com/sleuthkit/autopsy)**  
  Leading open-source digital forensics platform—GUI on The Sleuth Kit for disk analysis, timelines, keyword search, and reporting.

- **[The Sleuth Kit (TSK)](https://github.com/sleuthkit/sleuthkit)**  
  Foundational open library and CLI tools for volume and file-system forensic analysis.

- **[Volatility / Volatility 3](https://github.com/volatilityfoundation/volatility3)**  
  Industry-standard open memory forensics framework for RAM analysis and malware investigation.

- **[Plaso (log2timeline)](https://github.com/log2timeline/plaso)**  
  Open super-timeline engine—extracts timestamps from many artifact sources into a unified timeline.

- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  
  Open endpoint visibility and DFIR collection tool—live response, hunting, and artifact gathering at scale.

- **[Timesketch](https://github.com/google/timesketch)**  
  Open collaborative forensic timeline analysis platform for multi-investigator casework.

- **[GRR Rapid Response](https://github.com/google/grr)**  
  Open remote live forensics framework for incident response across large fleets.

- **[Dissect / IPED / Chainsaw](https://github.com/fox-it/dissect)**  
  Open evidence access, large-case processing, and Windows artifact triage tools used in modern DFIR.

### Additional Strong Open-Source Options

- **Disk workstation**: Autopsy + The Sleuth Kit.
- **Memory**: Volatility 3.
- **Timelines**: Plaso + Timesketch.
- **Live response**: Velociraptor or GRR.
- **Composable stacks**: Imaging (Guymager/dc3dd) → Autopsy/TSK → Plaso → Timesketch; Velociraptor for enterprise IR.
- Commercial platforms still lead in mobile unlock depth, polished artifact parsers, and vendor support for court testimony.

**Frameworks for building custom systems**:  
**Autopsy** + **TSK** for disk; **Volatility** for memory; **Plaso** + **Timesketch** for timelines; **Velociraptor** for fleet IR.  
Commercial tools (Magnet, Cellebrite, EnCase, FTK, etc.) add mobile, cloud, and lab workflow depth.  
Many labs run hybrid open + commercial toolchains. Fully open digital forensics is production-viable for disk, memory, and many IR scenarios; specialized mobile extraction often requires commercial solutions.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Only examine systems and data you are legally authorized to investigate. Maintain chain of custody, write-blocking, and documentation suitable for your jurisdiction. Bypassing device security may be restricted by law.
- Open-source tools are transparent and widely accepted in court when used properly, but operators must validate methods. Commercial platforms provide vendor support and specialized parsers. Neither replaces trained examiners and lawful process.

---

**Made for DFIR analysts, forensic examiners, and incident response teams.**  
Let's expand open forensic science while recognizing the specialized mobile and lab capabilities that leading commercial platforms deliver.
