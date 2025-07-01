---
title: "UltraVision+ Lab - Research"
layout: textlay
excerpt: "UltraVision+ Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

### *Learning to Simplify Sonography*

Freehand ultrasound examinations require significant clinical skill and are time-consuming. To simplify sonography, we develop deep learning methods utilizing real-world ultrasound scanning videos, audio, and probe movement data. Our goal is to offer real-time interpretation and navigation guidance for trainee sonographers, thereby reducing the learning curve and enhancing their confidence. For qualified sonographers, we aim to save their time by automating certain examination procedures.   
**Relevant Publications:**
* Sonomate: Visually grounded language model for fetal ultrasound understanding and human interaction [Nature Biomedical Engineering’25]
* <a href="https://arxiv.org/abs/2408.03761" target="_blank">MMSummary: Multimodal Summary Generation for Fetal Ultrasound Video</a> [MICCAI'24]
* <a href="https://arxiv.org/abs/2408.09931" target="_blank">Pose-GuideNet: Automatic Scanning Guidance for Fetal Head Ultrasound from Pose Estimation</a> [MICCAI'24]

![]({{ site.url }}{{ site.baseurl }}/images/slider7001400/US.png){: style="width: 80%; float: center; margin: 10px"}


# Project

### Automatic Ultrasound Video Summarization for Improved Diagnosis with Simplified Scanning Protocols	

**RGC Early Carrer Scheme (PI), ECS-22203525**

**Abstract:** Ultrasound imaging is a widely used diagnostic tool for visualizing various tissues, such as blood vessels, internal organs, and fetal structures. Compared to X-ray, CT, and MRI, ultrasound offers significant advantages such as being non-radiative, non-invasive, portable, and cost-effective. However, traditional ultrasound examinations rely heavily on the expertise of trained sonographers, making it difficult to scale in underserved areas. Simplified ultrasound scanning protocols have been developed to enable non-experts to acquire diagnostic-quality images, but interpreting these scans is challenging due to the low quality ultrasound video, such as non-standard planes, non-standardized frame sequences, redundant information, and non-informative frames. To address this, we propose novel ultrasound video summarization models aimed at enhancing data quality and diagnostic accuracy while reducing reliance on specialized sonographer skills. First, we propose a standard plane recognition and generation model that reconstructs high-quality standard planes from keyframes identified near anatomical landmarks. This will enable clinicians to extract critical diagnostic information from low-quality sweeps. Second, we introduce a 3D reconstruction model that synthesizes a volumetric representation of the anatomy by estimating the 3D pose of video frames. This comprehensive 3D view will simplify diagnosis and enhance interpretability. Third, we propose a memory-efficient video report generation model that dynamically compresses keyframes into a memory bank for long-term video analysis, providing clinicians with concise, informative textual summaries. Lastly, we introduce a human-interactive video question localization model that allows clinicians to quickly locate and review diagnostically relevant frames by integrating human input into the AI workflow. This research represents a significant step forward in ultrasound video summarization by offering innovative solutions for generating both visual and textual summaries, improving the quality, interpretability, and accessibility of ultrasound examinations. Our approach has the potential to democratize ultrasound diagnostics, particularly in remote and underserved areas, while also advancing the field of medical image analysis.
