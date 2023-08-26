---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a postdoctoral researcher with the [Department of Computer Science](https://www.cs.cityu.edu.hk/), City University of Hong Kong. 

I obtained my Ph.D. degree (June 2022) in Computer Science from City University of Hong Kong supervised by [Dr. Shiqi Wang (王诗淇)](https://www.cs.cityu.edu.hk/~shiqwang/). I obtained my M.S. degree in Intelligent Information Processing, Xidian University under the supervision of [Prof. Cheolkon Jung (Korea)](https://see.xidian.edu.cn/media/), in 2018, and B.S. degree in Electronic information science and technology, [Hefei University of Technology](https://www.hfut.edu.cn/), June 2015. 

My research interest includes image/video quality assessment and information forensics and security. 


# 🔥 News
- One paper accepted by ICCV2023. Fu-Zhao Ou, Baoliang Chen, Chongyi Li,  Shiqi Wang, and Sam Kwong, "Troubleshooting Ethnic Quality Bias with Curriculum Domain Adaptation for Face Image Quality Assessment". [code](https://github.com/oufuzhao/EQBM)
- One paper accepted by TMM2023. Yu Tian, Baoliang Chen, Shiqi Wang, and Sam Kwong, "Towards Thousands to One Reference: Can We Trust the Reference Image for Quality Assessment?" [code](https://github.com/ytian73/FLRE)
# 📝 Publications (*: Co-first authors)
-  **Baoliang Chen<sup>*</sup>**, Lingyu Zhu<sup>*</sup>, Hanwei Zhu, Wen Yang, Linqi Song, and Shiqi Wang, "Gap-closing Matters: Perceptual Quality Evaluation and  Optimization of Low-Light Image Enhancement", IEEE Transactions on Multimedia, 2023. [code](https://github.com/Baoliang93/IACA_For_Lowlight_IQA)
-  Hanwei Zhu, **Baoliang Chen**, Lingyu Zhu, and Shiqi Wang, “Learning spatiotemporal interactions for user-generated video quality assessment”, vol. 33, no. 3, pp. 1031–1042, 2022. [code](https://github.com/h4nwei/STI-VQA)
- **Baoliang Chen**, Lingyu Zhu, Chenqi Kong, Hanwei Zhu, Shiqi Wang, and Zhu Li, “[No-reference image quality assessment by hallucinating pristine features](https://ieeexplore.ieee.org/document/9894272),” IEEE Transactions on Image Process, vol. 31, pp. 6139-6151, 2022. [code](https://github.com/Baoliang93/FPR)
- **Baoliang Chen**, Lingyu Zhu, Guo Li, Fangbo Lu, Hongfei Fan, and Shiqi Wang, “[Learning generalized spatial-temporal deep feature representation for no-reference video quality assessment](https://ieeexplore.ieee.org/document/9452150),” IEEE Transactions on Circuits and Systems for Video Technology, vol. 32, pp. 1903-1916, 2022. [code](https://github.com/Baoliang93/GSTVQA)
- **Baoliang Chen**, Wenhan Yang, and Shiqi Wang, “Generalized face antispoofing by learning to fuse  features from high-and low-frequency domains,” IEEE MultiMedia, vol. 28, no. 1, pp. 56–64, 2021.
- **Baoliang Chen**, Wenhan Yang, Haoliang  Li, Shiqi  Wang, and Sam Kwong, “Camera invariant feature  learning for generalized face anti-spoofing,” IEEE Transactions on Information Forensics and Security, vol. 16, pp. 2477–2492, 2021.
- **Baoliang Chen**, Haoliang Li, Hongfei Fan, and Shiqi  Wang, “No-reference screen content image quality  assessment with unsupervised domain adaptation,” IEEE Transactions on Image Processing, vol. 30, pp. 5463–5476, 2021. [code]([https://github.com/Baoliang93/GSTVQA](https://mega.nz/folder/2LxFAZjQ#ZneNvMSKxCbLf0eEgPXfNw))
- **Baoliang Chen**, Cheolkon Jung, and Zhendong Zhang, “Variational fusion of time-of-flight and stereo data for depth estimation using edge-selective joint filtering,” IEEE Transactions on Multimedia, vol. 20, pp. 2882-2890, 2021.
- **Baoliang Chen**,  Wenhan Yang,  and  Shiqi Wang, “Face anti-spoofing by fusing high and low frequency  features for advanced generalization capability,” IEEE Conference  on  Multimedia  Information  Processing  and  Retrieval (MIPR 2020).
- **Baoliang Chen** and Cheolkon Jung, “Single depth image superresolution using convolutional neural networks,” IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP 2018).
- **Baoliang Chen** and Cheolkon Jung, “Patch-based stereo matching using 3D convolutional neural networks,” IEEE International Conference on Image Processing (ICIP 2018).
- **Baoliang Chen**, Cheolkon Jung, and Zhendong Zhang, “Variational fusion of time-of-ﬂight and stereo data using edge selective joint filtering,” IEEE International Conference on Image Processing (ICIP 2017).
- Xingran Liao, **Baoliang Chen**, Hanwei Zhu, Shiqi Wang, Mingliang Zhou, and Sam Kwong, “DeepWSD: Projecting degradations in perceptual space to Wasserstein distance in deep feature space,”  ACM Multimedia (ACM MM 2022). [code](https://github.com/Buka-Xing/DeepWSD)
- Shuvue Jia, **Baoliang Chen**, Dingquan Li, and Shiqi Wang, “No-reference image quality assessment via non-local dependency modeling,”  IEEE International Workshop on Multimedia Signal Processing (MMSP 2022). [code](https://github.com/SuperBruceJia/NLNet-IQA)
- Chenqi Kong, **Baoliang Chen**, Haoliang Li, Shiqi Wang, Anderson Rocha, and Sam Kwong, “Detect and locate: Exposing face manipulation by semantic- and noise-Level telltales,”  IEEE Transactions on Information Forensics and Security, vol. 17, pp. 1741-1756, 2022. [code](https://github.com/ChenqiKONG/Detect_and_Locate)
- Guo Li, **Baoliang Chen**, Lingyu Zhu, Qinwen He, Hongfei Fan, and Shiqi Wang, “PUGCQ: A large scale  dataset for quality assessment of professional user-generated content,”  ACM International Conference on Multimedia (ACM MM 2021). [code](https://github.com/wlkdb/pugcq_create)
- Chenqi Kong, **Baoliang Chen**, Shurun Wang, Haoliang Li, Peilin Chen, and Shiqi Wang, “Appearance matters, so does audio: Revealing the hidden face via cross-modality transfer,” IEEE Transactions on Circuits and Systems for Video Technology, vo. 32. no. 1, pp. 423-436, 2021.
- Pingping Zhang, Meng Wang, **Baoliang Chen**, Rongqun Lin, Xu Wang, Shiqi Wang, and Sam Kwong, “Learning-based Compression for Noisy Images in the Wild,” IEEE Transactions on Circuits and Systems for Video Technology, 2022.
- Lingyu Zhu, Wenhan Yang, **Baoliang Chen**, Fangbo Lu, and Shiqi Wang, “Enlightening low-light images with dynamic guidance for context enrichment,” IEEE Transactions on Circuits and Systems for Video Technology, 2022. [code](https://github.com/lingyzhu0101/GEMSC)
- Zhaopeng Feng, Keyang Zhang, Shuyue Jia, **Baoliang Chen**, and Shiqi Wang, “[Learning from Mixed Datasets: A Monotonic Image Quality Assessment Model](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ell2.12698),” Electronics Letters, 2022. [code](https://github.com/fzp0424/MonotonicIQA)


# 📖 Educations
- *2019.07 - 2022.06*,  Department of Computer Science, City University of Hong Kong (CityU). 
- *2015.09 - 2018.06*,  School of Electronic Engineering, University of Xidian (XDU). 
- *2011.09 - 2015.06*,  School of Computer and Information, Hefei University of Technology (HFUT).

# 🎖 Honors and Awards
- [芒果TV - VQA算法大赛](https://challenge.ai.mgtv.com/contest/detail/17) Top 10
- *2021.07*  Outstanding Academic Performance Award (CityU)
- *2021.07*  Research Tuition Scholarship (CityU)
- *2018.06*  Best Graduation Thesis (XDU)
- *2017.09*  Outstanding Graduate Student (XDU)
- *2015.06*  Outstanding Graduation Thesis (HFUT)

# 💻 Internships
- [PengCheng Lab](https://www.pcl.ac.cn/), Shenzhen, China.
