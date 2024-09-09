---
title: "From One Thousand Pages of Specification to Unveiling Hidden Bugs: Large Language Model Assisted Fuzzing of Matter IoT Devices"
collection: publications
permalink: /publication/Publication_usenix24
excerpt: 'Our tool that discovered over 60 zero-day vulnerabilities!'
date: 2024-05-29
venue: 'Security’24, Philadelphia, USA, Aug. 2024'
# paperurl: 'https://agatah2333.github.io/assets/IoT-Fuzzing.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**Abstract**  
Matter is an IoT connectivity standard backed by over two hundred companies. Since the release of its specification in October 2022, numerous IoT devices have become Matter-compatible. Identifying bugs and vulnerabilities in Matter devices is thus an emerging important problem. This paper introduces mGPTFuzz, the first Matter fuzzer in the literature. Our approach harnesses the extensive and detailed information within the Matter specification to guide the generation of test inputs. However, due to the sheer volume of the Matter specification, surpassing one thousand pages, manually converting human-readable content to machine-readable information is tedious, time-consuming and error-prone. To overcome this challenge, we leverage a large language model to successfully automate the conversion process. mGPTFuzz conducts stateful analysis, which generates message sequences to uncover bugs that would be challenging to discover otherwise. The evaluation involves 23 various Matter devices and discovers 147 new bugs, with three CVEs assigned. In comparison, a state-of-the-art IoT fuzzer finds zero bugs from these devices.

<!-- **[Teaser Video](https://www.youtube.com/watch?v=p9ALpVsMt28&list=PL6jLuiS6wP5bTR9rjQRDFxAVrRP0It6mn&t=1s)** -->

**[BibTex]**
```
@inproceedings{ma2024one,
  title={From One Thousand Pages of Specification to Unveiling Hidden Bugs: Large Language Model Assisted Fuzzing of Matter IoT Devices},
  author={Ma, Xiaoyue and Luo, Lannan and Zeng, Qiang},
booktitle={USENIX Security Symposium (USENIX Security)},
  year={2024}
}
```


