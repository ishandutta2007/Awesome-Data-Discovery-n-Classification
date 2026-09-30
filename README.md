# Awesome-Data-Discovery-n-Classification

## Top Data Discovery & Classification Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Sensitive Data Discovery, PII/PHI Classification, DSPM, Labeling, Data Inventory & Privacy Posture*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Discovery & Classification**. These systems scan structured and unstructured data to find, classify, and inventory sensitive information (PII, PHI, secrets, regulated data) across cloud, SaaS, and on-prem estates.



**Examples** include BigID, Varonis, Securiti, Microsoft Purview, Spirion, Netwrix Data Classification, PKWARE, Ground Labs, Egnyte Protect, IBM Guardium, Cyera, Sentra, Netwrix, DataMasque, Titus, and Egnyte (the category leaders).



**Open-source emphasis**: Enterprise DSPM and deep classification are largely commercial. Strong open building blocks exist for **PII detection and anonymization** (Presidio) and **metadata classification** (Apache Atlas, catalog classifiers). This section expands those while remaining realistic about coverage gaps.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[BigID](https://bigid.com/)**  

  Enterprise data discovery, classification, and privacy intelligence platform for hybrid and multi-cloud sensitive data inventory.



- **[Varonis](https://www.varonis.com/)**  

  Data security platform strong on unstructured data discovery, classification, permissions, and access governance.



- **[Securiti](https://www.securiti.ai/)**  

  Data command center for discovery, classification, privacy, and security posture across cloud and SaaS data.



- **[Microsoft Purview](https://azure.microsoft.com/products/purview/)**  

  Microsoft’s unified data governance and classification service with sensitivity labels and DLP integration across M365 and Azure.



- **[Spirion](https://www.spirion.com/)**  

  Sensitive data discovery and classification platform for finding and managing regulated data on endpoints and servers.



- **[Netwrix Data Classification / Netwrix](https://www.netwrix.com/)**  

  Data classification and access governance capabilities for discovering sensitive content and controlling exposure.



- **[PKWARE](https://www.pkware.com/)**  

  Data discovery, classification, and protection platform focused on sensitive data across enterprise environments.



- **[Ground Labs](https://www.groundlabs.com/)**  

  Sensitive data discovery and classification tools for locating regulated data across systems.



- **[Egnyte Protect / Egnyte](https://www.egnyte.com/)**  

  Content governance and classification features within Egnyte for cloud file collaboration environments.



- **[IBM Guardium](https://www.ibm.com/products/guardium)**  

  Data security and monitoring platform with discovery and classification capabilities for databases and data stores.



- **[Cyera](https://www.cyera.io/)**  

  Cloud-native DSPM platform for AI-driven discovery and classification of sensitive data in cloud environments.



- **[Sentra](https://www.sentra.io/)**  

  Data security posture management focused on discovering and classifying sensitive cloud data.



- **[DataMasque](https://datamasque.com/)**  

  Data masking and related discovery/classification tooling for protecting sensitive data in non-production environments.



- **[Titus](https://www.titus.com/)**  

  Data classification and labeling solutions for marking and controlling sensitive information.



## Open-Source GitHub Projects

- **[Presidio](https://github.com/data-privacy-stack/presidio)**  

  Leading open-source framework for detecting, redacting, masking, and anonymizing PII in text, images, and structured data.



- **[Apache Atlas](https://github.com/apache/atlas)**  

  Open-source metadata and governance platform with classification tags (including sensitive/PII-style labels) and lineage.



- **[DataHub / OpenMetadata classifiers](https://github.com/datahub-project/datahub)**  

  Open catalog platforms that support tagging and classification of data assets as part of metadata governance.



- **[OpenDLP-style and file scanners](https://github.com/)**  

  Community tools and scripts for scanning file systems and content for sensitive patterns (regex/PII heuristics).



- **[Regex and NLP PII detection libraries](https://github.com/)**  

  Open libraries for pattern-based and model-based detection of common sensitive entities.



- **[Document and image redaction open tools](https://github.com/)**  

  Projects that combine OCR with Presidio-style redaction for unstructured documents.



- **[Masking and synthetic data open projects](https://github.com/)**  

  Tools that complement discovery by enabling safe use of classified data in lower environments.



- **[Documentation and Presidio playbooks](https://microsoft.github.io/presidio/)**  

  Guides for deploying PII detection pipelines and integrating classification into data workflows.



- **[Self-hosted discovery prototypes](https://github.com/)**  

  Patterns combining Presidio + catalog tags + scheduled scans for limited-scope sensitive data inventory.



- **[Policy and labeling open templates](https://github.com/)**  

  Shared classification taxonomies and labeling schemes for internal governance programs.



### Additional Strong Open-Source Options

- Using **Presidio** for PII detection and anonymization in applications and pipelines.

- Applying classification tags in **Apache Atlas**, **DataHub**, or **OpenMetadata**.

- Building targeted file/content scanners for known high-risk repositories.

- Accepting that enterprise-scale multi-cloud DSPM, continuous posture, automated remediation, and broad connector coverage still require commercial platforms (BigID, Cyera, Varonis, Purview, Securiti, Spirion, etc.).

- Focusing open-source efforts on detection accuracy, privacy-preserving processing, and integration with internal catalogs.



**Frameworks for building custom systems**: Detect with Presidio → tag in an open catalog → restrict access via existing IAM → mask or redact for non-prod. Suitable for application-level PII handling and modest estates. Organizations with large hybrid data footprints typically adopt commercial discovery and classification platforms.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data discovery tools process highly sensitive information. Open-source scanners are not a substitute for regulated DSPM programs. False negatives can leave risk unaddressed. This list is not security or legal advice.



---

**Made for privacy, security, and data governance teams.**

Let's keep sensitive data visible, classified, and protected—with as much openness as practical.
