---
layout: page
title: "Speakers"
permalink: /speakers/
---
All speakers are confirmed. Titles are tentative

---

#### Zheng-Hua Tan
* **Affiliation:** Aalborg University, Denmark
* **Title:** Professor of Machine Learning and Speech Processing
* **Website:** [Aalborg University Profile](https://zhenghuatan.es.aau.dk/)
* **Title:** Self‑Supervised Learning and Alignment for Large Multimodal Models

**Abstract**
Self‑supervised learning (SSL) has become a central approach for training large multimodal models that learn from audio, vision, and language at scale, precisely because it requires no human labels. This talk introduces the core concepts and methods of SSL and shows how them form the foundation for building powerful multimodal systems. We will discuss how SSL enables effective pre-training and how such pre-trained models can be adapted to a wide range of downstream tasks. The talk will highlight several application domains, with an emphasis on audio and image data, including the development of multimodal language models.

While SSL leverages vast amounts of unlabelled data, there is often a significant mismatch between pre-trained representations and the downstream objectives, leading to poor alignment. In the second part of the talk - alignment - we will examine strategies to ensure that pre-trained models are aligned with downstream goals and real-world requirements. We will show how SSL and alignment together drive progress in modern multimodal AI.

**Bio**
Zheng-Hua Tan is a Professor of Machine Learning and Speech Processing, a Co-Head of the Centre for Acoustic Signal Processing Research (CASPR), and the Machine Learning Research Group Leader in the Department of Electronic Systems at Aalborg University, Denmark. He is a Co-Lead of Pioneer Centre for Artificial Intelligence, Denmark.

He was a Visiting Scientist/Professor at the Computer Science and Artificial Intelligence Laboratory (CSAIL), Massachusetts Institute of Technology (MIT), Cambridge, USA, and an Associate Professor with the Department of Electronic Engineering, SJTU, Shanghai, China. 

His research interests include machine learning, deep learning, noise-robust speech processing, and multimodal signal processing. He has co-authored 300 peer-reviewed papers. His works have been recognized by the IEEE Signal Processing Society 2022 Best Paper Award and International Speech Communication Association 2022 Best Research Paper Award. He is the Lead Editor for IEEE Journal of Selected Topics in Signal Processing Special Series on AI in Signal and Data Science. He served as the elected Chair of IEEE SPS Machine Learning for Signal Processing Technical Committee, a Member of IEEE SPS Technical Directions Board and Conferences Board, an Associate Editor for the IEEE TRANSACTIONS ON AUDIO, SPEECH AND LANGUAGE PROCESSING. He is the General Chair for ICASSP 2029 (Copenhagen) and a TPC Co-Chair for ICASSP 2028 (Tokyo). He was a TPC Vice-Chair for ICASSP 2024 (Seoul) and the General Chair for IEEE MLSP 2018 (Aalborg).

---

#### Tom Kelly
* **Affiliation:** British Antarctic Survey
* **Website:** [BAS Profile](https://www.bas.ac.uk/profile/thokel/)
* **Title:** L4 Sea Ice Dataset

**Abstract**
Antarctic sea ice is an essential climate variable, critical to navigation, forecasting, and conservation. However, Earth observation in this region is severely constrained by persistent cloud cover, prolonged darkness, and highly dynamic surface conditions characterized by rapid ice drift and variable snowfall. To address these deficits, we introduce L4 - Large-scale, Low-Latency & Low-Level Antarctic Datasets. To mitigate temporal latency in dynamic ice, L4 enforces strict temporal co-registration: Sentinel-1 (S1) and MODIS acquisitions are paired within one hour, while AMSR2 overlaps are constrained to six hours. To overcome optical limitations, L4 leverages active radar (S1) and passive microwave (AMSR2) sensors capable of continuous acquisition.

L4 encompasses a pretraining and finetuning partitions of chips covering Antarctic ice in coincident S1, MODIS, and AMSR2, channels, as well as metadata including per-pixel location, incidences, and ERA5 atmospheric variables. We demonstrate the dataset by training a geospatial foundation model on L4, applying the MultiMAE architecture to model missing modalities, such as S1:HV failures. Our results demonstrate that pretraining on L4 improves sea ice prediction efficacy compared to conventional supervised learning. Looking forward, L4 will facilitate automated validation of the AMSR2-derived sea ice record, enable the spatial representation of PM uncertainty, and support rigorous sensitivity analyses of the ubiquitous 15% sea ice area threshold.

**Bio**
Tom is a lost computer graphics researcher, who has found himself working at BAS (the British Antarctic Survey). Along the way he's worked as a video games programmer, bar staff, lecturer, and software engineer at ESRI. In academia, during his computer graphics PhD and postdoc, he invented new geometric primitives as well as learning the hardware and software skills for the nascent ML revolution, to publish at venues including CVPR, NeurIPS, Siggraph, ICCV, and Eurographics, Recently, Tom has applied his interest in all things visual to procedural and synthetic data, foundation models, and earth observation of the cryosphere.

---

#### Elena Tomasi
* **Affiliation:** Fondazione Bruno Kessler (FBK)
* **Website:** [FBK profile](https://magazine.fbk.eu/en/spotlight/elena-tomasi/)
* **Title:** Diffusion models and downscaling

**Abstract**
To appear.

---

#### Louisa Van Zeeland
* **Affiliation:** The Alan Turing Institute
* **Website:** [The Alan Turing Institute Profile](https://www.turing.ac.uk/people/louisa-van-zeeland)
* **Title:** Multimodal sea ice forecasting


**Abstract**
All 19 of the lowest Arctic September minimum extents on record have occurred in the last 19 years, yet the rapid, unpredictable nature of recent change is outpacing traditional physics-based models. IceNet-MP is an open-source multimodal deep learning pipeline built around an encode-process-decode architecture, with a vision transformer as one of the core processors, and an in-development diffusion model for probabilistic forecasting. Designed to ingest heterogeneous datasets simultaneously, IceNet-MP incorporates new observation streams as additional encoders without redesigning the core model. Argo float data have been integrated as a first new input modality, with forecast skill evaluation ongoing.

**Bio**
Louisa van Zeeland is a research lead at the Alan Turing Institute, where she leads development of IceNet-MP, a multimodal deep learning pipeline for sea ice forecasting in support of Arctic resilience. With over 20 years of ML experience at organizations like Stanford Research Institute, Vulcan, and AI2, her work spans ocean health, biodiversity, and environmental forecasting.

---

#### Lorenzo Zampieri
* **Affiliation:** European Centre for Medium-Range Weather Forecasts (ECMWF)
* **Website:** [ECMWF Profile](https://www.ecmwf.int/en/about/who-we-are/staff-profiles/lorenzo-zampieri)
* **Title:** Observational Requirements in the Context of AI Prediction Systems for Sea Ice: Introducing ORCAS, a PCAPS Task Team and SCOR Working Group

**Abstract**
Recent advances in artificial intelligence (AI) are transforming sea-ice forecasting. Data-driven models now achieve skill comparable to, and sometimes exceeding, traditional physics-based systems while requiring far fewer computational resources. However, forecast skill alone is not sufficient: the credibility of AI systems depends on their physical realism and consistency with observed polar processes.

ORCAS (Observational Requirements in the Context of AI prediction systems for Sea ice) is a Task Team of the WMO World Weather Research Programme’s Polar Coupled Analysis and Prediction for Services (PCAPS) project and a SCOR Working Group. It brings together experts in sea-ice observations, numerical modelling, and AI-based prediction to systematically assess how observations can be used to evaluate and strengthen AI-driven sea-ice forecasts up to seasonal timescales.

A central goal of ORCAS is to probe the physical consistency of AI models using observations. Beyond standard skill metrics, we assess whether AI forecasts respect known physical relationships, conservation constraints, and coupled sea ice–ocean–atmosphere processes. Using historical field campaigns such as MOSAiC and Antarctica InSync, we design coordinated validation scenarios in which AI and physics-based systems are benchmarked against in situ, airborne, satellite, and reanalysis datasets.

By identifying underutilised observations and testing models across representative and extreme polar conditions, ORCAS aims to develop internationally agreed benchmarking approaches and guide future observing strategies, including preparations for the Fifth International Polar Year (IPY5). Our objective is to ensure that next-generation AI sea-ice forecasts are physically grounded, trustworthy, and operationally relevant.

---

#### Simon Driscoll
* **Affiliation:** University of Cambridge
* **Title:** Assistant Research Professor
* **Website:** [University of Cambridge Profile](https://www.maths.cam.ac.uk/person/sd2136)
* **Title:** Observationally based AI emulation of Arctic sea ice processes

**Abstract**
Melt ponds play a central role in sea-ice thermodynamics through their strong control on albedo and are a key component of the ice–albedo feedback that drives Arctic amplification. Despite their importance, melt pond processes remain insufficiently represented in current models, contributing substantial uncertainty in projections of Arctic sea ice state and loss. At the same time, spring melt pond fraction is known to be a strong predictor of September sea-ice extent, indicating that melt ponds play an important role on seasonal forecasting timescales.

Our previous work has shown both the strong sensitivity of sea-ice predictions to melt pond parametrisations and the ability of neural networks to learn and replace such parametrisations from model data, running stably and without drift over long simulations. Building on this, I introduce an observationally trained melt pond emulator. This emulator captures observed variability, can be integrated into a sea-ice model, and improves sea ice model predictions when compared to existing physics-based parametrisations.

These results demonstrate a new pathway for climate model development: learning parametrisations directly from observations, deploying them stably within models, and improving physical realism. Because melt ponds are tightly linked to seasonal Arctic sea-ice predictability, improving their representation offers a direct route to enhancing forecasts of sea-ice extent and ice-free conditions, bridging process-based modelling and emerging AI-driven approaches. This fits within our broader portfolio of building emulators across a range of geophysical processes.

Our previous work has shown both the strong sensitivity of sea-ice predictions to melt pond parametrisations and the ability of neural networks to learn and replace such parametrisations from model data, running stably and without drift over long simulations. Building on this, I introduce an observationally trained melt pond emulator. This emulator captures observed variability, can be integrated into a sea-ice model, and improves sea ice model predictions when compared to existing physics-based parametrisations.

These results demonstrate a new pathway for climate model development: learning parametrisations directly from observations, deploying them stably within models, and improving physical realism. Because melt ponds are tightly linked to seasonal Arctic sea-ice predictability, improving their representation offers a direct route to enhancing forecasts of sea-ice extent and ice-free conditions, bridging process-based modelling and emerging AI-driven approaches. This fits within our broader portfolio of building emulators across a range of geophysical processes.

**Bio**
Dr. Simon Driscoll is an Assistant Research Professor in the Department of Applied Mathematics and Theoretical Physics at the University of Cambridge. He has a background training in pure and applied mathematics, and completed a DPhil (PhD) in physics at the University of Oxford. His earliest research focused on volcanic eruptions, stratosphere-troposphere dynamics, climate modelling and impacts of aerosols on climate.  His doctoral research featured in major European newspapers and books, and formed the basis of a documentary broadcast on Belgian national television. More recently he has switched from traditional modelling approaches into to AI research. Recently, Simon's research spans applied mathematics (eg. applications of Koopman theory), mathematical modelling, machine learning and artificial intelligence, climate science, econometrics and migration. Simon is the lead author of a comprehensive textbook on artificial intelligence across climate and the environmental sciences, available in major bookstores throughout Europe and North America. Recent cryospheric research - including cryospheric observations and remote sensing, the creation of emulators for Arctic sea ice modelling and Antarctic glaciology, and the implications for forecasting - will be the focus of his presentation at this workshop.

