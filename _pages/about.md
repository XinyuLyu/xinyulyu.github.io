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

<!-- Hi, my name is Xinyu Lyu (吕新昱). I’m a Ph.D. student from College of Computer Science, University of Electronic Science and Technology of China, advised by Prof.[Lianli Gao](https://lianligao.github.io/), Prof.[Jie Shao](https://cfm.uestc.edu.cn/~shaojie/) and Prof.[Jingkuan Song](https://jingkuansong.github.io/). Before that, I obtained my MS and BS degrees in Rutgers University under the supervision of Prof.[Ivan Marsic](https://www.ece.rutgers.edu/~marsic/) in 2019, and UESTC in 2018, respectively.   -->
Hi, my name is Xinyu Lyu (吕新昱). I’m an Associate Professor in School of Computing and Artificial Intelligence, Southwestern University of Finance and Economics. Before that, I obtained my Ph.D. degree from College of Computer Science, University of Electronic Science and Technology of China, advised by Prof.[Lianli Gao](https://lianligao.github.io/), Prof.[Jingkuan Song](https://cfm.uestc.edu.cn/~songjingkuan/) and Prof.[Jie Shao](https://cfm.uestc.edu.cn/~shaojie/). 

My research interests mainly focus are Multimedia Learning and AI Safety, icluding Hallucination Mitigation, Risk Detection and Jailbreak Defense of MLLMs.


# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, c tempus justo dapibus sit amet.  -->
- *2025.09*: &nbsp; Two papers were accepted by Conference on Neural Information Processing Systems (NeurIPS 2025).
- *2025.06*: &nbsp; I was recognized as an outstanding reviewer (Top 5%) for CVPR 2025.
- *2025.05*: &nbsp; One paper was accepted by IEEE Transactions on Image Processing (TIP 2025).
- *2025.02*: &nbsp; One paper was accepted by IEEE Transactions on Image Processing (TIP 2025).
- *2025.01*: &nbsp; One paper was accepted by International Journal of Computer Vision (IJCV 2025).
<!-- *2024.09*: &nbsp; One paper was accepted by Conference on Neural Information Processing Systems (NeurIPS 2024).  -->
  
<!--- *2023.11*: &nbsp; One paper was accepted by IEEE Transactions on Circuits and Systems for Video Technology (TCSVT 2023). -->
<!--- *2023.07*: &nbsp; One paper was accepted by IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI 2023). -->
<!--- *2023.07*: &nbsp; One paper was accepted by IEEE Transactions on Circuits and Systems for Video Technology (TCSVT 2023). -->
<!--- *2023.02*: &nbsp; One paper was accepted by IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2023). -->
<!--- *2022.10*: &nbsp; One paper was accepted by ACM International Conference on Multimedia (ACM MM 2022). -->
<!--- *2022.07*: &nbsp; Two papers were accepted by IEEE International Conference on Multimedia and Expo (ICME 2022). -->
<!--- *2022.06*: &nbsp; One paper was accepted by IEEE/CVF Conference on Computer Vision and Pattern Recognitionn (CVPR 2022). -->
<!--- *2021.10*: &nbsp; One paper was accepted by ACM International Conference on Multimedia (ACM MM 2021). -->
<!--- *2021.06*: &nbsp; One paper was accepted by Pattern Recognition (PR 2021). -->
<!--- *2019.10*: &nbsp; One paper was accepted by ACM International Conference on Multimedia (ACM MM 2019). -->


# 📝 Selected Publications 

(*: Equal Contribution, †: Corresponding Author, ✧: Project Leader)
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023 & CVPR 2022</div><img src='images/papers/tpami.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Adaptive Fine-Grained Predicates Learning for Scene Graph Generation.**](https://arxiv.org/pdf/2207.04602.pdf) 
**Xinyu Lyu**, Lianli Gao, Pengpeng Zeng, Heng Tao Shen, Jingkuan Song <a href="https://github.com/XinyuLyu/FGPL"><strong>Code</strong></a>
<strong><span class='show_paper_citations' data='kVcO9R4AAAAJ:UeHWp8X0CEIC'></span></strong>

