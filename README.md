<a name="readme-top"></a>

<div align="center">
  <a href="https://github.com/atfortes/Awesome-LLM-Reasoning/stargazers"><img src="https://img.shields.io/github/stars/atfortes/Awesome-LLM-Reasoning?style=for-the-badge" alt="Stargazers"></a>
  <a href="https://github.com/atfortes/Awesome-LLM-Reasoning/network/members"><img src="https://img.shields.io/github/forks/atfortes/Awesome-LLM-Reasoning?style=for-the-badge" alt="Forks"></a>
  <a href="https://github.com/atfortes/Awesome-LLM-Reasoning/graphs/contributors"><img src="https://img.shields.io/github/contributors/atfortes/Awesome-LLM-Reasoning?style=for-the-badge" alt="Contributors"></a>
  <a href="https://github.com/atfortes/Awesome-LLM-Reasoning/blob/main/LICENSE"><img src="https://img.shields.io/github/license/atfortes/Awesome-LLM-Reasoning?style=for-the-badge" alt="MIT License"></a>
</div>

<p align="center">
    <img src="assets/cot.svg" width="90%" style="align:center;"/>
</p>

<h1 align="center">Awesome LLM Reasoning</h1>

<p align="center">
    <b> Curated collection of papers and resources on how to unlock the reasoning ability of LLMs and MLLMs.</b>
</p>

<div align="center">
  <a href="https://buymeacoffee.com/atfortes"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?&logo=buy-me-a-coffee&logoColor=black" alt="Buy Me A Coffee"/></a>
</div>

<details>
  <summary>🗂️ Table of Contents</summary>
  <ol>
    <li><a href="#survey">Survey</a></li>
    <li><a href="#analysis">Analysis</a></li>
    <li><a href="#ltechnique">Technique</a>
      <ul>
        <li><a href="#llm">🔤 Reasoning in Large Language Models - <em>An Emergent Ability</em></a></li>
        <li><a href="#lm">🤏 Scaling Smaller Language Models to Reason</a></li>
        <li><a href="#mllm">🧠 Multimodal Reasoning in Large Language Models</a></li>
      </ul>
    </li>
    <li><a href="#other-useful-resources">Other Useful Resources</a></li>
    <li><a href="#other-awesome-lists">Other Awesome Lists</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

Also check out <b><a href=https://github.com/atfortes/Awesome-Controllable-Diffusion>Awesome-Controllable-Diffusion</a></b>.



## Survey



### 2024

