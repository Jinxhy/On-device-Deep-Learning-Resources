# On-device AI Resources
This GitHub repository summarizes a list of **On-device AI** resources with a special focus on **Security** and **Software Engineering**.

We will keep maintaining this list in a daily or weekly manner. :wink:


#### Why On-device AI?
On-device AI enables performing inference with models directly on a device (e.g. smartphone). Compared to offloading deep learning models to the cloud, On-device AI has many advantages as follows:
- Low Latency: there is no round trip to the server and no wait for results to come back.
- Privacy: the data processing happens on users' local devices.
- Works offline: network connectivity is not required.
- No cost: paying for cloud computing cycles is not needed.

## News :mega:
10/09/2024: The repository is back to update now!\
22/11/2022: The On-device AI Resources repository is first announced!!!

## On-device AI Security and Privacy
- THEMIS: Towards Practical Intellectual Property Protection for Post-Deployment On-Device Deep Learning Models.
  [[pdf]](https://arxiv.org/pdf/2503.23748)
  [[code]](https://github.com/Jinxhy/THEMIS)\
  venue: *34th USENIX Security Symposium (USENIX Security-2025)*

- SoK: All You Need to Know About On-Device ML Model Extraction - The Gap Between Research and Practice.
  [[pdf]](https://www.usenix.org/conference/usenixsecurity24/presentation/nayan)
  [[code]](https://github.com/sys-ris3/ML_Extraction_Sok)\
  venue: *33rd USENIX Security Symposium (USENIX Security-2024)*

- DynaMO: Protecting Mobile DL Models through Coupling Obfuscated DL Operators.
  [[pdf]](https://arxiv.org/pdf/2410.15033)
  [[code]](https://github.com/zhoumingyi/DynaMO)\
  venue: *39th IEEE/ACM International Conference on Automated Software Engineering (ASE-2024)*

- No Privacy Left Outside: On the (In-)Security of TEE-Shielded DNN Partition for On-Device ML.
  [[pdf]](https://arxiv.org/pdf/2310.07152)
  [[code]](https://github.com/ziqi-zhang/TEESlice-artifact)\
  venue: *2024 IEEE Symposium on Security and Privacy (S&P-2024)*

- Model-less Is the Best Model: Generating Pure Code Implementations to Replace On-Device DL Models.
  [[pdf]](https://arxiv.org/pdf/2403.16479)
  [[code]](https://github.com/zhoumingyi/CustomDLCoder)\
  venue: *The 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA-2024)*

- DEMISTIFY: Identifying On-device Machine Learning Models Stealing and Reuse Vulnerabilities in Mobile Apps.
  [[pdf]](https://bruceqczhao.github.io/assets/icse24/ICSE24b.pdf)
  [[code]](https://github.com/MGYN/DeMistify)\
  venue: *IEEE/ACM 46th International Conference on Software Engineering (ICSE-2024)*
  
- Investigating White-Box Attacks for On-Device Models.
  [[pdf]](https://arxiv.org/pdf/2402.05493)
  [[code]](https://github.com/zhoumingyi/REOM)\
  venue: *IEEE/ACM 46th International Conference on Software Engineering (ICSE-2024)*

- MirrorNet: A TEE-Friendly Framework for Secure On-Device DNN Inference.
  [[pdf]](https://arxiv.org/pdf/2311.09489)\
  venue: *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD-2023)*

- Quantization Backdoors to Deep Learning Commercial Frameworks.
  [[pdf]](https://arxiv.org/pdf/2108.09187)
  [[code]](https://github.com/quantization-backdoor/quantization-backdoor)\
  venue: *IEEE Transactions on Dependable and Secure Computing 2023 (TDSC-2023)*

- A First Look at On-device Models in iOS Apps.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3617177)
  [[code]](https://github.com/huhanGitHub/iOS-App-database)\
  venue: *ACM Transactions on Software Engineering and Methodology (TOSEM-2023)*

- ModelObfuscator: Obfuscating Model Information to Protect Deployed ML-based Systems.
  [[pdf]](https://nzjohng.github.io/publications/papers/issta2023.pdf)
  [[code]](https://github.com/zhoumingyi/ModelObfuscator)\
  venue: *The 32nd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA-2023)*
  
- ShadowNet: A Secure and Efficient On-device Model Inference System for Convolutional Neural Networks.
  [[pdf]](https://arxiv.org/pdf/2011.05905.pdf)\
  venue: *2023 IEEE Symposium on Security and Privacy (S&P-2023)*
  
- Publishing Efficient On-device Models Increases Adversarial Vulnerability.
  [[pdf]](https://openreview.net/pdf?id=nbNdDm1x3c)\
  venue: *1st IEEE Conference on Secure and Trustworthy Machine Learning 2023 (SaTML-2023)*

- Understanding Real-world Threats to Deep Learning Models in Android Apps.
  [[pdf]](https://arxiv.org/pdf/2209.09577.pdf)
  [[code]](https://github.com/Advdroid/advdroid-pro)\
  venue: *ACM SIGSAC Conference on Computer and Communications Security 2022 (CCS-2022)*
  
- Smart App Attack: Hacking Deep Learning Models in Android Apps.
  [[pdf]](https://arxiv.org/pdf/2204.11075.pdf)
  [[code]](https://github.com/Jinxhy/SmartAppAttack)\
  venue: *IEEE Transactions on Information Forensics and Security 2022 (TIFS-2022)*

- Mind Your Weight(s): A Large-scale Study on Insufficient Machine Learning Model Protection in Mobile Apps.
  [[pdf]](https://www.usenix.org/system/files/sec21-sun-zhichuang.pdf)
  [[code]](https://github.com/RiS3-Lab/ModelXRay)\
  venue: *30th USENIX Security Symposium (USENIX Security-2021)*

- DeepPayload: Black-box Backdoor Attack on Deep Learning Models through Neural Payload Injection.
  [[pdf]](https://arxiv.org/pdf/2101.06896.pdf)
  [[code]](https://github.com/yuanchun-li/DeepPayload)\
  venue: *IEEE/ACM 43rd International Conference on Software Engineering 2021 (ICSE-2021)*

- Robustness of on-device Models: Adversarial Attack to Deep Learning Models on Android Apps.
  [[pdf]](https://arxiv.org/pdf/2101.04401.pdf)
  [[code]](https://github.com/Jinxhy/AppAIsecurity)\
  venue: *IEEE/ACM 43rd International Conference on Software Engineering: Software Engineering in Practice 2021 (ICSE-SEIP-2021)*

## On-device AI Software Engineering
- Melon: Breaking the Memory Wall for Resource-Efficient On-Device Machine Learning.
  [[pdf]](https://xumengwei.github.io/files/MobiSys22-Melo.pdf)
  [[code]](https://github.com/qipengwang/Melon)\
  venue: *The 20th Annual International Conference on Mobile Systems, Applications and Services 2022 (MobiSys-2022)*
  
- Mandheling: Mixed-Precision On-Device DNN Training with DSP Offloading.
  [[pdf]](https://arxiv.org/pdf/2206.07509.pdf)
  [[code]](https://github.com/UbiquitousLearning/Mandheling-DSP-Training)\
  venue: *Proceedings of the 28th Annual International Conference on Mobile Computing And Networking 2022 (MobiCom-2022)*

- A Comprehensive Benchmark of Deep Learning Libraries on Mobile Devices.
  [[pdf]](https://arxiv.org/pdf/2202.06512.pdf)
  [[code]](https://github.com/UbiquitousLearning/MobileDLFrameworksBenchmark)\
  venue: *The Web Conference 2022 (WWW-2022)*
  
- MLPerf Mobile Inference Benchmark: An Industry-Standard Open-Source Machine Learning Benchmark for On-Device AI.
  [[pdf]](https://proceedings.mlsys.org/paper/2022/file/7eabe3a1649ffa2b3ff8c02ebfd5659f-Paper.pdf)
  [[code]](https://github.com/mlcommons)\
  venue: *Proceedings of Machine Learning and Systems 4 (MLSys-2022)*

- NNStreamer: Efficient and Agile Development of On-Device AI Systems.
  [[pdf]](https://arxiv.org/pdf/2101.06371.pdf)
  [[code]](https://github.com/nnstreamer/nnstreamer)\
  venue: *IEEE/ACM 43rd International Conference on Software Engineering: Software Engineering in Practice 2021 (ICSE-SEIP-2021)*

- Mistify: Automating DNN Model Porting for On-Device Inference at the Edge.
  [[pdf]](https://www.usenix.org/system/files/nsdi21-guo.pdf)
  [[code]](https://github.com/PatrickGuo/Mistify)\
  venue: *Proceedings of the 18th USENIX Symposium on Networked Systems Design and Implementation 2021 (NSDI-2021)*
  
- An Empirical Study on Deployment Faults of Deep Learning Based Mobile Applications.
  [[pdf]](https://arxiv.org/pdf/2101.04930.pdf)
  [[code]](https://github.com/chenzhenpeng18/icse2021)\
  venue: *IEEE/ACM 43rd International Conference on Software Engineering 2021 (ICSE-2021)*
  
- A First Look at Deep Learning Apps on Smartphones.
  [[pdf]](https://arxiv.org/pdf/1812.05448.pdf)
  [[code]](https://github.com/xumengwei/MobileDL)\
  venue: *The Web Conference 2019 (WWW-2019)*

## On-device AI Algorithm
- Learning Compressed Embeddings for On-Device Inference.
  [[pdf]](https://proceedings.mlsys.org/paper/2022/file/812b4ba287f5ee0bc9d43bbf5bbe87fb-Paper.pdf)\
  venue: *Proceedings of Machine Learning and Systems 4 (MLSys-2022)*

- On-Device Learning for Model Personalization with Large-Scale Cloud-Coordinated Domain Adaption.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539263)
  [[code]](https://github.com/mikudehuane/MPDA)\
  venue: *The 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining 2022 (KDD-2022)*

- p-Meta: Towards On-device Deep Model Adaptation.
  [[pdf]](https://arxiv.org/pdf/2206.12705.pdf)\
  venue: *The 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining 2022 (KDD-2022)*

- DeepRec: On-device Deep Learning for Privacy-Preserving Sequential Recommendation in Mobile Commerce.
  [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3442381.3449942)
  [[code]](https://github.com/hanjialiang/DeepRec)\
  venue: *The Web Conference 2021 (WWW-2021)*
  
## Contribution
Any contributions to this list are more than welcome! Feel free to contact Yujin Huang <Jinx.Huang@monash.edu>.