**Ensuring balanced and efficient learning process for fine-grained SGG.**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='images/papers/ijcv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Informative Scene Graph Generation via Debiasing.**](https://arxiv.org/pdf/2308.05286.pdf) \\
Lianli Gao, **Xinyu Lyu†**, Yuyu Guo, Yuxuan Hu, Yuan-Fang Li, Lu Xu, Heng Tao Shen, Jingkuan Song <a href="https://github.com/ZhuGeKongKong/SGG-G2S"><strong>Code</strong></a>
<strong><span class='show_paper_citations' data='MLqt214AAAAJ:IjCSPb-OGe4C'></span></strong> 

**Making balanced and informative predicate prediction for unbiased SGG.**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2025</div><img src='images/papers/tip.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Multi-Concept Learning for Scene Graph Generation.**](https://ieeexplore.ieee.org/document/10909340) \\
**Xinyu Lyu**, Lianli Gao, Junlin Xie, Pengpeng Zeng, Yulu Tian, Jie Shao, Heng Tao Shen <a href="https://github.com/XinyuLyu/G-USGG"><strong>Code</strong></a>
<strong><span class='show_paper_citations' data='MLqt214AAAAJ:IjCSPb-OGe4C'></span></strong>

**Addressing both predicate-level and concept-level imbalance issues for generalized unbiased SGG.**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/papers/Nips2024-halluciation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[**Alleviating Hallucinations in Large Vision-Language Models through Hallucination-Induced Optimization.**](https://arxiv.org/pdf/2405.15356) \\
**Xinyu Lyu**, Beitao Chen, Lianli Gao, Jingkuan Song and Heng Tao Shen <a href="https://github.com/BT-C/HIO"><strong>Code</strong></a>
<strong><span class='show_paper_citations' data='kVcO9R4AAAAJ:UeHWp8X0CEIC'></span></strong>

**Alleviating Hallucinations in LVLMs via Weak-to-Strong Generalization.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/papers/flexac.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[**FlexAC : Towards Flexible Control of Associative Reasoning in Multimodal Large Language Models.**](https://openreview.net/pdf?id=RbGUML7YK6) \\
Shengming Yuan, **Xinyu Lyu\***, Shuailong Wang, Jingkuan Song, Beitao Chen and Lianli Gao <a href="https://github.com/ylhz/FlexAC"><strong>Code</strong></a>
<strong><span class='show_paper_citations' data='kVcO9R4AAAAJ:UeHWp8X0CEIC'></span></strong>

**Enabling Controllable Associative Reasoning in MLLMs.**

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/papers/safeptr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[**SafePTR: Token-Level Jailbreak Defense in Multimodal LLMs via Prune-then-Restore Mechanism.**](https://openreview.net/pdf?id=MNSiBGNAvx) \\
Beitao Chen, **Xinyu Lyu✧**, Shengming Yuan, Jingkuan Song, Heng Tao Shen and Lianli Gao <a href="https://github.com/BT-C/SafePTR"><strong>Code</strong></a>
<strong><span class='show_paper_citations' data='kVcO9R4AAAAJ:UeHWp8X0CEIC'></span></strong>

**Defending Multi-modal Jailbreak via Token-level Prune-Restore.**

</div>
</div>

<!---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/papers/cvpr23.png' alt="sym" width="100%" height="125%"></div></div>
<div class='paper-box-text' markdown="1">

[Prototype-based Embedding Network for Scene Graph Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Zheng_Prototype-Based_Embedding_Network_for_Scene_Graph_Generation_CVPR_2023_paper.pdf) \\
Chaofan Zheng*, **Xinyu Lyu\***(Equal Contribution), Lianli Gao, Bo Dai, Jingkuan Song
<a href="https://youtu.be/pMBYBYlmkNQ"><strong>Video</strong></a>
\|
<a href="https://github.com/VL-Group/PENET"><strong>Code</strong></a>

[![](https://img.shields.io/github/stars/VL-Group/PENET?style=social&label=Stars)](https://github.com/VL-Group/PENET)
<strong><span class='show_paper_citations' data='kVcO9R4AAAAJ:W7OEmFMy1HYC'></span></strong>

**Acquiring robust features for reliable relation prediction in SGG.**

</div>
</div> 
-->
- `NeurIPS 2025` [SafePTR: Token-Level Jailbreak Defense in Multimodal LLMs via Prune-then-Restore Mechanism](https://arxiv.org/pdf/2507.01513), Beitao Chen, **Xinyu Lyu✧**, Lianli Gao, Jingkuan Song, Heng Tao Shen.
- `Arxiv 2025` [Attention Hijackers: Detect and Disentangle Attention Hijacking in LVLMs for Hallucination Mitigation](https://arxiv.org/pdf/2503.08216), Beitao Chen, **Xinyu Lyu✧**, Lianli Gao, Jingkuan Song, Heng Tao Shen.
- `TIP 2025` [Text-Video Retrieval with Global-Local Semantic Consistent Learning](https://arxiv.org/pdf/3312.17425.pdf), Haonan Zhang, Pengpeng Zeng, Lianli Gao, Jingkuan Song, Yihang Duan, **Xinyu Lyu**, Haonan Zhang, Heng Tao Shen.
- `Arxiv 2024` [ALF: Adaptive Label Finetuning for Scene Graph Generation](https://arxiv.org/abs/2312.17425.pdf), Qishen Chen, Jianzhi Liu, **Xinyu Lyu✧**, Lianli Gao, Jingkuan Song.
- `ISAIR 2023` [Local-global Information Interaction Debiasing for Dynamic Scene Graph Generation](https://arxiv.org/abs/2308.05274), **Xinyu Lyu†**, Jingwei Liu, Yuyu Guo.
- `CVPR 2023` [Prototype-based Embedding Network for Scene Graph Generation](https://openaccess.thecvf.com/content/CVPR2023/papers/Zheng_Prototype-Based_Embedding_Network_for_Scene_Graph_Generation_CVPR_2023_paper.pdf), Chaofan Zheng, **Xinyu Lyu\***, Lianli Gao, Bo Dai, Jingkuan Song.
- `TCSVT 2023` [SPT: Spatial Pyramid Transformer for Image Captioning](https://xinyulyu.github.io/), Haonan Zhang, Pengpeng Zeng, Lianli Gao, **Xinyu Lyu**, Jingkuan Song, Heng Tao Shen.
- `TCVST 2023` [Dual-branch hybrid learning network for unbiased scene graph generation](https://arxiv.org/pdf/2207.07913.pdf), Chaofan Zheng, Lianli Gao, **Xinyu Lyu**, Pengpeng Zeng, Abdulmotaleb El Saddik, Heng Tao Shen.
- `ICME 2022` [Learning to Generate Scene Graph from Head to Tail](https://arxiv.org/pdf/2206.11653.pdf),  Chaofan Zheng, **Xinyu Lyu**, Yuyu Guo, Jingkuan Song, Lianli Gao.
- `ICME 2022` [Multi-Scale Graph Attention Network for Scene Graph Generation](https://ieeexplore.ieee.org/document/9859970), Min Chen, **Xinyu Lyu**, Yuyu Guo, Jingkuan Song, Lianli Gao.
- `ACM MM 2022`  [Dynamic Scene Graph Generation via Temporal Prior Inference](https://dl.acm.org/doi/abs/10.1145/3503161.3548324), Shuang Wang, Lianli Gao, **Xinyu Lyu**, Yuyu Guo, Jingkuan Song.
- `ACM MM 2021`  (**oral**) [Conceptual and Syntactical Cross-modal Alignment with Cross-level Consistency for Image-Text Matching](https://dl.acm.org/doi/10.1145/3474085.3475380), Pengpeng Zeng, Lianli Gao, **Xinyu Lyu**, Shuaiqi Jing, Jingkuan Song.
- `PR 2021`  [GuessWhich? Visual dialog with attentive memory network](https://www.sciencedirect.com/science/article/pii/S0031320321000108), Lei Zhao, **Xinyu Lyu✧**, Jingkuan Song, Lianli Gao.
- `ACM MM 2019`  (**oral**) [Mutual correlation attentive factors in dyadic fusion networks for speech emotion recognition](https://dl.acm.org/doi/10.1145/3343031.3351039), Yue Gu, **Xinyu Lyu**, Weijia Sun, Weitian Li, Shuhong Chen, Xinyu Li, Ivan Marsic.
<!-- under review -->

# 🎖 Honors and Awards
- *2025.06* Outstanding Reviewers for CVPR 2025.([Webpage](https://cvpr.thecvf.com/Conferences/2025/ProgramCommittee#all-outstanding-reviewer))
- *2024.05* Academic Newcomer Honor of UESTC. ([Webpage](https://www.scse.uestc.edu.cn/info/1017/15497.htm))
- *2024.01* SCF Annual Outstanding Student Paper. ([Webpage](https://mp.weixin.qq.com/s/n1jSNB4aOd8YiYppOaf2hw))

# 📚 Course Teaching
- *Graduate MS*: Multimodal Large Models (Semester 1, 2025–2026)
- *Graduate MS*: Principles and Practice of Multimodal Large Models (Semester 1, 2025–2026)
- *Graduate PhD*: Frontiers in Multimodal Large Models (Semester 2, 2025–2026)
- *Undergraduate*: Artificial Intelligence and Modern Technology (Semesters 1–2, 2024–2026)


# 🙋 Service
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China.  -->

<!-- - Journal Reviewer of IEEE Transactions on Knowledge and Data Engineering, IEEE Transactions on Neural Networks and Learning Systems, IEEE Transactions on Systems, Man and Cybernetics: Systems. -->
- **Journal Reviewer**: IEEE TPAMI, IJCV, IEEE TIP, IEEE TCSVT, IEEE TMM, IEEE TGRS, ACM TOMM, etc.
- **Conference Reviewer**: CVPR, ICCV, ECCV, NeurIPS, ICLR, ACM MM, AAAI, EMNLP, ICME, etc.
<!-- - Conference Reviewer: of CVPR 2023/2024, NeurIPS 2022/2023, ACM MM 2021/2023, ICCV 2023, AAAI 2020/2024, EMNLP 2024, ICPR2020. -->
<!-- , CICAI 2021-2022, ICIG 2021, ACML 2021, PRCV 2021-2022 -->
- **Competition Reviewer**: Guangdong-Hong Kong-Macao Greater Bay Area (Whampoa) International Algorithm Calculation Competition 2022/2023.
<!--  ([Track: Panoptic Scene Graph Genetation](https://www.cvmart.net/race/10349/base?organic_url=https%3A%2F%2Fwww.google.com%2F))/ 2023([Track: FunQA](http://112.74.40.78:9092/contestdetail?id=64af50154a0ed647faca623a&award=1,000,000)) .-->

# 💻 Main Projects
- *2025.07 - 2027.07*, Teaching Practice Research on an Inclusive Finance Risk-Control Dialogue System Driven by Multimodal Large-Scale Models, Sichuan Provincial Department of Education Innovative Experimental Project of Undergraduate, **Project Leader**.
- *2025.01 - 2026.12*, Research on Visual Relationship Detection Algorithms and Applications in Open World Settings, Sichuan Provincial Natural Science Foundation Project (No. 2025ZNSFSC1463), **Project Leader**.
- *2023.02 - 2024.06*, 2030 Science and Technology Innovation Major Project for Next-Generation Artificial Intelligence by the Ministry of Science and Technology, National Key Research and Development Program of China (No. 2018AAA0102200), **Main Researcher**.
- *2021.01 - 2025.12*, Research on Key Technologies for Visual Natural Cognition through Collaborative Vision and Language Processing, National Natural Science Foundation of China under Grant (No. 62020106008), **Participant**.
- *2020.01 - 2022.07*, Research on Scene Graph Generation for E-commerce Live Streaming/Video, Kuaishou (No. 202109FKY00302), **Main Researcher**.
<!--- *2019.01 - 2022.12*, Research on Key Technology Research on Collaborative Deep Video Understanding, Description, and Visual Question Answering, National  Natural  Science Foundation of China (No. 61872064), **Participant**. -->
<!-- *2018.01 - 2021.12*, Research on Key Technology for Deep Visual Understanding Integrated with Natural Language Processing, National  Natural  Science  Foundation  of  China (No. 61772116), **Participant**. -->

  <a href="https://www.easycounter.com/">
  <img src="https://www.easycounter.com/counter.php?xinyulyu"
  border="0" alt="Free Web Counter"></a> visitors since Jun 2024.
