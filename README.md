# Awesome Adversarial Machine Learning [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome Machine Learning Security resources.

Also see [awesome-ml-for-cybersecurity](https://github.com/jivoi/awesome-ml-for-cybersecurity) and [The Definitive Security Data Science and Machine Learning Guide](http://www.covert.io/the-definitive-security-datascience-and-machinelearning-guide/).

- [Awesome Adversarial Machine Learning](#awesome-adversarial-machine-learning-)
  - [Terminology](#terminology)
  - [Threat Modeling](#threat-modeling)
  - [Controls Guidelines](#controls-guidelines)
  - [Case Studies](#case-studies)
  - [Attacks based on method](#attacks-based-on-method)
  - [Attacks based on domain](#attacks-based-on-domain)
  - [Attacks based on strategy](#attacks-based-on-strategy)
  - [CTF and Hackathons](#ctf-and-hackathons)
  - [Frameworks](#frameworks)

## Terminology
* [NIST: A Taxonomy and Terminology of Adversarial Machine Learning](https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8269-draft.pdf)

## Threat Modeling
* [ENISA: Artificial Intelligence Cybersecurity Challenges](https://www.enisa.europa.eu/news/publications/artificial-intelligence-cybersecurity-challenges)
* [MITRE: Adversarial Threat Landscape for Artificial-Intelligence Systems](https://atlas.mitre.org/)
* [The Threat of Offensive AI to Organizations](https://arxiv.org/pdf/2106.15764.pdf)
* [Threat of Adversarial Attacks on Deep Learning in Computer Vision: A Survey](https://arxiv.org/abs/1801.00553)

## Controls Guidelines
* [ENISA: Securing Machine Learning Algorithms](https://www.enisa.europa.eu/publications/securing-machine-learning-algorithms)
* [AISecOps](https://github.com/oasiszrz/awesome-AISecOps)

## Case Studies
* [MITRE reports on in-the-wild](https://github.com/mitre/advmlthreatmatrix/blob/master/pages/case-studies-page.md#case-studies-page)
* [Avito fights content theft using adversarial attacks](https://habr.com/ru/company/avito/blog/452142/)

## Attacks based on method
* [JSMA](https://ieeexplore.ieee.org/document/7467366)
* [One Pixel Attack](https://ieeexplore.ieee.org/abstract/document/8601309/)
* [DeepFool](https://arxiv.org/abs/1511.04599)
* [C&W](https://ieeexplore.ieee.org/abstract/document/7958570)
* [ATNs](https://arxiv.org/abs/1703.09387)
* [UPSET and ANGRI](https://arxiv.org/abs/1707.01159)
* Gradient-based:
  * [FGSM](https://arxiv.org/abs/1412.6572)
  * [Box-constrained L-BFGS](https://arxiv.org/pdf/1312.6199.pdf)
  * [I-FGSM](https://arxiv.org/abs/1607.02533)
  * [MI-FGSM](http://openaccess.thecvf.com/content_cvpr_2018/html/Dong_Boosting_Adversarial_Attacks_CVPR_2018_paper.html)
  * [DI^2-FGSM and M-DI^2FGSM](https://arxiv.org/abs/1803.06978)

Relationships between attacks:

<img src="./gradientrelationship.png" width="300">

## Attacks based on domain
* Computer Vision
* Speech Recognition
  * Model-specific research
    * [Kaldi](https://github.com/lealeasch/adversarialattacks)
    * [Lingvo](https://github.com/yaq007/cleverhans/tree/master/examples/adversarial_asr)
    * [Deepspeech](https://arxiv.org/pdf/1801.01944)
  * Approaches
    * [Man-in-the-Elevator](https://www.usenix.org/sites/default/files/conference/protected-files/woot15_slides_vaidya.pdf)
  * Noise hiding techniques
    * [DolphinAttack](https://github.com/USSLab/DolphinAttack)
    * [MPEG Compression](https://arxiv.org/pdf/1808.05665)

## Attacks based on strategy
* Information gathering
  * [Membership inference](https://arxiv.org/pdf/1610.05820)
  * [Deanonymization](https://www.cs.utexas.edu/~shmat/shmat_oak08netflix.pdf)
  * [Model inversion](https://dl.acm.org/doi/10.1145/2810103.2813677)
  * [Model stealing](https://arxiv.org/pdf/1805.02628)
  * [Blind-spot detection](https://arxiv.org/pdf/1901.04684)
  * [State prediction](https://ieeexplore.ieee.org/document/8716085)
* Denial of Service
  * [Poisoning DoS](https://arxiv.org/pdf/1708.08689.pdf)
  * [Sponge examples](https://arxiv.org/pdf/2006.03463)
* Biometric Spoofing
  * [Master fingerprint](https://arxiv.org/pdf/1705.07386)
  * [Face recognition evasion](https://dl.acm.org/doi/10.1145/2976749.2978392)


## CTF and Hackathons

* [NIPS 2017: Defense Against Adversarial Attack](https://www.kaggle.com/c/nips-2017-defense-against-adversarial-attack/data)
* [NIPS 2018 : Adversarial Vision Challenge](https://www.crowdai.org/challenges)
* [GeekPwn CAAD 2018](http://2018.geekpwn.org/en/index.html#4).
* [IJCAI-19 Alibaba Adversarial AI Challenge](https://tianchi.aliyun.com/markets/tianchi/ijcai19_en)
* [GeekPwn CAAD 2019](http://www.geekpwn.org/zh/index.html)
* [Positive Hack Days 2019: AI CTF](https://2019.phdays.com/en/program/contests/aI-ctf/)
* [Positive Hack Days 2021: AI CTF](https://2021.phdays.com/en/program/contests/ai-track/)
* [Positive Hack Days 2022: AI CTF](https://ai.ctf.su/)
* [UTCTF 2019 (FaceSafe, Bot Protection IV tasks)](https://github.com/utisss/UTCTF-19)
* [vishwaCTF21 (Good Driver Bad Driver task)](https://vishwactf.com/)

## Frameworks
* [**adversarial-robustness-toolbox**](https://github.com/IBM/adversarial-robustness-toolbox)
* [**foolbox**](https://github.com/bethgelab/foolbox)
* [**cleverhans**](https://github.com/tensorflow/cleverhans)
* [**advertorch**](https://github.com/BorealisAI/advertorch)
