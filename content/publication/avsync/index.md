---
title: "Detection of Audio-Video Synchronization Errors Via Event Detection"
authors: 
 - Joshua Ebenezer
 - Yongjun Wu
 - Hai Wei
 - Sriram Sethuraman
 - Zongyi Liu
publication_types: ["1"]
publishDate: "2021-01-01T00:00:00Z"
abstract: We present a new method and a large-scale database to detect audio-video synchronization(A/V sync) errors in tennis videos. A deep network is trained to detect the visual signature of the tennis ball being hit by the racquet in the video stream. Another deep network is trained to detect the auditory signature of the same event in the audio stream. During evaluation, the audio stream is searched by the audio network for the audio event of the ball being hit. If the event is found in audio, the neighboring interval in video is searched for the corresponding visual signature. If the event is not found in the video stream but is found in the audio stream, A/V sync error is flagged. We developed a large-scaled database of 504,300 frames from 6 hours of videos of tennis events, simulated A/V sync errors, and found our method achieves high accuracy on the task.
date: "2021-04-20"
math: true
image:
  caption: ''
  focal_point: ''
  preview_only: false

tags:
- Source Themes
featured: true

publication: In *IEEE ICASSP 2021*
publication_short: In *IEEE ICASSP 2021*
url_code: '' 
url_dataset: ''
url_pdf: 'pdf/avsync.pdf'
url_project: ''
url_video: ''
url_poster: ''
url_source: ''


---

