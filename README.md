# Awesome-Synthetic-Media-Detection

## Top Synthetic Media Detection Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Deepfake Detection, AI-Generated Content Identification, Content Provenance (C2PA), Media Authenticity & Trust Signals*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Synthetic Media Detection**. These systems analyze images, video, audio, and text to identify AI-generated or manipulated content, support content provenance standards, and help platforms, enterprises, and journalists assess media authenticity.



**Examples** include Hive, Sensity AI, Reality Defender, GetReal Security, Truepic, DeepMedia, Attestiv, C2PA Verify, Optic, and Adobe Content Credentials (the category leaders).



**Open-source emphasis**: Synthetic media detection has a vibrant research and open-source ecosystem. **C2PA SDKs**, **Defakepy**, open deepfake detection models, and related forensic toolkits provide strong building blocks. This section is expanded with the most relevant open projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Hive](https://thehive.ai/)**  

  Content moderation and AI-generated content detection APIs covering images, video, and audio, frequently used at scale for platform trust-and-safety workflows.



- **[Sensity AI](https://sensity.ai/)**  

  Visual deepfake and synthetic media detection platform with forensic analysis and threat-intelligence capabilities focused on manipulated faces and video.



- **[Reality Defender](https://www.realitydefender.com/)**  

  Multimodal deepfake detection platform (image, video, audio, text) delivered via API, targeting enterprise, financial, and media use cases.



- **[GetReal Security](https://www.getrealsecurity.com/)**  

  Media authenticity and deepfake detection solutions oriented toward enterprise and security-conscious organizations.



- **[Truepic](https://truepic.com/)**  

  Content authenticity platform combining capture-time verification, provenance, and detection capabilities for trusted media.



- **[DeepMedia](https://www.deepmedia.ai/)**  

  Synthetic media detection and analysis tools focused on identifying AI-generated or manipulated audiovisual content.



- **[Attestiv](https://attestiv.com/)**  

  Digital media authenticity and verification platform supporting provenance and integrity checks for images and documents.



- **[C2PA Verify / Content Authenticity tools](https://c2pa.org/)**  

  Verification services and tooling aligned with the Coalition for Content Provenance and Authenticity (C2PA) standard for inspecting content credentials.



- **[Optic](https://www.optic.com/)**  

  Solutions related to media verification and synthetic content detection in the broader authenticity ecosystem.



- **[Adobe Content Credentials](https://www.adobe.com/)**  

  Adobe’s implementation of content credentials and provenance features (part of the Content Authenticity Initiative) for creators and consumers of media.



## Open-Source GitHub Projects

- **[C2PA Rust SDK (c2pa-rs)](https://github.com/contentauth/c2pa-rs)**  

  Official open-source Rust SDK for creating, signing, embedding, and validating C2PA manifests — the core technical standard for content provenance and authenticity.



- **[Defakepy](https://github.com/ftralliance/defakepy)**  

  Open-source Python library for detecting AI-generated content across text, images, audio, and video. Modular design with ensemble forensic techniques and C2PA provenance checks.



- **[TrueMedia open models and components](https://github.com/truemediaorg)**  

  Open-source deepfake detection models, media resolvers, and related tooling released by TrueMedia.org for multi-modal synthetic media analysis.



- **[DeepFake-Detect and training pipelines](https://github.com/)**  

  Open pipelines for training deepfake and face-forgery detectors on public benchmarks (FaceForensics++, Celeb-DF, DFDC, etc.) using modern backbones.



- **[CLIP-based and transformer deepfake detectors](https://github.com/)**  

  Research implementations (e.g., C2P-CLIP and similar) that adapt vision-language models for improved generalization in deepfake and synthetic image detection.



- **[Synthetic image forensic detectors](https://github.com/)**  

  Academic open-source detectors for distinguishing real vs. synthetic images, including analysis of diffusion-model “laundering” and related artifacts.



- **[Audio deepfake / spoofing detection models](https://github.com/)**  

  Open implementations of AASIST, RawNet2, and related architectures for detecting synthetic or converted speech.



- **[Multi-modal deepfake benchmarks and evaluation suites](https://github.com/)**  

  Public datasets and evaluation frameworks (including recent in-the-wild benchmarks) used to measure detector robustness against modern generative models.



- **[Content Authenticity Initiative open tools](https://github.com/contentauth)**  

  Broader open-source ecosystem around C2PA, including additional language bindings, verification utilities, and example integrations.



- **[Browser and local forensic helper tools](https://github.com/)**  

  Lightweight open utilities for inspecting metadata, C2PA manifests, and basic statistical or biological signals (e.g., blink patterns) in media files.



### Additional Strong Open-Source Options

- Ensemble approaches that combine multiple open detectors for higher robustness.

- Integration of C2PA validation into content pipelines and CMS platforms.

- Fine-tuning open models on domain-specific or newly released generative outputs.

- Jupyter / notebook environments for exploratory forensic analysis of suspect media.

- Community-maintained lists of public deepfake datasets and challenge leaderboards.



**Frameworks for building custom systems**: Use the **C2PA SDK** to read and validate content credentials wherever present, then layer open detection models (Defakepy, TrueMedia models, research detectors) for probabilistic analysis of unsigned or suspicious media. Combine signals (metadata, model scores, biological cues, spectral analysis) into a trust score and surface results through internal tools or moderation queues. This stack provides transparency and full control over detection logic — valuable for research, platforms with specialized threat models, or organizations needing on-premise processing — while commercial services still lead in continuously updated model ensembles, scale, and managed API reliability against the latest generative systems.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Synthetic media detection is inherently probabilistic and constantly challenged by improving generative models. Open-source detectors can lag behind the latest techniques and should never be treated as definitive proof of authenticity or manipulation. Always combine automated signals with human review, especially in high-stakes contexts (journalism, legal, elections, security).

- Respect privacy, copyright, and applicable laws when analyzing media. Detection tools can produce false positives and false negatives; use them responsibly.



---

**Made for trust & safety teams, journalists, researchers, and platforms defending media integrity.**

Let's make content authenticity and synthetic media detection more transparent, open, and collaboratively improved.
