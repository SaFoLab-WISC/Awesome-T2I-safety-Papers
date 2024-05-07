# Awesome-T2I-safety-Papers
[![Update Log](https://img.shields.io/badge/💡-Update_Log-informational.svg?style=flat)](README.md)
[![Report Error](https://img.shields.io/badge/🐛-Report_Error-yellow.svg?style=flat)](https://github.com/Awesome-T2l-Safety/T2I-safety-Papers/issues)
[![Pull Request](https://img.shields.io/badge/👐-Pull_Request-brightgreen.svg?style=flat)](https://github.com/Awesome-T2l-Safety/T2I-safety-Papers/pulls)

A **continual** collection of papers related to safety of Text-to-Image/Text-to-Video Models (T2I/T2V Safety).


## 🚀 The scope of our collection

💡 **Topic 1:** The Jailbreak Attack/Defense methods on T2I/T2V Models.
   > Here, safety is defined as stopping models from following malicious instructions and generating toxic content, including violence, NSFW, privacy violation, animal abuse, child abuse, sexual, misinformation, etc.
   (please refer to [[the system card of DALL·E3](https://cdn.openai.com/papers/DALL_E_3_System_Card.pdf)])

💡 **Topic 2:** Digital Watermarking for T2I Safety. 
  > Digital Watermarking is broadly used for the verification, authenticity, and traceability of images. It can also trace the copyright and ownership of the T2I models.



💡 **Topic 3:** Attribution for T2I Methods. 
  > To determine whether an image is generated by AIGC methods, and by which model (e.g. Stable Diffusion, DALL-E, etc.), we can attribute an image to its generator, in proactive and passive ways.
  
---
## 💡 Jailbreak Attack on Text-to-Image Models

#### [0] SneakyPrompt: Jailbreaking Text-to-image Generative Models 
- **🧑‍🔬 Author**: Yuchen Yang, Bo Hui, Haolin Yuan, Neil Gong, Yinzhi Cao
- **🏫 Affiliation**: Johns Hopkins University, Duke University
- **🔗 Link**: [[Code](https://github.com/Yuchen413/text2image_safety)] [[arXiv:2305.12082](https://arxiv.org/abs/2305.12082)]
- **📝 Note**: 🔥 (S&P 2024)

#### [1] MMA-Diffusion: MultiModal Attack on Diffusion Models
- **🧑‍🔬 Author**: Yijun Yang, Ruiyuan Gao, Xiaosen Wang, Tsung-Yi Ho, Nan Xu, Qiang Xu
- **🏫 Affiliation**: The Chinese University of Hong Kong, Huawei Singular Security Lab, Institute of Automation, Chinese Academy of Sciences, Beijing Wenge Technology Co. Ltd
- **🔗 Link**: [[Code](https://github.com/cure-lab/MMA-Diffusion)] [[arXiv:2311.17516](https://arxiv.org/abs/2311.17516)]
- **📝 Note**: 🔥 (CVPR2024)

#### [2] RIATIG: Reliable and Imperceptible Adversarial Text-to-Image Generation With Natural Prompts
- **🧑‍🔬 Author**: Han Liu, Yuhao Wu, Shixuan Zhai, Bo Yuan, Ning Zhang
- **🏫 Affiliation**: Washington University in St. Louis, Rutgers University
- **🔗 Link**: [[Code](https://github.com/WUSTL-CSPL/RIATIG)] [[CVPR:2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_RIATIG_Reliable_and_Imperceptible_Adversarial_Text-to-Image_Generation_With_Natural_Prompts_CVPR_2023_paper.pdf)]
- **📝 Note**: 🔥 (CVPR2023)

#### [3] Prompt Stealing Attacks Against Text-to-Image Generation Model
- **🧑‍🔬 Author**: Xinyue Shen, Yiting Qu, Michael Backes, Yang Zhang
- **🏫 Affiliation**: CISPA Helmholtz Center for Information Security
- **🔗 Link**: [[Code]] [[arXiv:2302.09923](https://arxiv.org/abs/2302.09923)]
- **📝 Note**: 🔥 (CVPR2024)

#### [4] Divide-and-Conquer Attack: Harnessing the Power of LLM to Bypass the Censorship of Text-to-Image Generation Model
- **🧑‍🔬 Author**: Yimo Deng, Huangxun Chen
- **🏫 Affiliation**: The Hong Kong University of Science and Technology, Northeastern University
- **🔗 Link**:  [[Code](https://github.com/researchcode001/Divide-and-Conquer-Attack)] [[arXiv:2302.09923](https://arxiv.org/abs/2312.07130)]
- **📝 Note**:

#### [5] SurrogatePrompt: Bypassing the Safety Filter of Text-To-Image Models via Substitution
- **🧑‍🔬 Author**: Zhongjie Ba, Jieming Zhong, Jiachen Lei, Peng Cheng, Qinglong Wang, Zhan Qin, Zhibo Wang, Kui Ren
- **🏫 Affiliation**: Zhejiang University, ZJU-Hangzhou Global Scientific and Technological Innovation Center, 
- **🔗 Link**: [[Code]] [[arXiv:2309.14122](https://arxiv.org/abs/2309.14122)]
- **📝 Note**:

#### [6] Unsafe Diffusion: On the Generation of Unsafe Images and Hateful Memes From Text-To-Image Models
- **🧑‍🔬 Author**: Yiting Qu, Xinyue Shen, Xinlei He, Michael Backes, Savvas Zannettou, Yang Zhang
- **🏫 Affiliation**: CISPA Helmholtz Center for Information Security, Delft University of Technology 
- **🔗 Link**: [[Code](https://github.com/YitingQu/unsafe-diffusion)] [[arXiv:2305.13873](https://arxiv.org/abs/2305.13873)]
- **📝 Note**: 🔥 (ACM CCS 2023)

#### [7] Probing Unlearned Diffusion Models: A Transferable Adversarial Attack Perspective
- **🧑‍🔬 Author**: Xiaoxuan Han and Songlin Yang and Wei Wang and Yang Li and Jing Dong
- **🏫 Affiliation**: University of Chinese Academy of Sciences
- **🔗 Link**: [[Code](https://github.com/hxxdtd/PUND)] [[arXiv:2404.19382](https://arxiv.org/abs/2404.19382)]
- **📝 Note**: 30 Apr 2024 Arxiv

#### [8] UnsafeBench: Benchmarking Image Safety Classifiers on Real-World and AI-Generated Images
- **🧑‍🔬 Author**: Yiting Qu, Xinyue Shen, Yixin Wu, Michael Backes, Savvas Zannettou, Yang Zhang
- **🏫 Affiliation**: CISPA Helmholtz Center for Information Security, TU Delf
- **🔗 Link**: [[Code](https://github.com/YitingQu/UnsafeBench)] [[arXiv:2405.03486](https://arxiv.org/abs/2405.03486)]
- **📝 Note**: 30 Apr 2024 Arxiv
  

---
## 💡 Defenses on Text-to-Image Models

#### [0] GuardT2I: Defending Text-to-Image Models from Adversarial Prompts
- **🧑‍🔬 Author**: Yijun Yang, Ruiyuan Gao, Xiao Yang, Jianyuan Zhong, Qiang Xu
- **🏫 Affiliation**: The Chinese University of Hong Kong, Hong Kong,  Tsinghua University
- **🔗 Link**: [Code] [[arXiv:2403.01446](https://arxiv.org/abs/2403.01446)]
- **📝 Note**:

#### [1] Universal Prompt Optimizer for Safe Text-to-Image Generation
- **🧑‍🔬 Author**: Zongyu Wu, Hongcheng Gao, Yueze Wang, Xiang Zhang, Suhang Wang
- **🏫 Affiliation**: The Pennsylvania State University, University of Chinese Academy of Sciences, Tianjin University
- **🔗 Link**: [Code] [[arXiv:2402.10882](https://arxiv.org/abs/2402.10882)]
- **📝 Note**: 

#### [2] SAFEGEN: Mitigating Unsafe Content Generation in Text-to-Image Models
- **🧑‍🔬 Author**: Xinfeng Li, Yuchen Yang, Jiangyi Deng, Chen Yan, Yanjiao Chen, Xiaoyu Ji, Wenyuan Xu
- **🏫 Affiliation**: USSLAB, Zhejiang University, Johns Hopkins University
- **🔗 Link**: [Code] [[arXiv:2404.06666](https://arxiv.org/abs/2404.06666)]
- **📝 Note**:

#### [3] Adversarial Example Does Good: Preventing Painting Imitation from Diffusion Models via Adversarial Examples
- **🧑‍🔬 Author**: Chumeng Liang, Xiaoyu Wu, Yang Hua, Jiaru Zhang, Yiming Xue, Tao Song, Zhengui Xue, Ruhui Ma, Haibing Guan
- **🏫 Affiliation**: USSLAB, Zhejiang University, Johns Hopkins University
- **🔗 Link**: [[Code](https://github.com/psyker-team/mist)] [[arXiv:2302.04578](https://arxiv.org/abs/2302.04578)]
- **📝 Note**: ICML 2023 (Oral)

#### [4] Anti-DreamBooth: Protecting Users from Personalized Text-to-Image Synthesis
- **🧑‍🔬 Author**: Thanh Van Le, Hao Phung, Thuan Hoang Nguyen, Quan Dao, Ngoc Tran, Anh Tran
- **🏫 Affiliation**: VinAI Research, Vanderbilt University
- **🔗 Link**: [[Code](https://github.com/VinAIResearch/Anti-DreamBooth)] [[arXiv:2303.15433](https://arxiv.org/abs/2303.15433)]
- **📝 Note**: ICCV 2023

#### [5] Latent Guard: a Safety Framework for Text-to-image Generation
- **🧑‍🔬 Author**: Runtao Liu, Ashkan Khakzar, Jindong Gu, Qifeng Chen, Philip Torr, and Fabio Pizzati
- **🏫 Affiliation**: Hong Kong University of Science and Technology, University of Oxford,
- **🔗 Link**: [Code] [[arXiv:2404.08031](https://arxiv.org/abs/2404.08031)]
- **📝 Note**: 

---
## 💡 Digital Watermarking for T2I Safety

#### [0] The Stable Signature: Rooting Watermarks in Latent Diffusion Models
- **🧑‍🔬 Author**:  Pierre Fernandez, Guillaume Couairon, Herv´e J´egou, Matthijs Douze, Teddy Furon
- **🏫 Affiliation**: Meta AI, Centre Inria de l’Universit´ e de Rennes, Sorbonne University
- **🔗 Link**: [[Code](https://github.com/facebookresearch/stable_signature)] [[arXiv:2303.15435](https://arxiv.org/abs/2303.15435)]
- **📝 Note**: ICCV 2023

#### [1] Tree-Rings Watermarks: Invisible Fingerprints for Diffusion Images
- **🧑‍🔬 Author**: Yuxin Wen, John Kirchenbauer, Jonas Geiping, Tom Goldstein
- **🏫 Affiliation**: University of Maryland
- **🔗 Link**: [[Code](https://github.com/YuxinWenRick/tree-ring-watermark)] [[NeurIPS 2023](https://proceedings.neurips.cc/paper_files/paper/2023/file/b54d1757c190ba20dbc4f9e4a2f54149-Paper-Conference.pdf)]
- **📝 Note**: NeurIPS 2023
  
#### [2] Gaussian Shading: Provable Performance-Lossless Image Watermarking for Diffusion Models
- **🧑‍🔬 Author**: Zijin Yang, Kai Zeng, Kejiang Chen, Han Fang, Weiming Zhang, Nenghai Yu
- **🏫 Affiliation**: University of Science and Technology of China, National University of Singapore
- **🔗 Link**: [Code] [[arXiv:2404.04956](https://arxiv.org/abs/2404.04956)]
- **📝 Note**: CVPR 2024

#### [3] EditGuard: Versatile Image Watermarking for Tamper Localization and Copyright Protection
- **🧑‍🔬 Author**: Xuanyu Zhang, Runyi Li, Jiwen Yu, Youmin Xu, Weiqi Li, Jian Zhang
- **🏫 Affiliation**: Peking University
- **🔗 Link**: [[Code](https://github.com/xuanyuzhang21/EditGuard)] [[arXiv:2312.08883](https://arxiv.org/abs/2312.08883)]
- **📝 Note**: CVPR 2024

#### [4] Purified and Unified Steganographic Network
- **🧑‍🔬 Author**: Guobiao Li, Sheng Li, Zicong Luo, Zhenxing Qian, Xinpeng Zhang
- **🏫 Affiliation**: Peking University
- **🔗 Link**: [[Code](https://github.com/albblgb/PUSNet)] [[arXiv:2402.17210](https://arxiv.org/abs/2402.17210)]
- **📝 Note**: CVPR 2024

#### [5] ProMark: Proactive Diffusion Watermarking for Causal Attribution
- **🧑‍🔬 Author**: Vishal Asnani, John Collomosse, Tu Bui, Xiaoming Liu, Shruti Agarwal
- **🏫 Affiliation**: Adobe Research, Michigan State University, University of Surrey
- **🔗 Link**: [Code] [[arXiv:2403.09914](https://arxiv.org/abs/2403.09914)]
- **📝 Note**: CVPR 2024

#### [6] Performance-lossless Black-box Model Watermarking
- **🧑‍🔬 Author**: Na Zhao, Kejiang Chen, Weiming Zhang, and Nenghai Yu
- **🏫 Affiliation**: University of Science and Technology of China
- **🔗 Link**: [Code] [[arXiv:2312.06488](https://arxiv.org/abs/2312.06488)]
- **📝 Note**: IEEE TDSC 2023

#### [7] Detecting Voice Cloning Attacks via Timbre Watermarking
- **🧑‍🔬 Author**: Chang Liu, Jie Zhang, Tianwei Zhang, Xi Yang, Weiming Zhang, Nenghai Yu
- **🏫 Affiliation**: University of Science and Technology of China, Nanyang Technological University
- **🔗 Link**: [[Code](https://timbrewatermarking.github.io/samples)] [[arXiv:2312.03410](https://arxiv.org/abs/2312.03410)]
- **📝 Note**: NDSS 2024

#### [8] WavMark: Watermarking for Audio Generation
- **🧑‍🔬 Author**: Guangyu Chen, Yu Wu, Shujie Liu, Tao Liu, Xiaoyong Du, Furu Wei
- **🏫 Affiliation**: Microsoft Research Asia, Renmin University of China
- **🔗 Link**: [[Code](https://github.com/wavmark/wavmark)] [[arXiv:2308.12770](https://arxiv.org/abs/2308.12770)]
- **📝 Note**:

#### [9] Steal My Artworks for Fine-tuning? A Watermarking Framework for Detecting Art Theft Mimicry in Text-to-Image Models
- **🧑‍🔬 Author**: Ge Luo, Junqiang Huang, Manman Zhang, Zhenxing Qian, Sheng Li, Xinpeng Zhang
- **🏫 Affiliation**: Fudan University
- **🔗 Link**: [Code] [[arXiv:2311.13619](https://arxiv.org/abs/2311.13619)]
- **📝 Note**:

#### [10] Robust-Wide: Robust Watermarking against Instruction-driven Image Editing
- **🧑‍🔬 Author**: Runyi Hu, Jie Zhang, Ting Xu, Tianwei Zhang, Jiwei Li
- **🏫 Affiliation**: Zhejiang University, Nanyang Technological University, University of Science and Technology of China
- **🔗 Link**: [Code] [[arXiv:2402.12688](https://arxiv.org/abs/2402.12688)]
- **📝 Note**:

#### [11] Robust Image Watermarking using Stable Diffusion
- **🧑‍🔬 Author**: Lijun Zhang, Xiao Liu, Antoni Viros Martin, Cindy Xiong Bearfield, Yuriy Brun, Hui Guan
- **🏫 Affiliation**: University of Massachusetts, IBM
- **🔗 Link**: [[Code](https://github.com/zhanglijun95/ZoDiac)] [[arXiv:2401.04247](https://arxiv.org/abs/2401.04247)]
- **📝 Note**:

#### [12] Proactive Detection of Voice Cloning with Localized Watermarking
- **🧑‍🔬 Author**: Robin San Roman, Pierre Fernandez, Alexandre Défossez, Teddy Furon, Tuan Tran, Hady Elsahar
- **🏫 Affiliation**: FAIR, Meta
- **🔗 Link**: [[Code](https://github.com/facebookresearch/audioseal)] [[arXiv:2401.17264](https://arxiv.org/abs/2401.17264)]
- **📝 Note**:

#### [13] A Watermark-Conditioned Diffusion Model for IP Protection
- **🧑‍🔬 Author**: Rui Min, Sen Li, Hongyang Chen, Minhao Cheng
- **🏫 Affiliation**: Hong Kong University of Science and Technology, Zhejiang Lab, Pennsylvania State University
- **🔗 Link**: [Code] [[arXiv:2403.10893](https://arxiv.org/abs/2403.10893)]
- **📝 Note**:


---
## 💡 Attribution for T2I AIGC methods

#### [0] Watermark-based Detection and Attribution of AI-Generated Content
- **🧑‍🔬 Author**:  Zhengyuan Jiang, Moyang Guo, Yuepeng Hu, Neil Zhenqiang Gong
- **🏫 Affiliation**: Duke University
- **🔗 Link**: [Code] [[arXiv:2404.04254](https://arxiv.org/abs/2404.04254)]
- **📝 Note**:

#### [1] Detecting Image Attribution for Text-to-Image Diffusion Models in RGB and Beyond
- **🧑‍🔬 Author**:  Katherine Xu, Lingzhi Zhang, Jianbo Shi
- **🏫 Affiliation**: University of Pennsylvania, Adobe Inc.
- **🔗 Link**: [[Code](https://github.com/k8xu/ImageAttribution)] [[arXiv:2403.19653](https://arxiv.org/abs/2403.19653)]
- **📝 Note**:

#### [2] Regeneration Based Training-free Attribution of Fake Images Generated by Text-to-Image Generative Models
- **🧑‍🔬 Author**:  Meiling Li, Zhenxing Qian, Xinpeng Zhang
- **🏫 Affiliation**: Fudan University
- **🔗 Link**: [Code] [[arXiv:2403.01489](https://arxiv.org/abs/2403.01489)]
- **📝 Note**:

#### [3] Where Did I Come From? Origin Attribution of AI-Generated Images
- **🧑‍🔬 Author**:  Zhenting Wang, Chen Chen, Yi Zeng, Lingjuan Lyu, Shiqing Ma
- **🏫 Affiliation**: Rutgers University, Sony AI, Virginia Tech, University of Massachusetts Amherst
- **🔗 Link**: [[Code](https://github.com/ZhentingWang/RONAN)] [[NeurIPS 23](https://openreview.net/pdf?id=g8bjq0qxOl)]
- **📝 Note**: NeurIPS 2023

### 👍 Acknowledgement
Thanks to the [3D-Gaussian-Splatting-Papers](https://github.com/Awesome3DGS/3D-Gaussian-Splatting-Papers).
