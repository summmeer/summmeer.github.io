# 📚 Selected Publications 
\* indicates equal contribution.

*This page highlights my work on diffusion language models. For a complete list of publications, please refer to my CV.*

## Large Scale Diffusion LMs

[Dream-VL & Dream-VLA: Open Vision-Language and Vision-Language-Action Models with Diffusion Language Model Backbone](https://arxiv.org/abs/2512.22615) (technical report)

Jiacheng Ye\*, **Shansan Gong**\*, Jiahui Gao, Junming Fan, Shuang Wu, Wei Bi, Haoli Bai, Lifeng Shang, Lingpeng Kong

The open VL and VLA models that fully unlock discrete diffusion's advantages in long-horizon planning and parallel action generation for multimodal tasks.

---

[DreamOn: Diffusion Language Models For Code Infilling Beyond Fixed-size Canvas](https://arxiv.org/abs/2602.01326) (ICLR 2026)

Zirui Wu, Lin Zheng, Zhihui Xie, Jiacheng Ye, Jiahui Gao, **Shansan Gong**, Yansong Feng, Zhenguo Li, Wei Bi, Guorui Zhou, Lingpeng Kong

A novel diffusion framework that enables dynamic, variable-length generation.

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/diffucoder-fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffuCoder: Understanding and Improving Masked Diffusion Models for Code Generation](https://arxiv.org/abs/2506.20639) (ICLR 2026)

**Shansan Gong**, Ruixiang Zhang, Huangjie Zheng, Jiatao Gu, Navdeep Jaitly, Lingpeng Kong, Yizhe Zhang

[DiffuCoder ![](https://img.shields.io/github/stars/apple/ml-diffucoder?style=social)](https://github.com/apple/ml-diffucoder) \| We introduce DiffuCoder (7B), show that higher temperature diversifies both token choices and generation order; and propose coupled-GRPO, a diffusion-native RL method that avoids semi-AR and improves performance.

</div>
</div>

---

[Continuously Augmented Discrete Diffusion model for Categorical Generative Modeling](https://arxiv.org/abs/2510.01329) (ICLR 2026)

Huangjie Zheng, **Shansan Gong**, Ruixiang Zhang, Tianrong Chen, Jiatao Gu, Mingyuan Zhou, Navdeep Jaitly, Yizhe Zhang

We propose CADD, a framework that augments the discrete state space with a paired diffusion in a continuous latent space.

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/diffullama-fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scaling Diffusion Language Models via Adaptation from Autoregressive Models](https://arxiv.org/abs/2410.17891) (ICLR 2025)

**Shansan Gong**\*, Shivam Agarwal\*, Yizhe Zhang, Jiacheng Ye, Lin Zheng, Mukai Li, Chenxin An, Peilin Zhao, Wei Bi, Jiawei Han, Hao Peng, Lingpeng Kong

[DiffuLLaMA ![](https://img.shields.io/github/stars/HKUNLP/DiffuLLaMA?style=social)](https://github.com/HKUNLP/DiffuLLaMA) \| We convert AR models ranging from 127M to 7B parameters (GPT2 and LLaMA) into diffusion models DiffuGPT and DiffuLLaMA.

</div>
</div>

---

## Initial Exploration for Text Diffusion

[Beyond Autoregression: Discrete Diffusion for Complex Reasoning and Planning](https://arxiv.org/abs/2410.14157) (ICLR 2025)

Jiacheng Ye, Jiahui Gao, **Shansan Gong**, Lin Zheng, Xin Jiang, Zhenguo Li, Lingpeng Kong

[Code ![](https://img.shields.io/github/stars/HKUNLP/diffusion-vs-ar?style=social)](https://github.com/HKUNLP/diffusion-vs-ar) \| We demonstrate how discrete diffusion models effectively learn difficult subgoals that elude autoregressive models.

---

[Diffusion of Thoughts: Chain-of-Thought Reasoning in Diffusion Language Models](https://arxiv.org/pdf/2402.07754) (NeurIPS 2024)

Jiacheng Ye\*, **Shansan Gong**\*, Liheng Chen\*, Lin Zheng, Jiahui Gao, Han Shi, Chuan Wu, Zhenguo Li, Wei Bi, Lingpeng Kong

[DoT ![](https://img.shields.io/github/stars/HKUNLP/diffusion-of-thoughts?style=social)](https://github.com/HKUNLP/diffusion-of-thoughts) \| DoT allows the reasoning steps to diffuse over time through the diffusion process.

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023 Findings</div><img src='images/emnlp23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffuSeq-v2: Bridging Discrete and Continuous Text Spaces for Accelerated Seq2Seq Diffusion Models](https://arxiv.org/pdf/2310.05793.pdf)

**Shansan Gong**, Mukai Li, Jiangtao Feng, Zhiyong Wu, Lingpeng Kong

[Code](https://github.com/Shark-NLP/DiffuSeq/tree/diffuseq-v2)\| Accelerated version of DiffuSeq, where the discrete noise bridges the training and sampling stages, saving time consumption of these two stages.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/iclr23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DiffuSeq: Sequence to Sequence Text Generation With Diffusion Models](https://arxiv.org/pdf/2210.08933.pdf)

**Shansan Gong**, Mukai Li, Jiangtao Feng, Zhiyong Wu, Lingpeng Kong

[DiffuSeq ![](https://img.shields.io/github/stars/Shark-NLP/DiffuSeq?style=social)](https://github.com/Shark-NLP/DiffuSeq) <strong><span class='show_paper_citations' data='F86VNoMAAAAJ:2osOgNQ5qMEC'></span></strong>  | [Poster](./uploads/DiffuSeq_poster-v1.pdf) \|
<!-- - Our proposed **DiffuSeq** is trained end-to-end in a classifier-free manner, targeting Seq2Seq tasks. -->
<!-- - We establish a theoretical connection among AR, NAR and DiffuSeq models (refer to our original paper). -->
DiffuSeq is a powerful model for text generation, matching or even surpassing competitive AR, iterative NAR, and PLMs on quality and diversity.
</div>
</div>

<!-- ---

## Long context language models

[GIRAFFE: Design Choices for Extending the Context Length of Visual Language Models](https://arxiv.org/abs/2412.12735) (ACL 2025)

Mukai Li, Lei Li, **Shansan Gong**, Qi Liu

[GIRAFFE](https://github.com/kiaia/GIRAFFE) \| Explore design choices to extend the context window of existing VLMs. -->

<!-- --- -->

<!-- [Why Does the Effective Context Length of LLMs Fall Short?](https://arxiv.org/abs/2410.18745) (ICLR 2025)

Chenxin An, Jun Zhang, Ming Zhong, Lei Li, **Shansan Gong**, Yao Luo, Jingjing Xu, Lingpeng Kong

[STRING ![](https://img.shields.io/github/stars/HKUNLP/STRING?style=social)](https://github.com/HKUNLP/STRING) \| A  training-free method after analyzing the effective context length of LLMs. -->

<!-- ---

[L-Eval: Instituting Standardized Evaluation for Long Context Language Models](https://arxiv.org/pdf/2307.11088.pdf) (ACL 2024 <span style="color: red;">Outstanding</span>)

Chenxin An, **Shansan Gong**, Ming Zhong, Mukai Li, Jun Zhang, Lingpeng Kong, Xipeng Qiu

[L-Eval ![](https://img.shields.io/github/stars/OpenLMLab/LEval?style=social)](https://github.com/OpenLMLab/LEval) \| A  manually checked benchmark for long context language models with 20 sub-tasks.

---

[Training-Free Long-Context Scaling of Large Language Models](https://arxiv.org/pdf/2402.17463) (ICML 2024)

Chenxin An, Fei Huang, Jun Zhang, **Shansan Gong**, Xipeng Qiu, Chang Zhou, Lingpeng Kong

[ChunkLlama ![](https://img.shields.io/github/stars/HKUNLP/ChunkLlama?style=social)](https://github.com/HKUNLP/ChunkLlama) \| A  training-free method to extend Llama 2/3-70B to 100k context length.

---

[In-Context Learning with Many Demonstration Examples](https://arxiv.org/pdf/2302.04931.pdf)

Mukai Li, **Shansan Gong**, Jiangtao Feng, Yiheng Xu, Jun Zhang, Zhiyong Wu, Lingpeng Kong

[EVALM](https://github.com/Shark-NLP/EVALM) \| The pre-trained language model with efficient attention and 8k context length. -->

<!-- ---

## LLMs

[BBA: Bi-Modal Behavioral Alignment for Reasoning with Large Vision-Language Models](https://arxiv.org/pdf/2402.13577) (ACL 2024 Findings)

Xueliang Zhao, Xinting Huang, Tingchen Fu, Qintong Li, **Shansan Gong**, Lemao Liu, Wei Bi, Lingpeng Kong

BBA is designed to maximize the potential of DSL in augmenting complex multi-modal reasoning tasks. -->

<!-- ---

## Before LLMs -->

<!-- [Transferable and Efficient: Unifying Dynamic Multi-Domain Product Categorization](https://aclanthology.org/2023.acl-industry.46/) (ACL 2023 Industry)

**Shansan Gong**\*, Zelin Zhou\*, Shuo Wang, Fengjiao Chen, Xiujie Song, Xuezhi Cao, Yunsen Xian, Kenny Zhu

[Data](https://github.com/ze-lin/TaLR) \| [Poster](./uploads/TaLR-poster.pdf) \| A new framework to unify the categorization process as well as leverage knowledge from different domains. -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2022</div><img src='images/sigir22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Positive, Negative and Neutral: Modeling Implicit Feedback in Session-based News Recommendation](https://dl.acm.org/doi/10.1145/3477495.3532040)

**Shansan Gong**, Kenny Q. Zhu

[TCAR ![](https://img.shields.io/github/stars/summmeer/session-based-news-recommendation?style=social)](https://github.com/summmeer/session-based-news-recommendation) | [Slides](./uploads/SIGIR22-fp1153-slides.pdf)\|
By leveraging different kinds of implicit feedback, we alleviate the trade-off between the precision and diversity.

</div>
</div> -->