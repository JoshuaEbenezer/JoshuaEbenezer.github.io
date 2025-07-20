---
title: "Making Video Quality Assessment Models Robust to Bit Depth"
authors: 
 - Joshua Ebenezer
 - Zaixi Shang
 - Yongjun Wu
 - Hai Wei
 - Sriram Sethuraman
 - Alan Bovik
publication_types: ["1"]
publishDate: "2023-04-20T00:00:00Z"
abstract: We introduce a novel feature set, which we call HDRMAX features, that when included into Video Quality Assessment (VQA) algorithms designed for Standard Dynamic Range (SDR) videos, sensitizes them to distortions of High Dynamic Range (HDR) videos that are inadequately accounted for by these algorithms. While these features are not specific to HDR, and also augment the equality prediction performances of VQA models on SDR content, they are especially effective on HDR. HDRMAX features modify powerful priors drawn from Natural Video Statistics (NVS) models by enhancing their measurability where they visually impact the brightest and darkest local portions of videos, thereby capturing distortions that are often poorly accounted for by existing VQA models. As a demonstration of the efficacy of our approach, we show that, while current state-of-the-art VQA models perform poorly on 10-bit HDR databases, their performances are greatly improved by the inclusion of HDRMAX features when tested on HDR and 10-bit distorted videos.
date: "2023-04-20"
math: true
image:
  caption: ''
  focal_point: ''
  preview_only: false

tags:
- Source Themes
featured: true

publication: In *IEEE Signal Processing Letters 2023*
publication_short: In *IEEE SPL 2023*
url_code: '' 
url_dataset: ''
url_pdf: 'https://arxiv.org/abs/2304.13092'
url_project: ''
url_slides: ''
url_video: ''
url_poster: ''
url_source: ''


---

