---
title: "HDR-ChipQA: No-Reference Quality Assessment on High Dynamic Range Videos"
authors: 
 - Joshua Ebenezer
 - Zaixi Shang
 - Yongjun Wu
 - Hai Wei
 - Sriram Sethuraman
 - Alan Bovik
publication_types: ["1"]
publishDate: "2023-04-26T00:00:00Z"
abstract: We present a no-reference video quality model and algorithm that delivers standout performance for High Dynamic Range (HDR) videos, which we call HDR-ChipQA. HDR videos represent wider ranges of luminances, details, and colors than Standard Dynamic Range (SDR) videos. The growing adoption of HDR in massively scaled video networks has driven the need for video quality assessment (VQA) algorithms that better account for distortions on HDR content. In particular, standard VQA models may fail to capture conspicuous distortions at the extreme ends of the dynamic range, because the features that drive them may be dominated by distortions {that pervade the mid-ranges of the signal}. We introduce a new approach whereby a local expansive nonlinearity emphasizes distortions occurring at the higher and lower ends of the {local} luma range, allowing for the definition of additional quality-aware features that are computed along a separate path. These features are not HDR-specific, and also improve VQA on SDR video contents, albeit to a reduced degree. We show that this preprocessing step significantly boosts the power of distortion-sensitive natural video statistics (NVS) features when used to predict the quality of HDR content. In similar manner, we separately compute novel wide-gamut color features using the same nonlinear processing steps. We have found that our model significantly outperforms SDR VQA algorithms on the only publicly available, comprehensive HDR database, while also attaining state-of-the-art performance on SDR content.
date: "2023-04-26"
math: true
image:
  caption: ''
  focal_point: ''
  preview_only: false

tags:
- Source Themes
featured: true

publication: arxiv 2023
publication_short: arxiv 2023
url_code: '' 
url_dataset: ''
url_pdf: 'https://arxiv.org/abs/2304.13156'
url_project: ''
url_slides: ''
url_video: ''
url_poster: ''
url_source: ''


---

