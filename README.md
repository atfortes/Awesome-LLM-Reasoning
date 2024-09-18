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



1. **Reasoning with Language Model Prompting: A Survey.** `ACL 2023`

    *Shuofei Qiao, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen.* [[Paper](https://arxiv.org/abs/2212.09597)] [[Code](https://github.com/zjunlp/Prompt4ReasoningPapers)], 2022.12

1. **Towards Reasoning in Large Language Models: A Survey.** `ACL 2023 Findings`

    *Jie Huang, Kevin Chen-Chuan Chang.* [[Paper](https://arxiv.org/abs/2212.10403)] [[Code](https://github.com/jeffhj/LM-reasoning)], 2022.12

1. **Large Language Models for Mathematical Reasoning: Progresses and Challenges.** `ACL 2024`

   *Janice Ahn, Rishu Verma, Renze Lou, Di Liu, Rui Zhang, Wenpeng Yin.* [[Paper](https://arxiv.org/abs/2402.00157)], 2024.2

1. **Puzzle Solving using Reasoning of Large Language Models: A Survey.** `Preprint`

    *Panagiotis Giadikiaroglou, Maria Lymperaiou, Giorgos Filandrianos, Giorgos Stamou.* [[Paper](https://arxiv.org/abs/2402.11291)] [[Code](https://puzzlellms.github.io/)], 2024.2

1. **Internal Consistency and Self-Feedback in Large Language Models: A Survey.** `Preprint`

    *Xun Liang, Shichao Song, Zifan Zheng, Hanyu Wang, Qingchen Yu, Xunkai Li, Rong-Hua Li, Feiyu Xiong, Zhiyu Li.* [[Paper](https://arxiv.org/abs/2407.14507)] [[Code](https://github.com/IAAR-Shanghai/ICSFSurvey)], 2024.7

1. **Attention Heads of Large Language Models: A Survey** `Preprint`

    *Zifan Zheng, Yezhaohui Wang, Yuxin Huang, Shichao Song, Bo Tang, Feiyu Xiong, Zhiyu Li.* [[Paper](https://arxiv.org/abs/2409.03752)] [[Code](https://github.com/IAAR-Shanghai/Awesome-Attention-Heads)], 2024.9

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



## Analysis



1. **Can language models learn from explanations in context?** `EMNLP 2022`

    *Andrew K. Lampinen, Ishita Dasgupta, Stephanie C. Y. Chan, Kory Matthewson, Michael Henry Tessler, Antonia Creswell, James L. McClelland, Jane X. Wang, Felix Hill.* [[Paper](https://arxiv.org/abs/2204.02329)], 2022.4

1. **Emergent Abilities of Large Language Models.** `TMLR 2022`
   
    *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus.* [[Paper](https://arxiv.org/abs/2206.07682)] [[Blog](https://ai.googleblog.com/2022/11/characterizing-emergent-phenomena-in.html)], 2022.6

1. **Challenging BIG-Bench Tasks and Whether Chain-of-Thought Can Solve Them.** `ACL 2023 Findings`

    *Mirac Suzgun, Nathan Scales, Nathanael Schärli, Sebastian Gehrmann, Yi Tay, Hyung Won Chung, Aakanksha Chowdhery, Quoc V. Le, Ed H. Chi, Denny Zhou, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.09261)] [[Code](https://github.com/suzgunmirac/BIG-Bench-Hard)], 2022.10

1. **Towards Understanding Chain-of-Thought Prompting: An Empirical Study of What Matters.** `ACL 2023`
   
    *Boshi Wang, Sewon Min, Xiang Deng, Jiaming Shen, You Wu, Luke Zettlemoyer, Huan Sun.* [[Paper](https://arxiv.org/abs/2212.10001)] [[Code](https://github.com/sunlab-osu/Understanding-CoT)], 2022.12

1. **On Second Thought, Let's Not Think Step by Step! Bias and Toxicity in Zero-Shot Reasoning.** `ACL 2023`

    *Omar Shaikh, Hongxin Zhang, William Held, Michael Bernstein, Diyi Yang.* [[Paper](https://arxiv.org/abs/2212.08061)], 2022.12

1. **Large Language Models Can Be Easily Distracted by Irrelevant Context.** `ICML 2023`

    *Freda Shi, Xinyun Chen, Kanishka Misra, Nathan Scales, David Dohan, Ed Chi, Nathanael Schärli, Denny Zhou.* [[Paper](https://arxiv.org/abs/2302.00093)], 2023.1

1. **A Multitask, Multilingual, Multimodal Evaluation of ChatGPT on Reasoning, Hallucination, and Interactivity.** `AACL 2023`

    *Yejin Bang, Samuel Cahyawijaya, Nayeon Lee, Wenliang Dai, Dan Su, Bryan Wilie, Holy Lovenia, Ziwei Ji, Tiezheng Yu, Willy Chung, Quyet V. Do, Yan Xu, Pascale Fung.* [[Paper](https://arxiv.org/abs/2302.04023)], 2023.2

1. **Language Models Don't Always Say What They Think: Unfaithful Explanations in Chain-of-Thought Prompting.** `NeurIPS 2023`

    *Miles Turpin, Julian Michael, Ethan Perez, Samuel R. Bowman.* [[Paper](https://arxiv.org/abs/2305.04388)] [[Code](https://github.com/milesaturpin/cot-unfaithfulness)], 2023.5

1. **Faith and Fate: Limits of Transformers on Compositionality.** `NeurIPS 2023`

    *Nouha Dziri, Ximing Lu, Melanie Sclar, Xiang Lorraine Li, Liwei Jiang, Bill Yuchen Lin, Peter West, Chandra Bhagavatula, Ronan Le Bras, Jena D. Hwang, Soumya Sanyal, Sean Welleck, Xiang Ren, Allyson Ettinger, Zaid Harchaoui, Yejin Choi.* [[Paper](https://arxiv.org/abs/2305.18654)], 2023.5

1. **Measuring Faithfulness in Chain-of-Thought Reasoning.** `Preprint`

    *Tamera Lanham, Anna Chen, Ansh Radhakrishnan, Benoit Steiner, Carson Denison, Danny Hernandez, Dustin Li, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė, Karina Nguyen, Newton Cheng, Nicholas Joseph, Nicholas Schiefer, Oliver Rausch, Robin Larson, Sam McCandlish, Sandipan Kundu, Saurav Kadavath, Shannon Yang, Thomas Henighan, Timothy Maxwell, Timothy Telleen-Lawton, Tristan Hume, Zac Hatfield-Dodds, Jared Kaplan, Jan Brauner, Samuel R. Bowman, Ethan Perez.* [[Paper](https://arxiv.org/abs/2307.13702)], 2023.7

1. **At Which Training Stage Does Code Data Help LLM Reasoning?** `ICLR 2024`

    *Yingwei Ma, Yue Liu, Yue Yu, Yuanliang Zhang, Yu Jiang, Changjian Wang, Shanshan Li.* [[Paper](https://arxiv.org/pdf/2309.16298)], 2023.09

   
1. **Large Language Models Cannot Self-Correct Reasoning Yet.** `ICLR 2024`

    *Jie Huang, Xinyun Chen, Swaroop Mishra, Huaixiu Steven Zheng, Adams Wei Yu, Xinying Song, Denny Zhou.* [[Paper](https://arxiv.org/abs/2310.01798)], 2023.10
   


1. **The Impact of Reasoning Step Length on Large Language Models.** `ACL 2024 Findings`

    *Mingyu Jin, Qinkai Yu, Dong shu, Haiyan Zhao, Wenyue Hua, Yanda Meng, Yongfeng Zhang, Mengnan Du.* [[Paper](https://arxiv.org/abs/2401.04925)], 2024.1

1. **Premise Order Matters in Reasoning with Large Language Models.** `ICML 2024`

    *Xinyun Chen, Ryan A. Chi, Xuezhi Wang, Denny Zhou.* [[Paper](https://arxiv.org/abs/2402.08939)], 2024.2

1. **Do Large Language Models Latently Perform Multi-Hop Reasoning?** `ACL 2024`

    *Sohee Yang, Elena Gribovskaya, Nora Kassner, Mor Geva, Sebastian Riedel.* [[Paper](https://arxiv.org/abs/2402.16837)], 2024.2

1. **Can LLMs Generate Novel Research Ideas? A Large-Scale Human Study with 100+ NLP Researchers.** `Preprint`

    *Chenglei Si, Diyi Yang, Tatsunori Hashimoto.* [[Paper](https://arxiv.org/abs/2409.04109)], 2024.9

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



<h2 id="ltechnique">Technique</h2>



<h3 id="llm">🔤 Reasoning in Large Language Models - <i>An Emergent Ability</i></h3>

1. **Chain of Thought Prompting Elicits Reasoning in Large Language Models.** `NeurIPS 2022`

    *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou.* [[Paper](https://arxiv.org/abs/2201.11903)] [[Blog](https://ai.googleblog.com/2022/05/language-models-perform-reasoning-via.html)], 2022.1

1. **Self-consistency improves chain of thought reasoning in language models.** `ICLR 2023`

    *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou.* [[Paper](https://arxiv.org/abs/2203.11171)], 2022.3

1. **Iteratively Prompt Pre-trained Language Models for Chain of Thought.** `EMNLP 2022`

    *Boshi Wang, Xiang Deng, Huan Sun.* [[Paper](https://arxiv.org/abs/2203.08383)] [[Code](https://github.com/sunlab-osu/iterprompt)]

1. **Least-to-most prompting enables complex reasoning in large language models.** `ICLR 2023`

    *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le, Ed Chi.* [[Paper](https://arxiv.org/abs/2205.10625)], 2022.5

1. **Large Language Models are Zero-Shot Reasoners.** `NeurIPS 2022`
   
    *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa.* [[Paper](https://arxiv.org/abs/2205.11916)], 2022.5

1. **Making Large Language Models Better Reasoners with Step-Aware Verifier.** `ACL 2023`
   
    *Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen.* [[Paper](https://arxiv.org/abs/2206.02336)], 2022.6

1. **Large Language Models Still Can't Plan.** `NeurIPS 2022`
   
    *Karthik Valmeekam, Alberto Olmo, Sarath Sreedharan, Subbarao Kambhampati.* [[Paper](https://arxiv.org/abs/2206.10498)] [[Code](https://github.com/karthikv792/gpt-plan-benchmark)], 2022.6

1. **Solving Quantitative Reasoning Problems with Language Models.** `NeurIPS 2022`

    *Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay Ramasesh, Ambrose Slone, Cem Anil, Imanol Schlag, Theo Gutman-Solo, Yuhuai Wu, Behnam Neyshabur, Guy Gur-Ari, Vedant Misra.* [[Paper](https://arxiv.org/abs/2206.14858)] [[Blog](https://ai.googleblog.com/2022/06/minerva-solving-quantitative-reasoning.html)], 2022.6

1. **Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning.** `ICLR 2023`

    *Pan Lu, Liang Qiu, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Tanmay Rajpurohit, Peter Clark, Ashwin Kalyan.* [[Project](https://promptpg.github.io/)] [[Paper](https://arxiv.org/abs/2209.14610)] [[Code](https://github.com/lupantech/PromptPG)], 2022.9

1. **Ask Me Anything: A simple strategy for prompting language models.** `ICLR 2023`

    *Simran Arora, Avanika Narayan, Mayee F. Chen, Laurel Orr, Neel Guha, Kush Bhatia, Ines Chami, Frederic Sala, Christopher Ré.* [[Paper](https://arxiv.org/abs/2210.02441)] [[Code](https://github.com/hazyresearch/ama_prompting)], 2022.10

1. **Language Models are Multilingual Chain-of-Thought Reasoners.** `ICLR 2023`
   
    *Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.03057)], 2022.10

1. **Automatic Chain of Thought Prompting in Large Language Models.** `ICLR 2023`
   
    *Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola.* [[Paper](https://arxiv.org/abs/2210.03493)] [[Code](https://github.com/amazon-research/auto-cot)], 2022.10

1. **Mind's Eye: Grounded language model reasoning through simulation.** `ICLR 2023`
   
    *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai.* [[Paper](https://arxiv.org/abs/2210.05359)], 2022.10

1. **Language Models of Code are Few-Shot Commonsense Learners.** `EMNLP 2022`
   
    *Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang, Graham Neubig.* [[Paper](https://arxiv.org/abs/2210.07128)] [[Code](https://github.com/madaan/cocogen)], 2022.10

1. **Large Language Models Can Self-Improve.** `EMNLP 2023`
   
    *Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han.* [[Paper](https://arxiv.org/abs/2210.11610)], 2022.10

1. **Retrieval Augmentation for Commonsense Reasoning: A Unified Approach.** `EMNLP 2022`
   
    *Wenhao Yu, Chenguang Zhu, Zhihan Zhang, Shuohang Wang, Zhuosheng Zhang, Yuwei Fang, Meng Jiang.* [[Paper](https://arxiv.org/abs/2210.12887)] [[Code](https://github.com/wyu97/RACo)], 2022.10

1. **Solving Math Word Problems via Cooperative Reasoning induced Language Models.** `ACL 2023`

   *Xinyu Zhu, Junjie Wang, Lin Zhang, Yuxiang Zhang, Ruyi Gan, Jiaxing Zhang, Yujiu Yang.* [[Paper](https://arxiv.org/abs/2210.16257)] [[Code](https://github.com/TianHongZXY/CoRe)], 2022.10

1. **PAL: Program-aided Language Models.** `ICML 2023`
   
    *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig.* [[Project](https://reasonwithpal.com/)] [[Paper](https://arxiv.org/abs/2211.10435)] [[Code](https://github.com/reasoning-machines/pal)], 2022.11

1. **Unsupervised Explanation Generation via Correct Instantiations.** `AAAI 2023`

    *Sijie Cheng, Zhiyong Wu, Jiangjie Chen, Zhixing Li, Yang Liu, Lingpeng Kong.* [[Paper](https://arxiv.org/abs/2211.11160)], 2022.11

1. **Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks.** `TMLR 2023`

    *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen.* [[Paper](https://arxiv.org/abs/2211.12588)] [[Code](https://github.com/wenhuchen/program-of-thoughts)], 2022.11

1. **Complementary Explanations for Effective In-Context Learning.** `ACL 2023 Findings`

    *Xi Ye, Srinivasan Iyer, Asli Celikyilmaz, Ves Stoyanov, Greg Durrett, Ramakanth Pasunuru.* [[Paper](https://arxiv.org/abs/2211.13892)], 2022.11

1. **Can Retriever-Augmented Language Models Reason? The Blame Game Between the Retriever and the Language Model.** `EMNLP 2023 Findings`

    *Parishad BehnamGhader, Santiago Miret, Siva Reddy.* [[Paper](https://arxiv.org/abs/2212.09146)] [[Code](https://github.com/McGill-NLP/retriever-lm-reasoning)], 2022.12

1. **Large Language Models are reasoners with Self-Verification.** `EMNLP 2023 Findings`

    *Yixuan Weng, Minjun Zhu, Shizhu He, Kang Liu, Jun Zhao.* [[Paper](https://arxiv.org/abs/2212.09561)] [[Code](https://github.com/WENGSYX/Self-Verification)], 2022.12

1. **Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions.** `ACL 2023`

    *Harsh Trivedi, Niranjan Balasubramanian, Tushar Khot, Ashish Sabharwal.* [[Paper](https://arxiv.org/abs/2212.10509)] [[Code](https://github.com/StonyBrookNLP/ircot)], 2022.12

1. **Language Models as Inductive Reasoners.** `EACL 2024`

    *Zonglin Yang, Li Dong, Xinya Du, Hao Cheng, Erik Cambria, Xiaodong Liu, Jianfeng Gao, Furu Wei.* [[Paper](https://arxiv.org/abs/2212.10923)], 2022.12

1. **LAMBADA: Backward Chaining for Automated Reasoning in Natural Language.** `ACL 2023`

    *Seyed Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu, Deepak Ramachandran.* [[Paper](https://arxiv.org/abs/2212.13894)], 2022.12

1. **Rethinking with Retrieval: Faithful Large Language Model Inference.** `Preprint`

    *Hangfeng He, Hongming Zhang, Dan Roth.* [[Paper](https://arxiv.org/abs/2301.00303)], 2023.1

1. **Faithful Chain-of-Thought Reasoning.** `IJCNLP-AACL 2023`

    *Qing Lyu, Shreya Havaldar, Adam Stein, Li Zhang, Delip Rao, Eric Wong, Marianna Apidianaki, Chris Callison-Burch.* [[Paper](https://arxiv.org/abs/2301.13379)], 2023.1

1. **Synthetic Prompting: Generating Chain-of-Thought Demonstrations for Large Language Models.** `ICML 2023`

    *Zhihong Shao, Yeyun Gong, Yelong Shen, Minlie Huang, Nan Duan, Weizhu Chen.* [[Paper](https://arxiv.org/abs/2302.00618)], 2023.2

1. **Active Prompting with Chain-of-Thought for Large Language Models.** `ACL 2024`

    *Shizhe Diao, Pengcheng Wang, Yong Lin, Tong Zhang.* [[Paper](https://arxiv.org/abs/2302.12246)] [[Code](https://github.com/shizhediao/active-cot)], 2023.2

1. **Automatic Prompt Augmentation and Selection with Chain-of-Thought from Labeled Data.** `EMNLP 2023 Findings`

    *KaShun Shum, Shizhe Diao, Tong Zhang.* [[Paper](https://arxiv.org/abs/2302.12822)] [[Code](https://github.com/shizhediao/automate-cot)], 2023.2

1. **ART: Automatic multi-step reasoning and tool-use for large language models.** `Preprint`

    *Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro.* [[Paper](https://arxiv.org/abs/2303.09014)], 2023.3
    
1. **REFINER: Reasoning Feedback on Intermediate Representations.** `EACL 2024`

    *Debjit Paul, Mete Ismayilzada, Maxime Peyrard, Beatriz Borges, Antoine Bosselut, Robert West, Boi Faltings.* [[Project](https://debjitpaul.github.io/refiner/)] [[Paper](https://arxiv.org/abs/2304.01904)] [[Code](https://github.com/debjitpaul/refiner)], 2023.4

1. **SatLM: Satisfiability-Aided Language Models Using Declarative Prompting** `NeurIPS 2023`

    *Xi Ye, Qiaochu Chen, Isil Dillig, Greg Durrett* [[Paper](https://arxiv.org/abs/2305.09656)] [[Code](https://github.com/xiye17/sat-lm)], 2023.5

1. **Tree of Thoughts: Deliberate Problem Solving with Large Language Models.** `NeurIPS 2023`

    *Shunyu Yao, Dian Yu, Jeffrey Zhao, Izhak Shafran, Thomas L. Griffiths, Yuan Cao, Karthik Narasimhan.* [[Paper](https://arxiv.org/abs/2305.10601)] [[Code](https://github.com/ysymyth/tree-of-thought-llm)], 2023.5

1. **Reasoning Implicit Sentiment with Chain-of-Thought Prompting** `ACL 2023`

    *Hao Fei, Bobo Li, Qian Liu, Lidong Bing, Fei Li, Tat-Seng Chua.* [[Paper](https://arxiv.org/abs/2305.11255)] [[Code](https://github.com/scofield7419/THOR-ISA)], 2023.05

1. **Reasoning with Language Model is Planning with World Model.** `EMNLP 2023`

    *Shibo Hao, Yi Gu, Haodi Ma, Joshua Jiahua Hong, Zhen Wang, Daisy Zhe Wang, Zhiting Hu.* [[Paper](https://arxiv.org/abs/2305.14992)], 2023.5

1. **Let's Verify Step by Step.** `ICLR 2024`

    *Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe.* [[Paper](https://arxiv.org/abs/2305.20050)], 2023.5

1. **Recursion of Thought: A Divide and Conquer Approach to Multi-Context Reasoning with Language Models.** `ACL 2023 Findings`

    *Soochan Lee, Gunhee Kim.* [[Paper](https://arxiv.org/abs/2306.06891)] [[Code](https://github.com/soochan-lee/RoT)] [[Poster](https://soochanlee.com/img/rot/rot_poster.pdf)], 2023.6

1. **Question Decomposition Improves the Faithfulness of Model-Generated Reasoning.** `Preprint`

    *Ansh Radhakrishnan, Karina Nguyen, Anna Chen, Carol Chen, Carson Denison, Danny Hernandez, Esin Durmus, Evan Hubinger, Jackson Kernion, Kamilė Lukošiūtė, Newton Cheng, Nicholas Joseph, Nicholas Schiefer, Oliver Rausch, Sam McCandlish, Sheer El Showk, Tamera Lanham, Tim Maxwell, Venkatesa Chandrasekaran, Zac Hatfield-Dodds, Jared Kaplan, Jan Brauner, Samuel R. Bowman, Ethan Perez.* [[Paper](https://arxiv.org/abs/2307.11768)] [[Code](https://github.com/anthropics/DecompositionFaithfulnessPaper)], 2023.7

1. **Skeleton-of-Thought: Large Language Models Can Do Parallel Decoding.** `ICLR 2024`

    *Xuefei Ning, Zinan Lin, Zixuan Zhou, Huazhong Yang, Yu Wang.* [[Paper](https://arxiv.org/abs/2307.15337)], 2023.7

1. **Chain-of-Verification Reduces Hallucination in Large Language Models.** `ACL 2024 Findings`

    *Shehzaad Dhuliawala, Mojtaba Komeili, Jing Xu, Roberta Raileanu, Xian Li, Asli Celikyilmaz, Jason Weston.* [[Paper](https://arxiv.org/abs/2309.11495)], 2023.9

1. **Enhancing Zero-Shot Chain-of-Thought Reasoning in Large Language Models through Logic.** `COLING 2024`

    *Xufeng Zhao, Mengdi Li, Wenhao Lu, Cornelius Weber, Jae Hee Lee, Kun Chu, Stefan Wermter.* [[Paper](https://arxiv.org/abs/2309.13339)] [[Code](https://github.com/xf-zhao/LoT)], 2023.9

1. **Teaching Language Models to Self-Improve through Interactive Demonstrations.** `NAACL 2024`

    *Xiao Yu, Baolin Peng, Michel Galley, Jianfeng Gao, Zhou Yu.* [[Paper](https://arxiv.org/abs/2310.13522)], 2023.10

1. **Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning.** `EMNLP 2023 Findings`

    *Liangming Pan, Alon Albalak, Xinyi Wang, William Yang Wang.* [[Paper](https://arxiv.org/abs/2305.12295)] [[Code](https://github.com/teacherpeterpan/Logic-LLM)], 2023.10

1. **Boosting LLM Reasoning: Push the Limits of Few-shot Learning with Reinforced In-Context Pruning.** `Preprint`

    *Xijie Huang, Li Lyna Zhang, Kwang-Ting Cheng, Mao Yang.* [[Paper](https://arxiv.org/abs/2312.08901)], 2023.12

1. **Efficient Tool Use with Chain-of-Abstraction Reasoning.** `Preprint`

    *Silin Gao, Jane Dwivedi-Yu, Ping Yu, Xiaoqing Ellen Tan, Ramakanth Pasunuru, Olga Golovneva, Koustuv Sinha, Asli Celikyilmaz, Antoine Bosselut, Tianlu Wang.* [[Paper](https://arxiv.org/abs/2401.17464)], 2024.1

1. **K-Level Reasoning with Large Language Models.** `Preprint`

    *Yadong Zhang, Shaoguang Mao, Tao Ge, Xun Wang, Yan Xia, Man Lan, Furu Wei.* [[Paper](https://arxiv.org/abs/2402.01521)], 2024.2

1. **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models.** `Preprint`

    *Zhihong Shao, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Xiao Bi, Haowei Zhang, Mingchuan Zhang, Y.K. Li, Y. Wu, Daya Guo.* [[Paper](https://arxiv.org/abs/2402.03300)], 2024.2

1. **Self-Discover: Large Language Models Self-Compose Reasoning Structures.** `Preprint`

    *Pei Zhou, Jay Pujara, Xiang Ren, Xinyun Chen, Heng-Tze Cheng, Quoc V. Le, Ed H. Chi, Denny Zhou, Swaroop Mishra, Huaixiu Steven Zheng.* [[Paper](https://arxiv.org/abs/2402.03620)], 2024.2

1. **InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning.** `Preprint`

    *Huaiyuan Ying, Shuo Zhang, Linyang Li, Zhejian Zhou, Yunfan Shao, Zhaoye Fei, Yichuan Ma, Jiawei Hong, Kuikun Liu, Ziyi Wang, Yudong Wang, Zijian Wu, Shuaibin Li, Fengzhe Zhou, Hongwei Liu, Songyang Zhang, Wenwei Zhang, Hang Yan, Xipeng Qiu, Jiayu Wang, Kai Chen, Dahua Lin.* [[Paper](https://arxiv.org/abs/2402.06332)], 2024.2

1. **V-STaR: Training Verifiers for Self-Taught Reasoners.** `Preprint`

    *Arian Hosseini, Xingdi Yuan, Nikolay Malkin, Aaron Courville, Alessandro Sordoni, Rishabh Agarwal.* [[Paper](https://arxiv.org/abs/2402.06457)], 2024.2

1. **Chain-of-Thought Reasoning Without Prompting.** `Preprint`

    *Xuezhi Wang, Denny Zhou.* [[Paper](https://arxiv.org/abs/2402.10200)], 2024.2

1. **GLoRe: When, Where, and How to Improve LLM Reasoning via Global and Local Refinements.** `ICML 2024`

    *Alex Havrilla, Sharath Raparthy, Christoforus Nalmpantis, Jane Dwivedi-Yu, Maksym Zhuravinskyi, Eric Hambro, Roberta Railneau.* [[Paper](https://arxiv.org/abs/2402.10963)], 2024.2

1. **Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking.** `Preprint`

    *Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman.* [[Paper](https://arxiv.org/abs/2403.09629)], 2024.3

1. **LLM3: Large Language Model-based Task and Motion Planning with Motion Failure Reasoning.** `IROS 2024`
   
   *Shu Wang, Muzhi Han, Ziyuan Jiao, Zeyu Zhang, Ying Nian Wu, Song-Chun Zhu, Hangxin Liu.* [[Paper](https://arxiv.org/abs/2403.11552)][[Code](https://github.com/AssassinWS/LLM-TAMP)], 2024.3

1. **Advancing LLM Reasoning Generalists with Preference Trees.** `Preprint`

    *Lifan Yuan, Ganqu Cui, Hanbin Wang, Ning Ding, Xingyao Wang, Jia Deng, Boji Shan, Huimin Chen, Ruobing Xie, Yankai Lin, Zhenghao Liu, Bowen Zhou, Hao Peng, Zhiyuan Liu, Maosong Sun.* [[Paper](https://arxiv.org/abs/2404.02078)], 2024.4

1. **Evaluating Mathematical Reasoning Beyond Accuracy.** `Preprint`

    *Shijie Xia, Xuefeng Li, Yixin Liu, Tongshuang Wu, Pengfei Liu.* [[Paper](https://arxiv.org/abs/2404.05692)], 2024.4

1. **Self-playing Adversarial Language Game Enhances LLM Reasoning.** `Preprint`

    *Pengyu Cheng, Tianhao Hu, Han Xu, Zhisong Zhang, Yong Dai, Lei Han, Nan Du.* [[Paper](https://arxiv.org/abs/2404.10642)], 2024.4

1. **Toward Self-Improvement of LLMs via Imagination, Searching, and Criticizing.** `Preprint`

    *Ye Tian, Baolin Peng, Linfeng Song, Lifeng Jin, Dian Yu, Haitao Mi, Dong Yu.* [[Paper](https://arxiv.org/abs/2404.12253)], 2024.4

1. **Buffer of Thoughts: Thought-Augmented Reasoning with Large Language Models.** `Preprint`

    *Ling Yang, Zhaochen Yu, Tianjun Zhang, Shiyi Cao, Minkai Xu, Wentao Zhang, Joseph E. Gonzalez, Bin Cui.* [[Paper](https://arxiv.org/abs/2406.04271)] [[Code](https://github.com/YangLing0818/buffer-of-thought-llm)], 2024.6

1. **Q\*: Improving Multi-step Reasoning for LLMs with Deliberative Planning.** `Preprint`

   *Chaojie Wang, Yanchen Deng, Zhiyi Lv, Shuicheng Yan, An Bo.* [[Paper](https://arxiv.org/abs/2406.14283)], 2024.6

1. **LLM-ARC: Enhancing LLMs with an Automated Reasoning Critic.** `Preprint`

   *Aditya Kalyanpur, Kailash Saravanakumar, Victor Barres, Jennifer Chu-Carroll, David Melville, David Ferrucci.* [[Paper](https://arxiv.org/abs/2406.17663)], 2024.6

1. **DotaMath: Decomposition of Thought with Code Assistance and Self-correction for Mathematical Reasoning.** `Preprint`

    *Chengpeng Li, Guanting Dong, Mingfeng Xue, Ru Peng, Xiang Wang, Dayiheng Liu.* [[Paper](https://arxiv.org/abs/2407.04078)] [[Code](https://github.com/ChengpengLi1003/DotaMath)], 2024.7

1. **Agent Q: Advanced Reasoning and Learning for Autonomous AI Agents.** `Preprint`

    *Pranav Putta, Edmund Mills, Naman Garg, Sumeet Motwani, Chelsea Finn, Divyansh Garg, Rafael Rafailov.* [[Paper](https://arxiv.org/abs/2408.07199)], 2024.8

1. **OpenAI o1.** `Technical Report`

    *Open AI Team.* [[Blog](https://openai.com/index/learning-to-reason-with-llms/)], 2024.9

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



### <h3 id="lm">🤏 Scaling Smaller Language Models to Reason<h3/>



1. **Scaling Instruction-Finetuned Language Models.** `JMLR`

    *Hyung Won Chung, Le Hou, Shayne Longpre, Barret Zoph, Yi Tay, William Fedus, Eric Li, Xuezhi Wang, Mostafa Dehghani, Siddhartha Brahma, Albert Webson, Shixiang Shane Gu, Zhuyun Dai, Mirac Suzgun, Xinyun Chen, Aakanksha Chowdhery, Sharan Narang, Gaurav Mishra, Adams Yu, Vincent Zhao, Yanping Huang, Andrew Dai, Hongkun Yu, Slav Petrov, Ed H. Chi, Jeff Dean, Jacob Devlin, Adam Roberts, Denny Zhou, Quoc V. Le, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.11416)], 2022.10

1. **Distilling Multi-Step Reasoning Capabilities of Large Language Models into Smaller Models via Semantic Decompositions.** `ACL 2023 Findings`

    *Kumar Shridhar, Alessandro Stolfo, Mrinmaya Sachan.* [[Paper](https://arxiv.org/abs/2212.00193)], 2022.12

1. **Teaching Small Language Models to Reason.** `ACL 2023 Short`

    *Lucie Charlotte Magister, Jonathan Mallinson, Jakub Adamek, Eric Malmi, Aliaksei Severyn.* [[Paper](https://arxiv.org/abs/2212.08410)], 2022.12

1. **Large Language Models Are Reasoning Teachers.** `ACL 2023`

    *Namgyu Ho, Laura Schmid, Se-Young Yun.* [[Paper](https://arxiv.org/abs/2212.10071)] [[Code](https://github.com/itsnamgyu/reasoning-teacher)], 2022.12
    
1. **Specializing Smaller Language Models towards Multi-Step Reasoning.** `ICML 2023`

    *Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal, Tushar Khot.* [[Paper](https://arxiv.org/abs/2301.12726)], 2023.1

1. **Symbolic Chain-of-Thought Distillation: Small Models Can Also "Think" Step-by-Step.** `ACL 2023`

    *Liunian Harold Li, Jack Hessel, Youngjae Yu, Xiang Ren, Kai-Wei Chang, Yejin Choi.* [[Paper](https://arxiv.org/abs/2306.14050)] [[Code](https://github.com/allenai/cot_distillation)], 2023.6

1. **Learning Deductive Reasoning from Synthetic Corpus based on Formal Logic.** `ICML 2023`

    *Terufumi Morishita, Gaku Morio, Atsuki Yamaguchi, Yasuhiro Sogawa.* [[Paper](https://arxiv.org/abs/2308.07336)] [[Code](https://github.com/hitachi-nlp/FLD)], 2023.8

1. **MathScale: Scaling Instruction Tuning for Mathematical Reasoning.** `Preprint`

    *Zhengyang Tang, Xingxing Zhang, Benyou Wang, Furu Wei.* [[Paper](https://arxiv.org/abs/2403.02884)], 2024.3

<p align="right" style="font-size: 14px; color: #555; margin-top: 20px;">
    <a href="#readme-top" style="text-decoration: none; color: #007bff; font-weight: bold;">
        ↑ Back to Top ↑
    </a>
</p>



### <h3 id="mllm">🧠 Multimodal Reasoning in Large Language Models<h3/>



1. **Socratic Models: Composing Zero-Shot Multimodal Reasoning with Language.** `ICLR 2023`

    *Andy Zeng, Maria Attarian, Brian Ichter, Krzysztof Choromanski, Adrian Wong, Stefan Welker, Federico Tombari, Aveek Purohit, Michael Ryoo, Vikas Sindhwani, Johnny Lee, Vincent Vanhoucke, Pete Florence.* [[Project](https://socraticmodels.github.io/)] [[Paper](https://arxiv.org/abs/2204.00598)] [[Code](https://github.com/google-research/google-research/tree/master/socraticmodels)], 2022.4

1. **Visual Programming: Compositional visual reasoning without training.** `CPVR 2023`

    *Tanmay Gupta, Aniruddha Kembhavi.* [[Project](https://prior.allenai.org/projects/visprog)] [[Paper](https://arxiv.org/abs/2211.11559)] [[Code](https://github.com/allenai/visprog)], 2022.11

1. **Multimodal Chain-of-Thought Reasoning in Language Models.** `Preprint`

    *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, Alex Smola.* [[Paper](https://arxiv.org/abs/2302.00923)] [[Code](https://github.com/amazon-science/mm-cot)], 2023.2

1. **Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models.** `Preprint`

    *Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan.* [[Paper](https://arxiv.org/abs/2303.04671)] [[Code](https://github.com/microsoft/visual-chatgpt)], 2023.3

1. **ViperGPT: Visual Inference via Python Execution for Reasoning.** `ICCV 2023`

    *Dídac Surís, Sachit Menon, Carl Vondrick.* [[Project](https://viper.cs.columbia.edu/)] [[Paper](https://arxiv.org/abs/2303.08128)] [[Code](https://github.com/cvlab-columbia/viper)], 2023.3

1. **MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action.** `Preprint`

    *Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Ehsan Azarnasab, Faisal Ahmed, Zicheng Liu, Ce Liu, Michael Zeng, Lijuan Wang.* [[Project](https://multimodal-react.github.io/)] [[Paper](https://arxiv.org/abs/2303.11381)] [[Code](https://github.com/microsoft/MM-REACT)] [[Demo](https://huggingface.co/spaces/microsoft-cognitive-service/mm-react)], 2023.3

1. **Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models.** `NeurIPS 2023`

    *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao.* [[Project](https://chameleon-llm.github.io/)] [[Paper](https://arxiv.org/abs/2304.09842)] [[Code](https://github.com/lupantech/chameleon-llm)], 2023.4

1. **Link-Context Learning for Multimodal LLMs.** `CVPR 2024`

    *Yan Tai, Weichen Fan, Zhao Zhang, Feng Zhu, Rui Zhao, Ziwei Liu.* [[Paper](https://arxiv.org/abs/2308.07891)] [[Code](https://github.com/isekai-portal/Link-Context-Learning)], 2023.8

1. **G-LLaVA: Solving Geometric Problem with Multi-Modal Large Language Model.** `Preprint`

   *Jiahui Gao, Renjie Pi, Jipeng Zhang, Jiacheng Ye, Wanjun Zhong, Yufei Wang, Lanqing Hong, Jianhua Han, Hang Xu, Zhenguo Li, Lingpeng Kong.* [[Paper](https://arxiv.org/abs/2312.11370)], 2023.12

1. **Gemini in Reasoning: Unveiling Commonsense in Multimodal Large Language Models.** `Preprint`

   *Yuqing Wang, Yun Zhao.* [[Paper](https://arxiv.org/abs/2312.17661)], 2023.12

1. **Chain-of-Table: Evolving Tables in the Reasoning Chain for Table Understanding.** `ICLR 2024`

    *Zilong Wang, Hao Zhang, Chun-Liang Li, Julian Martin Eisenschlos, Vincent Perot, Zifeng Wang, Lesly Miculicich, Yasuhisa Fujii, Jingbo Shang, Chen-Yu Lee, Tomas Pfister.* [[Paper](https://arxiv.org/abs/2401.04398)], 2024.1

1. **SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities.** `CVPR 2024`

    *Boyuan Chen, Zhuo Xu, Sean Kirmani, Brian Ichter, Danny Driess, Pete Florence, Dorsa Sadigh, Leonidas Guibas, Fei Xia.* [[Project](https://spatial-vlm.github.io/)] [[Paper](https://arxiv.org/abs/2401.12168)], 2024.1

1. **Chart-based Reasoning: Transferring Capabilities from LLMs to VLMs.** `NAACL 2024 Findings`

    *Victor Carbune, Hassan Mansoor, Fangyu Liu, Rahul Aralikatte, Gilles Baechler, Jindong Chen, Abhanshu Sharma.* [[Paper](https://arxiv.org/abs/2403.12596)], 2024.3

1. **Visual Sketchpad: Sketching as a Visual Chain of Thought for Multimodal Language Models.** `Preprint`

    *Yushi Hu, Weijia Shi, Xingyu Fu, Dan Roth, Mari Ostendorf, Luke Zettlemoyer, Noah A Smith, Ranjay Krishna.* [[Project](https://visualsketchpad.github.io/)] [[Paper](https://arxiv.org/abs/2406.09403)] [[Code](https://github.com/Yushi-Hu/VisualSketchpad)], 2024.6

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
