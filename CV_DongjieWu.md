# Dongjie Wu

email: [wodenjay@gmail.com](mailto:wodenjay@gmail.com)

**Research Interests:** Computer Vision, Generative Models, Image Enhancement

## Education

### Central South University, China

*Sep. 2023 – Jun. 2027*

*Bachelor of Engineering in Computer Science and Technology; Double First-Class Initiative, 985 Project*

- **GPA:** 88.21/100
- **Coursework:** Digital Image Processing (94/100), Artificial Intelligence (89/100), Machine Learning (95/100)
- **Awards:** Annual Scholarship for 2023–2024 and 2024–2025

## Publications

- Haitao Nie<sup>\*</sup>, **Dongjie Wu<sup>\*</sup>**, and Bin Xie<sup>✉</sup>, “WaveDE: Wavelet-Routed Dual-Expert Network for Fundus Photograph Enhancement,” in *MICCAI*, 2026. Code: [github.com/WodenJay/WaveDE](https://github.com/WodenJay/WaveDE). [<sup>\*</sup>Equal contribution; <sup>✉</sup>Corresponding author.]
- Haitao Nie<sup>\*</sup>, **Dongjie Wu<sup>\*</sup>**, Bin Xie<sup>✉</sup>, *et al.*, “Controllable Region-Aware Diffusion for High-Fidelity Fundus Enhancement,” manuscript in preparation. Target journal: *Nature Medicine Intelligence*. [<sup>\*</sup>Equal contribution; <sup>✉</sup>Corresponding author.]
- Bin Xie, Yiran Dai, **Dongjie Wu**, and Haitao Nie, “Degradation-Aware Fundus Image Quality Enhancement Method, System, Device, and Medium.” China: CN 202610656256.0.

## Research Experience

### Controllable Region-Aware Diffusion for High-Fidelity Fundus Enhancement

*Sep. 2025 – Present*  
*Advisor: Prof. Bin Xie, Prof. Jing Luo*

- Addressed precise **region of interest enhancement** with minimal hallucination by proposing a controllable region-aware diffusion framework that restores clinician-specified regions while preserving non-selected areas.
- Achieved **+4.13 dB PSNR** over MDA-Net (*MIA* 2024) with consistent gains on SSIM/LPIPS/VIF/Haralick; outperformed 12 recent baselines and improved downstream disease classification and vessel/optic-disc segmentation in both in-domain and OOD settings.
- Built a reproducible end-to-end pipeline for compound degradation modeling, training, and benchmarking across 24 public datasets; the project resulted in a manuscript currently in preparation for **Nature Medicine Intelligence**.

### WaveDE: Wavelet-Routed Dual-Expert Network for Fundus Photograph Enhancement

*Nov. 2025 – Feb. 2026*  
*Advisor: Prof. Bin Xie*

- Addressed the **optimization conflict** between high-frequency details and low-frequency color/illumination in fundus enhancement by designing WaveDE, a wavelet-routed dual-expert architecture with frequency-aware routing.
- Improved detail recovery via HF-injected VAE decoding and enforced structural fidelity via anatomical consistency regularization.
- Achieved **SOTA PSNR/SSIM** among 12 methods from CVPR/ICCV/NeurIPS and other top-tier venues, with consistent gains in downstream tasks. This work led to a **MICCAI 2026** publication.

### Global RETFound: Hunan Ophthalmic Data Curation

*Jul. 2025 – Sep. 2025*  
*Advisor: Prof. Bin Xie, Prof. Jing Luo*

- Extended RETFound, a retinal foundation model pretrained on large-scale fundus and OCT data, by building a model-ready Hunan ophthalmic cohort from the Second Xiangya Hospital for the Global RETFound Consortium.
- Curated ~20K retinal cases through acquisition, cleaning, metadata standardization, image–text alignment, and quality control, covering demographics, camera type, DR, AMD, glaucoma, hypertension, and diabetes.

### Medical VLM Benchmarking for Robustness and Safety Evaluation

*Sep. 2024 – Aug. 2025*  
*Advisor: Prof. Bin Xie*

- Developed a multi-dimensional Med-VLM benchmark to evaluate accuracy, robustness, fairness, and risk aversion under clinically relevant uncertainty and distribution shifts; demo: [consummatewebsite.vercel.app](https://consummatewebsite.vercel.app).
- Built LLM-assisted label verification and safety-evaluation workflows for medical descriptors and Chinese LLM jailbreak benchmarking.

## Awards & Certifications

- National Finalist, 11th National Undergraduate Biomedical Engineering Innovation Design Competition.
- 2025 CCF-CSP Software Talent Certification: 270 points (top 11% nationwide).
- National Third Prize, China College Student Computer Design Competition.
- Third Prize, China Collegiate Computing Competition — AIGC Innovation Track.
