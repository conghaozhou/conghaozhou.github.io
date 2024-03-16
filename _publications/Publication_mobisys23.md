---
title: "No More Companion Apps Hacking but One Dongle: Hub-Based Blackbox Fuzzing of IoT Firmware"
collection: publications
permalink: /publication/Publication_mobisys23
excerpt: 'This work has discovered over twenty zero-day vulnerabilities and 6 CVEs have been assigned to them: CVE-2023-24678, CVE-2022-47100, CVE-2023-29780, CVE-2023-29779, CVE-2023-34596, CVE-2023-34597'
date: 2023-02-27
venue: 'In Proceedings of the 21st ACM International Conference on Mobile Systems, Applications, and Services (MobiSys)'
paperurl: 'https://agatah2333.github.io/assets/IoT-Fuzzing.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**Abstract**  
Given the massive difficulty in emulating IoT firmware, blackbox fuzzing of IoT devices for vulnerability discovery has become an attractive option. However, existing blackbox IoT fuzzers need muchtime and tedious effort to reverse engineer the IoT companion app (or manually collect test scripts) of each IoT device, which
is unscalable when analyzing many devices. Moreover, fuzzing through a companion app is impeded by the input sanitization inside the app and limited to the manually revealed functions. We notice that IoT devices are typically able to connect a hub using standard wireless protocols (such as ZigBee, Z-Wave, and WiFi). We thus propose a uniform hub-based architecture for fuzzing various IoT devices, without reverse engineering any companion apps. It exploits the messages exchanged between a hub and an IoT device to automatically discover all the functions, and then launches systematic function-oriented message-semantics-guided fuzzing. It avoids sanitization imposed by a companion app. In addition, it conducts device state-sensitive fuzzing, which we find very effective in finding IoT bugs. We implement the system named HubFuzzer. The evaluation shows that HubFuzzer leads to much higher coverage than prior state of the art. We test 21 IoT devices and find 23 zero-day vulnerabilities. Six CVEs have been assigned.

**[Teaser Video](https://www.youtube.com/watch?v=p9ALpVsMt28&list=PL6jLuiS6wP5bTR9rjQRDFxAVrRP0It6mn&t=1s)**

**[BibTex]**
```
@inproceedings{ma2023hubbased,
  author = {Ma, Xiaoyue and Zeng, Qiang and Chi, Haotian and Luo, Lannan},
  title = {No More Companion Apps Hacking but One Dongle: Hub-Based Blackbox Fuzzing of IoT Firmware},
  booktitle = {Proceedings of the 21st Annual International Conference on Mobile Systems, Applications and Services (MobiSys)},
  year = {2023}
}
```


