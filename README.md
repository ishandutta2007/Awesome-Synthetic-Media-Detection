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

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Hive](https://thehive.ai/)** | Content moderation and AI-generated media detection APIs across image, video, and audio. | Starting at **$6.00 / 1,000 image requests**, $6.00 / 1,000 video frames, $10.00 / audio hour | **$50 free API credits** on sign-up; default rate limit of 100 requests/day during evaluation + free web demo |
| **[Sensity AI](https://sensity.ai/)** | Visual deepfake and synthetic media detection platform with forensic analysis and threat intelligence. | Starting at **$29.00 / month** (entry-level plan); custom enterprise plans based on scan volume | **7-day free trial** upon sales request for KYC & detection testing; free web demonstration tool |
| **[Reality Defender](https://www.realitydefender.com/)** | Multimodal deepfake detection platform (image, video, audio, text) via API and web app. | Business Plan starting at **$399.00 / month** ($4,788/yr billed annually for 1,000 scans/month) | **Free forever Developer API** with **50 scans/month** (no credit card required) |
| **[GetReal Security](https://www.getrealsecurity.com/)** | Deepfake detection and media authenticity platform protecting enterprise workflows and identity verification. | Starter kits starting at **$500.00 / month** (use-case pilots); custom quotes for enterprise rollouts | **14-day proof-of-concept / pilot trial** available upon request with guided onboarding demo |
| **[Truepic](https://truepic.com/)** | Content authenticity and C2PA-compliant provenance verification platform (Truepic Vision / Lens). | Starting at **$15.00 – $65.00 per inspection** (tiered volume commitment; custom for >10,000/yr) | **14-day free trial** / guided test inspection demo upon request (no permanent free business tier) |
| **[DeepMedia](https://www.deepmedia.ai/)** | Synthetic media and deepfake detection engine (audio, video, face swap, voice clone) for enterprise & defense. | Starting at **$0.01 per detection request** (enterprise pilot packages start at $1,000.00/month) | **14-day pilot evaluation** with sample detection credits upon sales demo request |
| **[Attestiv](https://attestiv.com/)** | Digital media authenticity, tampering analysis, and forensic verification platform for images and video. | Starting at **$49.00 / month** for base commercial API licenses | **Free forever plan** with **5 video scans/month**; **30-day full API trial**; unlimited free tier for journalists |
| **[C2PA Verify](https://c2pa.org/)** | Official open-standard provenance inspector for validating and viewing C2PA Content Credentials. | **$0.00 (100% Free)** open-standard public utility | **Unlimited free in-browser and API manifest verification** (no usage cap, no registration required) |
| **[Optic (AI or Not)](https://aiornot.com/)** | AI-generated media and deepfake detector for images, audio, and synthetic content analysis. | Starting at **$5.00 / month** (includes $10 monthly API credits, pay-as-you-go thereafter) | **Free forever tier** with **10–20 image checks/month** + **$5 free API credits** on sign-up |
| **[Adobe Content Credentials](https://contentauthenticity.org/)** | Adobe's provenance ecosystem tools to inspect, verify, and attach tamper-evident metadata to digital media. | **$0.00 (100% Free)** for Content Authenticity web app (Creative Cloud plans start at $9.99/month) | **Unlimited free access** via Adobe Content Authenticity app & browser inspect tools (requires free Adobe ID) |



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
