---
layout: archive
title: ""
permalink: /counter-uas/
author_profile: true
---
# Vision-based Detection of Unmanned Air Systems for Counter-UAS

Fusing visible and long-wave infrared (LWIR) spectrum cameras to automatically detect UAS, or drones, at any period of the day. This research was winner of the 2020 SPIE Automatic Target Recognition Best Student Paper Award. 

<center>
    <img src="/images/drone_detection.png" width="900" />
    <p style="font-size: 0.9rem;"><em>Sample of frames illustrating our proposed approach (LWIR+RGB, leftmost image) compared to LWIR and RGB alone to detect sUAS. The proposed method synchronizes and combines both LWIR and RGB images leveraging the advantages of both sensors for object detection.</em></p>
</center>

This research work proposes combining the advantages of the long-wave infrared (LWIR) and visible spectrum sensors using machine learning for vision-based detection of small unmanned air systems (sUAS). Utilizing the heightened background contrast from the LWIR sensor combined and synchronized with the relatively increased resolution of the visible spectrum sensor, a deep learning model was trained to detect the sUAS through previously difficult environments. More specifically, the approach demonstrated effective detection of multiple sUAS flying above and below the treeline, in the presence of birds and glare from the sun. With a network of these small and affordable sensors, one can accurately estimate the 3D position of the sUAS, which could then be used for elimination or further localization from more narrow sensors, like a fire-control radar (FCR).

<center>
    <img src="/images/research/drone_detect_sensors.png" width="350" />
    <p style="font-size: 0.9rem;"><em>Picture of the mounted RGB and LWIR cameras used to capture data for this research work.</em></p>
</center>


### Combining Visible and Infrared Spectrum Imagery using Machine Learning for Small Unmanned Aerial System Detection
- [Project page](https://sites.google.com/view/tamudrone-spie2020/)
- [Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11394/2557442/Combining-visible-and-infrared-spectrum-imagery-using-machine-learning-for/10.1117/12.2557442.short)
- [Paper (preprint)](https://arxiv.org/abs/2003.12638)
- [News article](https://engineering.tamu.edu/news/2018/11/a-team-wins-md5-a-hack-of-the-drones-2018.html)
- Citation:
```
@inproceedings{goecks2020combining,
  title={Combining visible and infrared spectrum imagery using machine learning for small unmanned aerial system detection},
  author={Goecks, Vinicius G and Woods, Grayson and Valasek, John},
  booktitle={Automatic Target Recognition XXX},
  volume={11394},
  pages={113940Z},
  year={2020},
  organization={International Society for Optics and Photonics}
}
```

<center>
    <img src="/images/research/drone_detect_awards.png" width="850" />
    <p style="font-size: 0.9rem;"><em>This research was winner of the 2020 SPIE Automatic Target Recognition Best Student Paper Award (left) and winner of the A-Hack-of-the-Drones 2018 hackathon (right), where the concept idea was born.</em></p>
</center>