1. **[Attention Heads of Large Language Models: A Survey.](https://arxiv.org/abs/2409.03752)** [[code](https://github.com/IAAR-Shanghai/Awesome-Attention-Heads)]

    *Zifan Zheng, Yezhaohui Wang, Yuxin Huang, Shichao Song, Bo Tang, Feiyu Xiong, Zhiyu Li.* Preprint'24

1. **[Internal Consistency and Self-Feedback in Large Language Models: A Survey.](https://arxiv.org/abs/2407.14507)** [[code](https://github.com/IAAR-Shanghai/ICSFSurvey)]

    *Xun Liang, Shichao Song, Zifan Zheng, Hanyu Wang, Qingchen Yu, Xunkai Li, Rong-Hua Li, Feiyu Xiong, Zhiyu Li.* Preprint'24

1. **[Puzzle Solving using Reasoning of Large Language Models: A Survey.](https://arxiv.org/abs/2402.11291)** [[code](https://puzzlellms.github.io/)]

    *Panagiotis Giadikiaroglou, Maria Lymperaiou, Giorgos Filandrianos, Giorgos Stamou.* Preprint'24

1. **[Large Language Models for Mathematical Reasoning: Progresses and Challenges.](https://arxiv.org/abs/2402.00157)** 

    *Janice Ahn, Rishu Verma, Renze Lou, Di Liu, Rui Zhang, Wenpeng Yin.* ACL'24

### 2022

1. **[Towards Reasoning in Large Language Models: A Survey.](https://arxiv.org/abs/2212.10403)** [[code](https://github.com/jeffhj/LM-reasoning)]

    *Jie Huang, Kevin Chen-Chuan Chang.* ACL'23 Findings

1. **[Reasoning with Language Model Prompting: A Survey.](https://arxiv.org/abs/2212.09597)** [[code](https://github.com/zjunlp/Prompt4ReasoningPapers)]

    *Shuofei Qiao, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen.* ACL'23

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



## Analysis



### 2024

1. **[From Medprompt to o1: Exploration of Run-Time Strategies for Medical Challenge Problems and Beyond.](https://arxiv.org/abs/2411.03590)**

    *Harsha Nori, Naoto Usuyama, Nicholas King, Scott Mayer McKinney, Xavier Fernandes, Sheng Zhang, Eric Horvitz.* Preprint'24

1. **[To CoT or not to CoT? Chain-of-thought helps mainly on math and symbolic reasoning.](https://arxiv.org/abs/2409.12183)**

    *Zayne Sprague, Fangcong Yin, Juan Diego Rodriguez, Dongwei Jiang, Manya Wadhwa, Prasann Singhal, Xinyu Zhao, Xi Ye, Kyle Mahowald, Greg Durrett.* Preprint'24

1. **[Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers.](https://arxiv.org/abs/2409.04109)**

    *Chenglei Si, Diyi Yang, Tatsunori Hashimoto.* Preprint'24

1. **[A Peek into Token Bias: Large Language Models Are Not Yet Genuine Reasoners.](https://arxiv.org/abs/2406.11050)** [[code](https://github.com/bowen-upenn/llm_token_bias)]

    *Bowen Jiang, Yangxinyu Xie, Zhuoqun Hao, Xiaomeng Wang, Tanwi Mallick, Weijie J. Su, Camillo J. Taylor, Dan Roth.* EMNLP'24

1. **[Iteration Head: A Mechanistic Study of Chain-of-Thought](https://arxiv.org/abs/2406.02128)**

    *Vivien Cabannes, Charles Arnal, Wassim Bouaziz, Alice Yang, Francois Charton, Julia Kempe.* NeurIPS'24

1. **[Do Large Language Models Latently Perform Multi-Hop Reasoning?](https://arxiv.org/abs/2402.16837)**

    *Sohee Yang, Elena Gribovskaya, Nora Kassner, Mor Geva, Sebastian Riedel.* ACL'24

1. **[Premise Order Matters in Reasoning with Large Language Models.](https://arxiv.org/abs/2402.08939)**

    *Xinyun Chen, Ryan A. Chi, Xuezhi Wang, Denny Zhou.* ICML'24

1. **[The Impact of Reasoning Step Length on Large Language Models.](https://arxiv.org/abs/2401.04925)**

    *Mingyu Jin, Qinkai Yu, Dong Shu, Haiyan Zhao, Wenyue Hua, Yanda Meng, Yongfeng Zhang, Mengnan Du.* ACL'24 Findings

1. **[Large Language Models Cannot Self-Correct Reasoning Yet.](https://arxiv.org/abs/2310.01798)**

    *Jie Huang, Xinyun Chen, Swaroop Mishra, Huaixiu Steven Zheng, Adams Wei Yu, Xinying Song, Denny Zhou.* ICLR'24

1. **[At Which Training Stage Does Code Data Help LLM Reasoning?](https://arxiv.org/pdf/2309.16298)**

    *Yingwei Ma, Yue Liu, Yue Yu, Yuanliang Zhang, Yu Jiang, Changjian Wang, Shanshan Li.* ICLR'24

### 2023

1. **[Measuring Faithfulness in Chain-of-Thought Reasoning.](https://arxiv.org/abs/2307.13702)**

    *Tamera Lanham, Anna Chen, Ansh Radhakrishnan, Benoit Steiner, Carson Denison, Danny Hernandez, Dustin Li, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė, Karina Nguyen, Newton Cheng, Nicholas Joseph, Nicholas Schiefer, Oliver Rausch, Robin Larson, Sam McCandlish, Sandipan Kundu, Saurav Kadavath, Shannon Yang, Thomas Henighan, Timothy Maxwell, Timothy Telleen-Lawton, Tristan Hume, Zac Hatfield-Dodds, Jared Kaplan, Jan Brauner, Samuel R. Bowman, Ethan Perez.* Preprint'23

1. **[Faith and Fate: Limits of Transformers on Compositionality.](https://arxiv.org/abs/2305.18654)**

    *Nouha Dziri, Ximing Lu, Melanie Sclar, Xiang Lorraine Li, Liwei Jiang, Bill Yuchen Lin, Peter West, Chandra Bhagavatula, Ronan Le Bras, Jena D. Hwang, Soumya Sanyal, Sean Welleck, Xiang Ren, Allyson Ettinger, Zaid Harchaoui, Yejin Choi.* NeurIPS'23

1. **[Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting.](https://arxiv.org/abs/2305.04388)** [[code](https://github.com/milesaturpin/cot-unfaithfulness)]

    *Miles Turpin, Julian Michael, Ethan Perez, Samuel R. Bowman.* NeurIPS'23

1. **[A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity.](https://arxiv.org/abs/2302.04023)**

    *Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung.* AACL'23

1. **[Large Language Models Can Be Easily Distracted by Irrelevant Context.](https://arxiv.org/abs/2302.00093)**

    *Freda Shi, Xinyun Chen, Kanishka Misra, Nathan Scales, David Dohan, Ed Chi, Nathanael Schärli, Denny Zhou.* ICML'23
   
1. **[On Second Thought, Let's Not Think Step by Step! Bias and Toxicity in Zero-Shot Reasoning.](https://arxiv.org/abs/2212.08061)**

    *Omar Shaikh, Hongxin Zhang, William Held, Michael Bernstein, Diyi Yang.* ACL'23

1. **[Towards Understanding Chain-of-Thought Prompting: An Empirical Study of What Matters.](https://arxiv.org/abs/2212.10001)** [[code](https://github.com/sunlab-osu/Understanding-CoT)]

    *Boshi Wang, Sewon Min, Xiang Deng, Jiaming Shen, You Wu, Luke Zettlemoyer, Huan Sun.* ACL'23

1. **[Challenging BIG-Bench Tasks and Whether Chain-of-Thought Can Solve Them.](https://arxiv.org/abs/2210.09261)** [[code](https://github.com/suzgunmirac/BIG-Bench-Hard)]

    *Mirac Suzgun, Nathan Scales, Nathanael Schärli, Sebastian Gehrmann, Yi Tay, Hyung Won Chung, Aakanksha Chowdhery, Quoc V. Le, Ed H. Chi, Denny Zhou, Jason Wei.* ACL'23 Findings

### 2022

1. **[Emergent Abilities of Large Language Models.](https://arxiv.org/abs/2206.07682)** [[blog](https://ai.googleblog.com/2022/11/characterizing-emergent-phenomena-in.html)]

    *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus.* TMLR'22

1. **[Can language models learn from explanations in context?](https://arxiv.org/abs/2204.02329)**

    *Andrew K. Lampinen, Ishita Dasgupta, Stephanie C. Y. Chan, Kory Matthewson, Michael Henry Tessler, Antonia Creswell, James L. McClelland, Jane X. Wang, Felix Hill.* EMNLP'22

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



<h2 id="ltechnique">Technique</h2>



<h3 id="llm">🔤 Reasoning in Large Language Models - <i>An Emergent Ability</i></h3>

### 2024

1. **[Training Language Models to Self-Correct via Reinforcement Learning.](https://arxiv.org/abs/2409.12917)**

    *Aviral Kumar, Vincent Zhuang, Rishabh Agarwal, Yi Su, JD Co-Reyes, Avi Singh, Kate Baumli, Shariq Iqbal, Colton Bishop, Rebecca Roelofs, Lei M. Zhang, Kay McKinney, Disha Shrivastava, Cosmin Paduraru, George Tucker, Doina Precup, Feryal Behbahani, Aleksandra Faust.* Preprint'24

1. **[OpenAI o1.](https://openai.com/index/learning-to-reason-with-llms/)**

    *Open AI Team.* Technical Report'24

1. **[Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents.](https://arxiv.org/abs/2408.07199)**

    *Pranav Putta, Edmund Mills, Naman Garg, Sumeet Motwani, Chelsea Finn, Divyansh Garg, Rafael Rafailov.* Preprint'24

1. **[DotaMath: Decomposition of Thought with Code Assistance and Self-correction for Mathematical Reasoning.](https://arxiv.org/abs/2407.04078)** [[code](https://github.com/ChengpengLi1003/DotaMath)]

    *Chengpeng Li, Guanting Dong, Mingfeng Xue, Ru Peng, Xiang Wang, Dayiheng Liu.* Preprint'24

1. **[LLM-ARC: Enhancing LLMs with an Automated Reasoning Critic.](https://arxiv.org/abs/2406.17663)**

    *Aditya Kalyanpur, Kailash Saravanakumar, Victor Barres, Jennifer Chu-Carroll, David Melville, David Ferrucci.* Preprint'24

1. **[Q\*: Improving Multi-step Reasoning for LLMs with Deliberative Planning.](https://arxiv.org/abs/2406.14283)**

    *Chaojie Wang, Yanchen Deng, Zhiyi Lv, Shuicheng Yan, An Bo.* Preprint'24

1. **[Buffer of Thoughts: Thought-Augmented Reasoning with Large Language Models.](https://arxiv.org/abs/2406.04271)** [[code](https://github.com/YangLing0818/buffer-of-thought-llm)]

    *Ling Yang, Zhaochen Yu, Tianjun Zhang, Shiyi Cao, Minkai Xu, Wentao Zhang, Joseph E. Gonzalez, Bin Cui.* Preprint'24

1. **[Toward Self-Improvement of LLMs via Imagination, Searching, and Criticizing.](https://arxiv.org/abs/2404.12253)**

    *Ye Tian, Baolin Peng, Linfeng Song, Lifeng Jin, Dian Yu, Haitao Mi, Dong Yu.* Preprint'24

1. **[Self-playing Adversarial Language Game Enhances LLM Reasoning.](https://arxiv.org/abs/2404.10642)**

    *Pengyu Cheng, Tianhao Hu, Han Xu, Zhisong Zhang, Yong Dai, Lei Han, Nan Du.* Preprint'24

1. **[Evaluating Mathematical Reasoning Beyond Accuracy.](https://arxiv.org/abs/2404.05692)**

    *Shijie Xia, Xuefeng Li, Yixin Liu, Tongshuang Wu, Pengfei Liu.* Preprint'24

1. **[Advancing LLM Reasoning Generalists with Preference Trees.](https://arxiv.org/abs/2404.02078)**

    *Lifan Yuan, Ganqu Cui, Hanbin Wang, Ning Ding, Xingyao Wang, Jia Deng, Boji Shan, Huimin Chen, Ruobing Xie, Yankai Lin, Zhenghao Liu, Bowen Zhou, Hao Peng, Zhiyuan Liu, Maosong Sun.* Preprint'24

1. **[LLM3: Large Language Model-based Task and Motion Planning with Motion Failure Reasoning.](https://arxiv.org/abs/2403.11552)** [[code](https://github.com/AssassinWS/LLM-TAMP)]

    *Shu Wang, Muzhi Han, Ziyuan Jiao, Zeyu Zhang, Ying Nian Wu, Song-Chun Zhu, Hangxin Liu.* IROS'24

1. **[Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking.](https://arxiv.org/abs/2403.09629)**

    *Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman.* Preprint'24

1. **[GLoRe: When, Where, and How to Improve LLM Reasoning via Global and Local Refinements.](https://arxiv.org/abs/2402.10963)**

    *Alex Havrilla, Sharath Raparthy, Christoforus Nalmpantis, Jane Dwivedi-Yu, Maksym Zhuravinskyi, Eric Hambro, Roberta Railneau.* ICML'24

1. **[Chain-of-Thought Reasoning Without Prompting.](https://arxiv.org/abs/2402.10200)**

    *Xuezhi Wang, Denny Zhou.* Preprint'24

1. **[V-STaR: Training Verifiers for Self-Taught Reasoners.](https://arxiv.org/abs/2402.06457)**

    *Arian Hosseini, Xingdi Yuan, Nikolay Malkin, Aaron Courville, Alessandro Sordoni, Rishabh Agarwal.* Preprint'24

1. **[InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning.](https://arxiv.org/abs/2402.06332)**

    *Huaiyuan Ying, Shuo Zhang, Linyang Li, Zhejian Zhou, Yunfan Shao, Zhaoye Fei, Yichuan Ma, Jiawei Hong, Kuikun Liu, Ziyi Wang, Yudong Wang, Zijian Wu, Shuaibin Li, Fengzhe Zhou, Hongwei Liu, Songyang Zhang, Wenwei Zhang, Hang Yan, Xipeng Qiu, Jiayu Wang, Kai Chen, Dahua Lin.* Preprint'24

1. **[Self-Discover: Large Language Models Self-Compose Reasoning Structures.](https://arxiv.org/abs/2402.03620)**

    *Pei Zhou, Jay Pujara, Xiang Ren, Xinyun Chen, Heng-Tze Cheng, Quoc V. Le, Ed H. Chi, Denny Zhou, Swaroop Mishra, Huaixiu Steven Zheng.* Preprint'24

1. **[DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models.](https://arxiv.org/abs/2402.03300)**

    *Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Xiao Bi, Haowei Zhang, Mingchuan Zhang, Y.K. Li, Y. Wu, Daya Guo.* Preprint'24

1. **[K-Level Reasoning with Large Language Models.](https://arxiv.org/abs/2402.01521)**

    *Yadong Zhang, Shaoguang Mao, Tao Ge, Xun Wang, Yan Xia, Man Lan, Furu Wei.* Preprint'24

1. **[Efficient Tool Use with Chain-of-Abstraction Reasoning.](https://arxiv.org/abs/2401.17464)**

    *Silin Gao, Jane Dwivedi-Yu, Ping Yu, Xiaoqing Ellen Tan, Ramakanth Pasunuru, Olga Golovneva, Koustuv Sinha, Asli Celikyilmaz, Antoine Bosselut, Tianlu Wang.* Preprint'24

1. **[Teaching Language Models to Self-Improve through Interactive Demonstrations.](https://arxiv.org/abs/2310.13522)**

    *Xiao Yu, Baolin Peng, Michel Galley, Jianfeng Gao, Zhou Yu.* NAACL'24

1. **[Enhancing Zero-Shot Chain-of-Thought Reasoning in Large Language Models through Logic.](https://arxiv.org/abs/2309.13339)** [[code](https://github.com/xf-zhao/LoT)]

    *Xufeng Zhao, Mengdi Li, Wenhao Lu, Cornelius Weber, Jae Hee Lee, Kun Chu, Stefan Wermter.* COLING'24

1. **[Chain-of-Verification Reduces Hallucination in Large Language Models.](https://arxiv.org/abs/2309.11495)**

    *Shehzaad Dhuliawala, Mojtaba Komeili, Jing Xu, Roberta Raileanu, Xian Li, Asli Celikyilmaz, Jason Weston.* ACL'24 Findings

1. **[Skeleton-of-Thought: Large Language Models Can Do Parallel Decoding.](https://arxiv.org/abs/2307.15337)**

    *Xuefei Ning, Zinan Lin, Zixuan Zhou, Huazhong Yang, Yu Wang.* ICLR'24

1. **[Question Decomposition Improves the Faithfulness of Model-Generated Reasoning.](https://arxiv.org/abs/2307.11768)** [[code](https://github.com/anthropics/DecompositionFaithfulnessPaper)]

    *Ansh Radhakrishnan, Karina Nguyen, Anna Chen, Carol Chen, Carson Denison, Danny Hernandez, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė, Newton Cheng, Nicholas Joseph, Nicholas Schiefer, Oliver Rausch, Sam McCandlish, Sheer El Showk, Tamera Lanham, Tim Maxwell, Venkatesa Chandrasekaran, Zac Hatfield-Dodds, Jared Kaplan, Jan Brauner, Samuel R. Bowman, Ethan Perez.* Preprint'23

1. **[Let's Verify Step by Step.](https://arxiv.org/abs/2305.20050)**

    *Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe.* ICLR'24

1. **[REFINER: Reasoning Feedback on Intermediate Representations.](https://arxiv.org/abs/2304.01904)** [[project](https://debjitpaul.github.io/refiner/)] [[code](https://github.com/debjitpaul/refiner)]

    *Debjit Paul, Mete Ismayilzada, Maxime Peyrard, Beatriz Borges, Antoine Bosselut, Robert West, Boi Faltings.* EACL'24

1. **[Active Prompting with Chain-of-Thought for Large Language Models.](https://arxiv.org/abs/2302.12246)** [[code](https://github.com/shizhediao/active-cot)]

    *Shizhe Diao, Pengcheng Wang, Yong Lin, Tong Zhang.* ACL'24

1. **[Language Models as Inductive Reasoners.](https://arxiv.org/abs/2212.10923)**

    *Zonglin Yang, Li Dong, Xinya Du, Hao Cheng, Erik Cambria, Xiaodong Liu, Jianfeng Gao, Furu Wei.* EACL'24

### 2023

1. **[Boosting LLM Reasoning: Push the Limits of Few-shot Learning with Reinforced In-Context Pruning.](https://arxiv.org/abs/2312.08901)**

    *Xijie Huang, Li Lyna Zhang, Kwang-Ting Cheng, Mao Yang.* Preprint'23

1. **[Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning.](https://arxiv.org/abs/2305.12295)** [[code](https://github.com/teacherpeterpan/Logic-LLM)]

    *Liangming Pan, Alon Albalak, Xinyi Wang, William Yang Wang.* EMNLP'23 Findings

1. **[Recursion of Thought: A Divide and Conquer Approach to Multi-Context Reasoning with Language Models.](https://arxiv.org/abs/2306.06891)** [[code](https://github.com/soochan-lee/RoT)] [[poster](https://soochanlee.com/img/rot/rot_poster.pdf)]

    *Soochan Lee, Gunhee Kim.* ACL'23 Findings

1. **[Reasoning with Language Model is Planning with World Model.](https://arxiv.org/abs/2305.14992)**

    *Shibo Hao, Yi Gu, Haodi Ma, Joshua Jiahua Hong, Zhen Wang, Daisy Zhe Wang, Zhiting Hu.* EMNLP'23

1. **[Reasoning Implicit Sentiment with Chain-of-Thought Prompting.](https://arxiv.org/abs/2305.11255)** [[code](https://github.com/scofield7419/THOR-ISA)]

    *Hao Fei, Bobo Li, Qian Liu, Lidong Bing, Fei Li, Tat-Seng Chua.* ACL'23

1. **[Tree of Thoughts: Deliberate Problem Solving with Large Language Models.](https://arxiv.org/abs/2305.10601)** [[code](https://github.com/ysymyth/tree-of-thought-llm)]

    *Shunyu Yao, Dian Yu, Jeffrey Zhao, Izhak Shafran, Thomas L. Griffiths, Yuan Cao, Karthik Narasimhan.* NeurIPS'23

1. **[SatLM: Satisfiability-Aided Language Models Using Declarative Prompting.](https://arxiv.org/abs/2305.09656)** [[code](https://github.com/xiye17/sat-lm)]

    *Xi Ye, Qiaochu Chen, Isil Dillig, Greg Durrett.* NeurIPS'23

1. **[ART: Automatic multi-step reasoning and tool-use for large language models.](https://arxiv.org/abs/2303.09014)**

    *Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro.* Preprint'23

1. **[Automatic Prompt Augmentation and Selection with Chain-of-Thought from Labeled Data.](https://arxiv.org/abs/2302.12822)** [[code](https://github.com/shizhediao/automate-cot)]

    *KaShun Shum, Shizhe Diao, Tong Zhang.* EMNLP'23 Findings

1. **[Synthetic Prompting: Generating Chain-of-Thought Demonstrations for Large Language Models.](https://arxiv.org/abs/2302.00618)**

    *Zhihong Shao, Yeyun Gong, Yelong Shen, Minlie Huang, Nan Duan, Weizhu Chen.* ICML'23

1. **[Faithful Chain-of-Thought Reasoning.](https://arxiv.org/abs/2301.13379)**

    *Qing Lyu, Shreya Havaldar, Adam Stein, Li Zhang, Delip Rao, Eric Wong, Marianna Apidianaki, Chris Callison-Burch.* IJCNLP-AACL'23

1. **[Rethinking with Retrieval: Faithful Large Language Model Inference.](https://arxiv.org/abs/2301.00303)**

    *Hangfeng He, Hongming Zhang, Dan Roth.* Preprint'23

1. **[LAMBADA: Backward Chaining for Automated Reasoning in Natural Language.](https://arxiv.org/abs/2212.13894)**

    *Seyed Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu, Deepak Ramachandran.* ACL'23

1. **[Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions.](https://arxiv.org/abs/2212.10509)** [[code](https://github.com/StonyBrookNLP/ircot)]

    *Harsh Trivedi, Niranjan Balasubramanian, Tushar Khot, Ashish Sabharwal.* ACL'23

1. **[Large Language Models are Reasoners with Self-Verification.](https://arxiv.org/abs/2212.09561)** [[code](https://github.com/WENGSYX/Self-Verification)]

    *Yixuan Weng, Minjun Zhu, Shizhu He, Kang Liu, Jun Zhao.* EMNLP'23 Findings

1. **[Can Retriever-Augmented Language Models Reason? The Blame Game Between the Retriever and the Language Model.](https://arxiv.org/abs/2212.09146)** [[code](https://github.com/McGill-NLP/retriever-lm-reasoning)]

    *Parishad BehnamGhader, Santiago Miret, Siva Reddy.* EMNLP'23 Findings

1. **[Complementary Explanations for Effective In-Context Learning.](https://arxiv.org/abs/2211.13892)**

    *Xi Ye, Srinivasan Iyer, Asli Celikyilmaz, Ves Stoyanov, Greg Durrett, Ramakanth Pasunuru.* ACL'23 Findings

1. **[Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks.](https://arxiv.org/abs/2211.12588)** [[code](https://github.com/wenhuchen/program-of-thoughts)]

    *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen.* TMLR'23

1. **[Unsupervised Explanation Generation via Correct Instantiations.](https://arxiv.org/abs/2211.11160)**

    *Sijie Cheng, Zhiyong Wu, Jiangjie Chen, Zhixing Li, Yang Liu, Lingpeng Kong.* AAAI'23

1. **[PAL: Program-aided Language Models.](https://arxiv.org/abs/2211.10435)** [[project](https://reasonwithpal.com/)] [[code](https://github.com/reasoning-machines/pal)]

    *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig.* ICML'23

1. **[Solving Math Word Problems via Cooperative Reasoning induced Language Models.](https://arxiv.org/abs/2210.16257)** [[code](https://github.com/TianHongZXY/CoRe)]

    *Xinyu Zhu, Junjie Wang, Lin Zhang, Yuxiang Zhang, Ruyi Gan, Jiaxing Zhang, Yujiu Yang.* ACL'23

1. **[Large Language Models Can Self-Improve.](https://arxiv.org/abs/2210.11610)**

    *Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han.* EMNLP'23

1. **[Mind's Eye: Grounded language model reasoning through simulation.](https://arxiv.org/abs/2210.05359)**

    *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai.* ICLR'23

1. **[Automatic Chain of Thought Prompting in Large Language Models.](https://arxiv.org/abs/2210.03493)** [[code](https://github.com/amazon-research/auto-cot)]

    *Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola.* ICLR'23

1. **[Language Models are Multilingual Chain-of-Thought Reasoners.](https://arxiv.org/abs/2210.03057)**

    *Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, Jason Wei.* ICLR'23

1. **[Ask Me Anything: A simple strategy for prompting language models.](https://arxiv.org/abs/2210.02441)** [[code](https://github.com/hazyresearch/ama_prompting)]

    *Simran Arora, Avanika Narayan, Mayee F. Chen, Laurel Orr, Neel Guha, Kush Bhatia, Ines Chami, Frederic Sala, Christopher Ré.* ICLR'23

1. **[Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning.](https://arxiv.org/abs/2209.14610)** [[project](https://promptpg.github.io/)] [[code](https://github.com/lupantech/PromptPG)]

    *Pan Lu, Liang Qiu, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Tanmay Rajpurohit, Peter Clark, Ashwin Kalyan.* ICLR'23

1. **[Making Large Language Models Better Reasoners with Step-Aware Verifier.](https://arxiv.org/abs/2206.02336)**

    *Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen.* ACL'23

1. **[Least-to-most prompting enables complex reasoning in large language models.](https://arxiv.org/abs/2205.10625)**

    *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le, Ed Chi.* ICLR'23

1. **[Self-consistency improves chain of thought reasoning in language models.](https://arxiv.org/abs/2203.11171)**

    *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou.* ICLR'23

### 2022

1. **[Retrieval Augmentation for Commonsense Reasoning: A Unified Approach.](https://arxiv.org/abs/2210.12887)** [[code](https://github.com/wyu97/RACo)]

    *Wenhao Yu, Chenguang Zhu, Zhihan Zhang, Shuohang Wang, Zhuosheng Zhang, Yuwei Fang, Meng Jiang.* EMNLP'22

1. **[Language Models of Code are Few-Shot Commonsense Learners.](https://arxiv.org/abs/2210.07128)** [[code](https://github.com/madaan/cocogen)]

    *Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang, Graham Neubig.* EMNLP'22

1. **[Solving Quantitative Reasoning Problems with Language Models.](https://arxiv.org/abs/2206.14858)** [[blog](https://ai.googleblog.com/2022/06/minerva-solving-quantitative-reasoning.html)]

    *Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay Ramasesh, Ambrose Slone, Cem Anil, Imanol Schlag, Theo Gutman-Solo, Yuhuai Wu, Behnam Neyshabur, Guy Gur-Ari, Vedant Misra.* NeurIPS'22

1. **[Large Language Models Still Can't Plan.](https://arxiv.org/abs/2206.10498)** [[code](https://github.com/karthikv792/gpt-plan-benchmark)]

    *Karthik Valmeekam, Alberto Olmo, Sarath Sreedharan, Subbarao Kambhampati.* NeurIPS'22

1. **[Large Language Models are Zero-Shot Reasoners.](https://arxiv.org/abs/2205.11916)**

    *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa.* NeurIPS'22

1. **[Iteratively Prompt Pre-trained Language Models for Chain of Thought.](https://arxiv.org/abs/2203.08383)** [[code](https://github.com/sunlab-osu/iterprompt)]

    *Boshi Wang, Xiang Deng, Huan Sun.* EMNLP'22

1. **[Chain of Thought Prompting Elicits Reasoning in Large Language Models.](https://arxiv.org/abs/2201.11903)** [[blog](https://ai.googleblog.com/2022/05/language-models-perform-reasoning-via.html)]

    *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou.* NeurIPS'22

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



### <h3 id="lm">🤏 Scaling Smaller Language Models to Reason<h3/>

### 2024

1. **[MathScale: Scaling Instruction Tuning for Mathematical Reasoning.](https://arxiv.org/abs/2403.02884)**

    *Zhengyang Tang, Xingxing Zhang, Benyou Wang, Furu Wei.* Preprint'24

### 2023

1. **[Learning Deductive Reasoning from Synthetic Corpus based on Formal Logic.](https://arxiv.org/abs/2308.07336)** [[code](https://github.com/hitachi-nlp/FLD)]

    *Terufumi Morishita, Gaku Morio, Atsuki Yamaguchi, Yasuhiro Sogawa.* ICML'23

1. **[Symbolic Chain-of-Thought Distillation: Small Models Can Also "Think" Step-by-Step.](https://arxiv.org/abs/2306.14050)** [[code](https://github.com/allenai/cot_distillation)]

    *Liunian Harold Li, Jack Hessel, Youngjae Yu, Xiang Ren, Kai-Wei Chang, Yejin Choi.* ACL'23

1. **[Specializing Smaller Language Models towards Multi-Step Reasoning.](https://arxiv.org/abs/2301.12726)**

    *Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal, Tushar Khot.* ICML'23

1. **[Large Language Models Are Reasoning Teachers.](https://arxiv.org/abs/2212.10071)** [[code](https://github.com/itsnamgyu/reasoning-teacher)]

    *Namgyu Ho, Laura Schmid, Se-Young Yun.* ACL'23

1. **[Teaching Small Language Models to Reason.](https://arxiv.org/abs/2212.08410)**

    *Lucie Charlotte Magister, Jonathan Mallinson, Jakub Adamek, Eric Malmi, Aliaksei Severyn.* ACL'23 Short

1. **[Distilling Multi-Step Reasoning Capabilities of Large Language Models into Smaller Models via Semantic Decompositions.](https://arxiv.org/abs/2212.00193)**

    *Kumar Shridhar, Alessandro Stolfo, Mrinmaya Sachan.* ACL'23 Findings

### 2022

1. **[Scaling Instruction-Finetuned Language Models.](https://arxiv.org/abs/2210.11416)**

    *Hyung Won Chung, Le Hou, Shayne Longpre, Barret Zoph, Yi Tay, William Fedus, Eric Li, Xuezhi Wang, Mostafa Dehghani, Siddhartha Brahma, Albert Webson, Shixiang Shane Gu, Zhuyun Dai, Mirac Suzgun, Xinyun Chen, Aakanksha Chowdhery, Sharan Narang, Gaurav Mishra, Adams Yu, Vincent Zhao, Yanping Huang, Andrew Dai, Hongkun Yu, Slav Petrov, Ed H. Chi, Jeff Dean, Jacob Devlin, Adam Roberts, Denny Zhou, Quoc V. Le, Jason Wei.* JMLR'22

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



### <h3 id="mllm">🧠 Multimodal Reasoning in Large Language Models<h3/>

### 2024

1. **[Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models.](https://arxiv.org/abs/2406.09403)** [[project](https://visualsketchpad.github.io/)] [[code](https://github.com/Yushi-Hu/VisualSketchpad)]

    *Yushi Hu, Weijia Shi, Xingyu Fu, Dan Roth, Mari Ostendorf, Luke Zettlemoyer, Noah A Smith, Ranjay Krishna.* Preprint'24

1. **[Chart-based Reasoning: Transferring Capabilities from LLMs to VLMs.](https://arxiv.org/abs/2403.12596)**

    *Victor Carbune, Hassan Mansoor, Fangyu Liu, Rahul Aralikatte, Gilles Baechler, Jindong Chen, Abhanshu Sharma.* NAACL'24 Findings

1. **[SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities.](https://arxiv.org/abs/2401.12168)** [[project](https://spatial-vlm.github.io/)]

    *Boyuan Chen, Zhuo Xu, Sean Kirmani, Brian Ichter, Danny Driess, Pete Florence, Dorsa Sadigh, Leonidas Guibas, Fei Xia.* CVPR'24

1. **[Chain-of-Table: Evolving Tables in the Reasoning Chain for Table Understanding.](https://arxiv.org/abs/2401.04398)**

    *Zilong Wang, Hao Zhang, Chun-Liang Li, Julian Martin Eisenschlos, Vincent Perot, Zifeng Wang, Lesly Miculicich, Yasuhisa Fujii, Jingbo Shang, Chen-Yu Lee, Tomas Pfister.* ICLR'24

1. **[Link-Context Learning for Multimodal LLMs.](https://arxiv.org/abs/2308.07891)** [[code](https://github.com/isekai-portal/Link-Context-Learning)]

    *Yan Tai, Weichen Fan, Zhao Zhang, Feng Zhu, Rui Zhao, Ziwei Liu.* CVPR'24

### 2023

1. **[Gemini in Reasoning: Unveiling Commonsense in Multimodal Large Language Models.](https://arxiv.org/abs/2312.17661)**

    *Yuqing Wang, Yun Zhao.* Preprint'23

1. **[G-LLaVA: Solving Geometric Problems with Multi-Modal Large Language Model.](https://arxiv.org/abs/2312.11370)**

    *Jiahui Gao, Renjie Pi, Jipeng Zhang, Jiacheng Ye, Wanjun Zhong, Yufei Wang, Lanqing Hong, Jianhua Han, Hang Xu, Zhenguo Li, Lingpeng Kong.* Preprint'23

1. **[Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models.](https://arxiv.org/abs/2304.09842)** [[project](https://chameleon-llm.github.io/)] [[code](https://github.com/lupantech/chameleon-llm)]

    *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao.* NeurIPS'23

1. **[MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action.](https://arxiv.org/abs/2303.11381)** [[project](https://multimodal-react.github.io/)] [[code](https://github.com/microsoft/MM-REACT)] [[demo](https://huggingface.co/spaces/microsoft-cognitive-service/mm-react)]

    *Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang.* Preprint'23

1. **[ViperGPT: Visual Inference via Python Execution for Reasoning.](https://arxiv.org/abs/2303.08128)** [[project](https://viper.cs.columbia.edu/)] [[code](https://github.com/cvlab-columbia/viper)]

    *Dídac Surís, Sachit Menon, Carl Vondrick.* ICCV'23

1. **[Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models.](https://arxiv.org/abs/2303.04671)** [[code](https://github.com/microsoft/visual-chatgpt)]

    *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan.* Preprint'23

1. **[Multimodal Chain-of-Thought Reasoning in Language Models.](https://arxiv.org/abs/2302.00923)** [[code](https://github.com/amazon-science/mm-cot)]

    *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, Alex Smola.* Preprint'23

1. **[Visual Programming: Compositional Visual Reasoning without Training.](https://arxiv.org/abs/2211.11559)** [[project](https://prior.allenai.org/projects/visprog)] [[code](https://github.com/allenai/visprog)]

    *Tanmay Gupta, Aniruddha Kembhavi.* CPVR'23

1. **[Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language.](https://arxiv.org/abs/2204.00598)** [[project](https://socraticmodels.github.io/)] [[code](https://github.com/google-research/google-research/tree/master/socraticmodels)]

    *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence.* ICLR'23

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



## Other Useful Resources



- **[LLM Reasoners](https://github.com/Ber666/llm-reasoners)**  A library for advanced large language model reasoning.
- **[Chain-of-Thought Hub](https://github.com/FranxYao/chain-of-thought-hub)**  Benchmarking LLM reasoning performance with chain-of-thought prompting.
- **[ThoughtSource](https://github.com/OpenBioLink/ThoughtSource)**  Central and open resource for data and tools related to chain-of-thought reasoning in large language models.
- **[AgentChain](https://github.com/jina-ai/agentchain)**  Chain together LLMs for reasoning & orchestrate multiple large models for accomplishing complex tasks.
- **[google/Cascades](https://github.com/google-research/cascades)**  Python library which enables complex compositions of language models such as scratchpads, chain of thought, tool use, selection-inference, and more.
- **[LogiTorch](https://github.com/LogiTorch/logitorch)**  PyTorch-based library for logical reasoning on natural language.
- **[salesforce/LAVIS](https://github.com/salesforce/LAVIS)**  One-stop Library for Language-Vision Intelligence.
- **[facebookresearch/RAM](https://github.com/facebookresearch/RAM)**  A framework to study AI models in Reasoning, Alignment, and use of Memory (RAM).

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



## Other Awesome Lists



- **[Awesome-Controllable-Generation](https://github.com/atfortes/Awesome-Controllable-Generation)**  Collection of papers and resources on Controllable Generation using Diffusion Models.
- **[Chain-of-ThoughtsPapers](https://github.com/Timothyxxx/Chain-of-ThoughtsPapers)**  A trend starts from "Chain-of-Thought Prompting Elicits Reasoning in Large Language Models".
- **[LM-reasoning](https://github.com/jeffhj/LM-reasoning)**  Collection of papers and resources on Reasoning in Large Language Models.
- **[Prompt4ReasoningPapers](https://github.com/zjunlp/Prompt4ReasoningPapers)**  Repository for the paper "Reasoning with Language Model Prompting: A Survey".
- **[ReasoningNLP](https://github.com/FreedomIntelligence/ReasoningNLP)**  Paper list on reasoning in NLP
- **[Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)**  Curated list of Large Language Model.
- **[Awesome LLM Self-Consistency](https://github.com/SuperBruceJia/Awesome-LLM-Self-Consistency)**  Curated list of Self-consistency in Large Language Models.
- **[Deep-Reasoning-Papers](https://github.com/floodsung/Deep-Reasoning-Papers)**  Recent Papers including Neural-Symbolic Reasoning, Logical Reasoning, and Visual Reasoning.

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



## Contributing

- Add a new paper or update an existing paper, thinking about which category the work should belong to.
- Use the same format as existing entries to describe the work.
- Add the abstract link of the paper (`/abs/` format if it is an arXiv publication).

**Don't worry if you do something wrong, it will be fixed for you!**

### Contributors

<a href="https://github.com/atfortes/Awesome-LLM-Reasoning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=atfortes/Awesome-LLM-Reasoning" />
</a>

### Star History

[![Star History Chart](https://api.star-history.com/svg?repos=atfortes/Awesome-LLM-Reasoning&type=Timeline)](https://star-history.com/#atfortes/Awesome-LLM-Reasoning&Timeline)
