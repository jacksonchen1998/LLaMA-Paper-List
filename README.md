# LLaMA-Paper-List

Collection of papers using LLaMA as backbone model.

## Contributors

<a href="https://github.com/jacksonchen1998/LLaMA-Paper-List/graphs/contributors">
  <img src="http://contributors.nn.ci/api?repo=jacksonchen1998/LLaMA-Paper-List" />
</a>

## Table of Contents

- [About LLaMA and related theory](#about-llama-and-related-theory)
- [LLaMA with parameter efficiency](#llama-with-parameter-efficiency)
- [Fine-tune LLaMA on downstream tasks](#fine-tune-llama-on-downstream-tasks)
- [LLaMA with retrieval](#llama-with-retrieval)
- [LLaMA using reinforcement learning](#llama-using-reinforcement-learning)
- [Quantitative analysis of LLaMA](#quantitative-analysis-of-llama)

## Papers

### About LLaMA and related theory

- **LLaMA: Open and Efficient Foundation Language Models.** arxiv 2023. [paper](https://arxiv.org/abs/2302.13971). [code](https://github.com/facebookresearch/llama/tree/main)<br />
*YHugo Touvron, Thibaut Lavril, Gautier Izacard, Xavier Martinet, Marie-Anne Lachaux, Timothée Lacroix, Baptiste Rozière, Naman Goyal, Eric Hambro, Faisal Azhar, Aurelien Rodriguez, Armand Joulin, Edouard Grave, Guillaume Lample*
- **Training Compute-Optimal Large Language Models.** NeurIPS 2022. [paper](https://arxiv.org/abs/2203.15556).<br />
*Jordan Hoffmann, Sebastian Borgeaud, Arthur Mensch, Elena Buchatskaya, Trevor Cai, Eliza Rutherford, Diego de Las Casas, Lisa Anne Hendricks, Johannes Welbl, Aidan Clark, Tom Hennigan, Eric Noland, Katie Millican, George van den Driessche, Bogdan Damoc, Aurelia Guy, Simon Osindero, Karen Simonyan, Erich Elsen, Jack W. Rae, Oriol Vinyals, Laurent Sifre*
- **Root Mean Square Layer Normalization.** NeurIPS 2019. [paper](https://arxiv.org/abs/1910.07467). [code](https://github.com/bzhangGo/rmsnorm) <br />
*Biao Zhang, Rico Sennrich*
- **GLU Variants Improve Transformer.** arxiv 2020. [paper](https://arxiv.org/abs/2002.05202). [code](https://github.com/Rishit-dagli/GLU) <br />
*Noam Shazeer*
- **RoFormer: Enhanced Transformer with Rotary Position Embedding.** arxiv 2021. [paper](https://arxiv.org/abs/2104.09864). [code](https://github.com/ZhuiyiTechnology/roformer) <br />
*Jianlin Su, Yu Lu, Shengfeng Pan, Ahmed Murtadha, Bo Wen, Yunfeng Liu*
- **Decoupled Weight Decay Regularization.** ICLR 2019. [paper](https://arxiv.org/abs/1711.05101). [code](https://github.com/loshchil/AdamW-and-SGDW) <br />
*Ilya Loshchilov, Frank Hutter*
- **Self-attention Does Not Need $O(n^2)$ Memory.** arxiv 2021. [paper](https://arxiv.org/abs/2112.05682). [code](https://github.com/lucidrains/memory-efficient-attention-pytorch) <br />
*Markus N. Rabe and Charles Staats*
- **FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness.** arxiv 2022. [paper](https://arxiv.org/abs/2205.14135). [code](https://github.com/HazyResearch/flash-attention) <br />
*Tri Dao, Daniel Y. Fu, Stefano Ermon, Atri Rudra, Christopher Ré*
- **Reducing Activation Recomputation in Large Transformer Models.** arxiv 2022. [paper](https://arxiv.org/abs/2205.14135). <br />
*Vijay Korthikanti, Jared Casper, Sangkug Lym, Lawrence McAfee, Michael Andersch, Mohammad Shoeybi, Bryan Catanzaro*

### LLaMA with parameter efficiency

- **LLaMA-Adapter: Efficient Fine-tuning of Language Models with Zero-init Attention.** arxiv 2023. [paper](https://arxiv.org/abs/2303.16199). [code](https://github.com/ZrrSkywalker/LLaMA-Adapter)<br />
*Zhang, Renrui and Han, Jiaming and Zhou, Aojun and Hu, Xiangfei and Yan, Shilin and Lu, Pan and Li, Hongsheng and Gao, Peng and Qiao, Yu*
- **LLaMA-Adapter V2: Parameter-Efficient Visual Instruction Model.** arxiv 2023. [paper](https://arxiv.org/abs/2304.15010). [code](https://github.com/ZrrSkywalker/LLaMA-Adapter)<br />
*Peng Gao, Jiaming Han, Renrui Zhang, Ziyi Lin, Shijie Geng, Aojun Zhou, Wei Zhang, Pan Lu, Conghui He, Xiangyu Yue, Hongsheng Li, Yu Qiao*
- **LLM-Adapters: An Adapter Family for Parameter-Efficient Fine-Tuning of Large Language Models.** arxiv 2023. [paper](https://arxiv.org/abs/2304.01933).<br />
*Zhiqiang Hu, Yihuai Lan, Lei Wang, Wanyu Xu, Ee-Peng Lim, Roy Ka-Wei Lee, Lidong Bing, Xing Xu, Soujanya Poria*
- **A Simple and Effective Pruning Approach for Large Language Models.** arxiv 2023. [paper](https://arxiv.org/abs/2306.11695v1). [code](https://github.com/locuslab/wanda) <br />
*Mingjie Sun, Zhuang Liu, Anna Bair, J. Zico Kolter*
- **LLM-Pruner: On the Structural Pruning of Large Language Models.** arxiv 2023. [paper](https://arxiv.org/abs/2305.11627v2). [code](https://github.com/horseee/llm-pruner) <br />
*Xinyin Ma, Gongfan Fang, Xinchao Wang*

### Fine-tune LLaMA on downstream tasks

- **ChatDoctor: A Medical Chat Model Fine-Tuned on a Large Language Model Meta-AI (LLaMA) Using Medical Domain Knowledge.**. arxiv 2023. [paper](https://arxiv.org/abs/2303.14070).<br />
*Yunxiang Li, Zihan Li, Kai Zhang, Ruilong Dan, Steve Jiang, You Zhang*
- **Efficient and Effective Text Encoding for Chinese LLaMA and Alpaca.** arxiv 2023. [paper](https://arxiv.org/abs/2304.08177). [code](https://github.com/ymcui/Chinese-LLaMA-Alpaca)<br />
*Yiming Cui, Ziqing Yang, Xin Yao*
- **PMC-LLaMA: Further Finetuning LLaMA on Medical Papers.** arxiv 2023. [paper](https://arxiv.org/abs/2304.14454).<br />
*Chaoyi Wu, Xiaoman Zhang, Ya Zhang, Yanfeng Wang, Weidi Xie*
- **Dr. LLaMA: Improving Small Language Models on PubMedQA
via Generative Data Augmentation.** arxiv 2023. [paper](https://arxiv.org/abs/2305.07804).<br />
*Zhen Guo, Peiqi Wang, Yanwei Wang, Shangdi Yu*
- **Goat: Fine-tuned LLaMA Outperforms GPT-4 on Arithmetic Tasks.** arxiv 2023. [paper](https://arxiv.org/abs/2305.14201).<br />
*Tiedong Liu, Bryan Kian Hsiang Low*
- **WizardLM: Empowering Large Language Models to Follow Complex Instructions.** arxiv 2023. [paper](https://arxiv.org/abs/2304.12244v2). [code](https://github.com/nlpxucan/wizardlm) <br />
*Can Xu, Qingfeng Sun, Kai Zheng, Xiubo Geng, Pu Zhao, Jiazhan Feng, Chongyang Tao, Daxin Jiang*
- **Enhancing Chat Language Models by Scaling High-quality Instructional Conversations.** arxiv 2023. [paper](https://arxiv.org/abs/2305.14233v1). [code](https://github.com/thunlp/ultrachat) <br />
*Ning Ding, Yulin Chen, Bokai Xu, Yujia Qin, Zhi Zheng, Shengding Hu, Zhiyuan Liu, Maosong Sun, BoWen Zhou*
- **LongForm: Optimizing Instruction Tuning for Long Text Generation with Corpus Extraction.** arxiv 2023. [paper](https://arxiv.org/abs/2304.08460v1). [code](https://github.com/akoksal/longform) <br />
*Abdullatif Köksal, Timo Schick, Anna Korhonen, Hinrich Schütze*
- **In-Context Learning User Simulators for Task-Oriented Dialog Systems.** arxiv 2023. [paper](https://arxiv.org/abs/2306.00774v1). [code](https://github.com/telepathylabsai/prompt-based-user-simulator) <br />
*Silvia Terragni, Modestas Filipavicius, Nghia Khau, Bruna Guedes, André Manso, Roland Mathis*
- **NetGPT: A Native-AI Network Architecture Beyond Provisioning Personalized Generative Services.** arxiv 2023. [paper](https://arxiv.org/pdf/2307.06148.pdf). [code]() <br />
*Yuxuan Chen, Rongpeng Li, Zhifeng Zhao, Chenghui Peng, Jianjun Wu, Ekram Hossain, Honggang Zhang*
- **On decoder-only architecture for speech-to-text and large language model integration.** arxiv 2023. [paper](https://arxiv.org/pdf/2307.03917.pdf). [code]() <br />
*Jian Wu, Yashesh Gaur, Zhuo Chen, Long Zhou, Yimeng Zhu, Tianrui Wang, Jinyu Li, Shujie Liu, Bo Ren, Linquan Liu, Yu Wu*
### LLaMA with retrieval

- **Polyglot or Not? Measuring Multilingual Encyclopedic Knowledge Retrieval from Foundation Language Models.** arxiv 2023. [paper](https://arxiv.org/abs/2305.13675). [code](https://github.com/daniel-furman/polyglot-or-not) <br />
*Tim Schott, Daniel Furman, Shreshta Bhat*
- **ReWOO: Decoupling Reasoning from Observations for Efficient Augmented Language Models** [paper](https://arxiv.org/abs/2305.18323v1). [code](https://github.com/billxbf/rewoo) <br />
*Binfeng Xu, Zhiyuan Peng, Bowen Lei, Subhabrata Mukherjee, Yuchen Liu, Dongkuan Xu*
- **Landmark Attention: Random-Access Infinite Context Length for Transformers.** arxiv 2023. [paper](https://arxiv.org/abs/2305.16300v1). [code](https://github.com/epfml/landmark-attention) <br />
*Amirkeivan Mohtashami, Martin Jaggi*

### LLaMA using reinforcement learning

- **LIMA: Less Is More for Alignment.** arxiv 2023. [paper](https://arxiv.org/abs/2305.11206v1). [code](https://github.com/h2oai/h2o-llmstudio) <br />
*Chunting Zhou, Pengfei Liu, Puxin Xu, Srini Iyer, Jiao Sun, Yuning Mao, Xuezhe Ma, Avia Efrat, Ping Yu, Lili Yu, Susan Zhang, Gargi Ghosh, Mike Lewis, Luke Zettlemoyer, Omer Levy*
- **RRHF: Rank Responses to Align Language Models with Human Feedback without tears.** [paper](https://arxiv.org/abs/2304.05302v2). [code](https://github.com/ganjinzero/rrhf) <br />
*Zheng Yuan, Hongyi Yuan, Chuanqi Tan, Wei Wang, Songfang Huang, Fei Huang*

### Quantitative analysis of LLaMA

- **SpQR: A Sparse-Quantized Representation for Near-Lossless LLM Weight Compression.** arxiv 2023. [paper](https://arxiv.org/abs/2306.03078v1). [code](https://github.com/vahe1994/spqr) <br />
*Tim Dettmers, Ruslan Svirschevski, Vage Egiazarian, Denis Kuznedelev, Elias Frantar, Saleh Ashkboos, Alexander Borzunov, Torsten Hoefler, Dan Alistarh*
- **SqueezeLLM: Dense-and-Sparse Quantization.** arxiv 2023. [paper](https://arxiv.org/abs/2306.07629v1). [code](https://github.com/squeezeailab/squeezellm) <br />
*Sehoon Kim, Coleman Hooper, Amir Gholami, Zhen Dong, Xiuyu Li, Sheng Shen, Michael W. Mahoney, Kurt Keutzer*

## How to contribute

Contributions are welcome! Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
