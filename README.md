# Reasoning using Language Models

[![Awesome](https://awesome.re/badge.svg)](https://github.com/atfortes/LM-Reasoning-Papers) 
![](https://img.shields.io/github/last-commit/atfortes/LM-Reasoning-Papers?color=green)
![](https://img.shields.io/badge/PRs-Welcome-red)
<!-- ![](https://img.shields.io/badge/paper%20number-45-brightgreen) -->
<!-- ![](https://visitor-badge.glitch.me/badge?page_id=atfortes/LM-Reasoning-Papers) -->

Collection of papers and resources on ***Reasoning using Language Models***.

> Author: [Armando Fortes](https://atfortes.github.io/) @THU

## Contents

- [Introduction](#-introduction)
- [Papers](#-papers)
  - [Survey](#survey)
  - [Analysis](#analysis)
  - [Technique](#technique)
- [Benchmarks](#-benchmarks)
- [Other Resources](#-other-resources)
- [Contributing](#-contributing)

## 👋 Introduction

Language models have recently revolutionized the landscape of Natural Language Processing, and scaling them up in size has been shown to confer several benefits, such as improved performance and sample efficiency. However, increasing model size alone has not proved sufficient for achieving high performance on challenging reasoning tasks, such as solving arithmetic problems or answering commonsense questions. This repository contains a collection of papers and resources which explore how the reasoning ability of language models can be unlocked.

## 📄 Papers

### Survey

1. **Reasoning with Language Model Prompting: A Survey.** `Preprint`

    *Shuofei Qiao, Yixin Ou, Ningyu Zhang, Xiang Chen, Yunzhi Yao, Shumin Deng, Chuanqi Tan, Fei Huang, Huajun Chen.* [[Paper](https://arxiv.org/abs/2212.09597)], 2022.12

2. **Towards Reasoning in Large Language Models: A Survey.** `Preprint`

    *Jie Huang, Kevin Chen-Chuan Chang.* [[Paper](https://arxiv.org/abs/2212.10403)], 2022.12

### Analysis

1. **Can language models learn from explanations in context?.** `EMNLP 2022`

    *Andrew K. Lampinen, Ishita Dasgupta, Stephanie C. Y. Chan, Kory Matthewson, Michael Henry Tessler, Antonia Creswell, James L. McClelland, Jane X. Wang, Felix Hill.* [[Paper](https://arxiv.org/abs/2204.02329)], 2022.4

2. **Emergent Abilities of Large Language Models.** `TMLR 2022`
   
    *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus.* [[Paper](https://arxiv.org/abs/2206.07682)] [[Blog](https://ai.googleblog.com/2022/11/characterizing-emergent-phenomena-in.html)], 2022.6

3. **Challenging BIG-Bench Tasks and Whether Chain-of-Thought Can Solve Them.** `Preprint`

    *Mirac Suzgun, Nathan Scales, Nathanael Schärli, Sebastian Gehrmann, Yi Tay, Hyung Won Chung, Aakanksha Chowdhery, Quoc V. Le, Ed H. Chi, Denny Zhou, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.09261)] [[Code](https://github.com/suzgunmirac/BIG-Bench-Hard)], 2022.10

4. **Towards Understanding Chain-of-Thought Prompting: An Empirical Study of What Matters.** `Preprint`
   
    *Boshi Wang, Sewon Min, Xiang Deng, Jiaming Shen, You Wu, Luke Zettlemoyer, Huan Sun.* [[Paper](https://arxiv.org/abs/2212.10001)] [[Code](https://github.com/sunlab-osu/Understanding-CoT)], 2022.12

5. **On Second Thought, Let's Not Think Step by Step! Bias and Toxicity in Zero-Shot Reasoning.** `Preprint`

    *Omar Shaikh, Hongxin Zhang, William Held, Michael Bernstein, Diyi Yang.* [[Paper](https://arxiv.org/abs/2212.08061)], 2022.12

6. **Dissociating language and thought in large language models: a cognitive perspective.** `Preprint`

    *Kyle Mahowald, Anna A. Ivanova, Idan A. Blank, Nancy Kanwisher, Joshua B. Tenenbaum, Evelina Fedorenko.* [[Paper](https://arxiv.org/abs/2301.06627)], 2023.1

7. **Large Language Models Can Be Easily Distracted by Irrelevant Context.** `Preprint`

    *Freda Shi, Xinyun Chen, Kanishka Misra, Nathan Scales, David Dohan, Ed Chi, Nathanael Schärli, Denny Zhou.* [[Paper](https://arxiv.org/abs/2302.00093)], 2023.1

### Technique

1. **Chain of Thought Prompting Elicits Reasoning in Large Language Models.** `NeurIPS 2022`

    *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou.* [[Paper](https://arxiv.org/abs/2201.11903)] [[Blog](https://ai.googleblog.com/2022/05/language-models-perform-reasoning-via.html)], 2022.1

2. **Self-consistency improves chain of thought reasoning in language models.** `Preprint`

    *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou.* [[Paper](https://arxiv.org/abs/2203.11171)], 2022.3

3. **Iteratively Prompt Pre-trained Language Models for Chain of Thought.** `EMNLP 2022`

    *Boshi Wang, Xiang Deng, Huan Sun.* [[Paper](https://arxiv.org/abs/2203.08383)] [[Code](https://github.com/sunlab-osu/iterprompt)]

4. **Least-to-most prompting enables complex reasoning in large language models.** `Preprint`

    *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le, Ed Chi.* [[Paper](https://arxiv.org/abs/2205.10625)], 2022.5

5. **Large Language Models are Zero-Shot Reasoners.** `NeurIPS 2022`
   
    *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa.* [[Paper](https://arxiv.org/abs/2205.11916)], 2022.5

6. **On the Advance of Making Language Models Better Reasoners.** `Preprint`
   
    *Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen.* [[Paper](https://arxiv.org/abs/2206.02336)], 2022.6

7. **Large Language Models Still Can't Plan.** `NeurIPS 2022`
   
    *Karthik Valmeekam, Alberto Olmo, Sarath Sreedharan, Subbarao Kambhampati.* [[Paper](https://arxiv.org/abs/2206.10498)] [[Code](https://github.com/karthikv792/gpt-plan-benchmark)], 2022.6

8. **Solving Quantitative Reasoning Problems with Language Models.** `NeurIPS 2022`

    *Aitor Lewkowycz, Anders Andreassen, David Dohan, Ethan Dyer, Henryk Michalewski, Vinay Ramasesh, Ambrose Slone, Cem Anil, Imanol Schlag, Theo Gutman-Solo, Yuhuai Wu, Behnam Neyshabur, Guy Gur-Ari, Vedant Misra.* [[Paper](https://arxiv.org/abs/2206.14858)] [[Blog](https://ai.googleblog.com/2022/06/minerva-solving-quantitative-reasoning.html)], 2022.6

9. **Rationale-Augmented Ensembles in Language Models.** `Preprint`

    *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Denny Zhou.* [[Paper](https://arxiv.org/abs/2207.00747)], 2022.7

10. **Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning.** `Preprint`

    *Pan Lu, Liang Qiu, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Tanmay Rajpurohit, Peter Clark, Ashwin Kalyan.* [[Project](https://promptpg.github.io/)] [[Paper](https://arxiv.org/abs/2209.14610)] [[Code](https://github.com/lupantech/PromptPG)], 2022.9

11. **Ask Me Anything: A simple strategy for prompting language models.** `Preprint`

    *Simran Arora, Avanika Narayan, Mayee F. Chen, Laurel Orr, Neel Guha, Kush Bhatia, Ines Chami, Frederic Sala, Christopher Ré.* [[Paper](https://arxiv.org/abs/2210.02441)] [[Code](https://github.com/hazyresearch/ama_prompting)], 2022.10

12. **Language Models are Multilingual Chain-of-Thought Reasoners.** `ICLR 2023`
   
    *Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.03057)], 2022.10

13. **Measuring and Narrowing the Compositionality Gap in Language Models.** `Preprint`

    *Ofir Press, Muru Zhang, Sewon Min, Ludwig Schmidt, Noah A. Smith, Mike Lewis.* [[Paper](https://arxiv.org/abs/2210.03350)], 2022.10

14. **Automatic Chain of Thought Prompting in Large Language Models.** `Preprint`
   
    *Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola.* [[Paper](https://arxiv.org/abs/2210.03493)], 2022.10

15. **ReAct: Synergizing Reasoning and Acting in Language Models.** `Preprint`
   
    *Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao.* [[Project](https://react-lm.github.io/)] [[Paper](https://arxiv.org/abs/2210.03629)] [[Code](https://github.com/ysymyth/ReAct)] [[Blog](https://ai.googleblog.com/2022/11/react-synergizing-reasoning-and-acting.html)], 2022.10

16. **Mind's Eye: Grounded language model reasoning through simulation.** `ICLR 2023`
   
    *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai.* [[Paper](https://arxiv.org/abs/2210.05359)], 2022.10

17. **Language Models of Code are Few-Shot Commonsense Learners.** `EMNLP 2022`
   
    *Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang, Graham Neubig.* [[Paper](https://arxiv.org/abs/2210.07128)] [[Code](https://github.com/madaan/cocogen)], 2022.10

18. **Challenging BIG-Bench tasks and whether chain-of-thought can solve them.** `Preprint`
   
    *Mirac Suzgun, Nathan Scales, Nathanael Schärli, Sebastian Gehrmann, Yi Tay, Hyung Won Chung, Aakanksha Chowdhery, Quoc V. Le, Ed H. Chi, Denny Zhou, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.09261)] [[Code](https://github.com/suzgunmirac/big-bench-hard)], 2022.10

19. **Scaling Instruction-Finetuned Language Models.** `Preprint`

    *Hyung Won Chung, Le Hou, Shayne Longpre, Barret Zoph, Yi Tay, William Fedus, Eric Li, Xuezhi Wang, Mostafa Dehghani, Siddhartha Brahma, Albert Webson, Shixiang Shane Gu, Zhuyun Dai, Mirac Suzgun, Xinyun Chen, Aakanksha Chowdhery, Sharan Narang, Gaurav Mishra, Adams Yu, Vincent Zhao, Yanping Huang, Andrew Dai, Hongkun Yu, Slav Petrov, Ed H. Chi, Jeff Dean, Jacob Devlin, Adam Roberts, Denny Zhou, Quoc V. Le, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.11416)], 2022.10

20. **Large Language Models Can Self-Improve.** `Preprint`
   
    *Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han.* [[Paper](https://arxiv.org/abs/2210.11610)], 2022.10

21. **Retrieval Augmentation for Commonsense Reasoning: A Unified Approach.** `EMNLP 2022`
   
    *Wenhao Yu, Chenguang Zhu, Zhihan Zhang, Shuohang Wang, Zhuosheng Zhang, Yuwei Fang, Meng Jiang.* [[Paper](https://arxiv.org/abs/2210.12887)] [[Code](https://github.com/wyu97/RACo)], 2022.10

22. **PAL: Program-aided Language Models.** `Preprint`
   
    *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig.* [[Project](https://reasonwithpal.com/)] [[Paper](https://arxiv.org/abs/2211.10435)] [[Code](https://github.com/reasoning-machines/pal)], 2022.11

23. **Unsupervised Explanation Generation via Correct Instantiations.** `AAAI 2023`

    *Sijie Cheng, Zhiyong Wu, Jiangjie Chen, Zhixing Li, Yang Liu, Lingpeng Kong.* [[Paper](https://arxiv.org/abs/2211.11160)], 2022.11

24. **Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks.** `Preprint`

    *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen.* [[Paper](https://arxiv.org/abs/2211.12588)] [[Code](https://github.com/wenhuchen/program-of-thoughts)], 2022.11

25. **Complementary Explanations for Effective In-Context Learning.** `Preprint`

    *Xi Ye, Srinivasan Iyer, Asli Celikyilmaz, Ves Stoyanov, Greg Durrett, Ramakanth Pasunuru.* [[Paper](https://arxiv.org/abs/2211.13892)], 2022.11

26. **Distilling Multi-Step Reasoning Capabilities of Large Language Models into Smaller Models via Semantic Decompositions.** `Preprint`

    *Kumar Shridhar, Alessandro Stolfo, Mrinmaya Sachan.* [[Paper](https://arxiv.org/abs/2212.00193)], 2022.12

27. **Teaching Small Language Models to Reason.** `Preprint`

    *Lucie Charlotte Magister, Jonathan Mallinson, Jakub Adamek, Eric Malmi, Aliaksei Severyn.* [[Paper](https://arxiv.org/abs/2212.08410)], 2022.12

28. **MURMUR: Modular Multi-Step Reasoning for Semi-Structured Data-to-Text Generation.** `Preprint`

    *Swarnadeep Saha, Xinyan Velocity Yu, Mohit Bansal, Ramakanth Pasunuru, Asli Celikyilmaz.* [[Paper](https://arxiv.org/abs/2212.08607)], 2022.12

29. **Can Retriever-Augmented Language Models Reason? The Blame Game Between the Retriever and the Language Model.** `Preprint`

    *Parishad BehnamGhader, Santiago Miret, Siva Reddy.* [[Paper](https://arxiv.org/abs/2212.09146)] [[Code](https://github.com/McGill-NLP/retriever-lm-reasoning)], 2022.12

30. **Large Language Models are reasoners with Self-Verification.** `Preprint`

    *Yixuan Weng, Minjun Zhu, Shizhu He, Kang Liu, Jun Zhao.* [[Paper](https://arxiv.org/abs/2212.09561)] [[Code](https://github.com/WENGSYX/Self-Verification)], 2022.12

31. **Language Models as Inductive Reasoners.** `Preprint`

    *Zonglin Yang, Li Dong, Xinya Du, Hao Cheng, Erik Cambria, Xiaodong Liu, Jianfeng Gao, Furu Wei.* [[Paper](https://arxiv.org/abs/2212.10923)], 2022.12

32. **LAMBADA: Backward Chaining for Automated Reasoning in Natural Language.** `Preprint`

    *Seyed Mehran Kazemi, Najoung Kim, Deepti Bhatia, Xin Xu, Deepak Ramachandran.* [[Paper](https://arxiv.org/abs/2212.13894)], 2022.12

33. **Rethinking with Retrieval: Faithful Large Language Model Inference.** `Preprint`

    *Hangfeng He, Hongming Zhang, Dan Roth.* [[Paper](https://arxiv.org/abs/2301.00303)], 2023.1

34. **Specializing Smaller Language Models towards Multi-Step Reasoning.** `Preprint`

    *Yao Fu, Hao Peng, Litu Ou, Ashish Sabharwal, Tushar Khot.* [[Paper](https://arxiv.org/abs/2301.12726)], 2023.1

35. **Synthetic Prompting: Generating Chain-of-Thought Demonstrations for Large Language Models.** `Preprint`

    *Zhihong Shao, Yeyun Gong, Yelong Shen, Minlie Huang, Nan Duan, Weizhu Chen.* [[Paper](https://arxiv.org/abs/2302.00618)], 2023.2

36. **Multimodal Chain-of-Thought Reasoning in Language Models.** `Preprint`

    *Zhuosheng Zhang, Aston Zhang, Mu Li, Hai Zhao, George Karypis, Alex Smola.* [[Paper](https://arxiv.org/abs/2302.00923)] [[Code](https://github.com/amazon-science/mm-cot)], 2023.2

## 🎯 Benchmarks

|     Reasoning Skills      | Benchmarks                                                   |
| :-----------------------: | ------------------------------------------------------------ |
| **Arithmetic Reasoning**  | [GSM8K](https://arxiv.org/abs/2110.14168), [SVAMP](https://aclanthology.org/2021.naacl-main.168), [ASDiv](https://aclanthology.org/2020.acl-main.92/), [AQuA](https://aclanthology.org/P17-1015/), [MAWPS](https://aclanthology.org/N16-1136/), [AddSub](https://aclanthology.org/D14-1058/), [MultiArith](https://aclanthology.org/D15-1202/), [SingleEq](https://aclanthology.org/Q15-1042/), [SingleOp]( https://doi.org/10.1162/tacl_a_00118), [Lila](https://arxiv.org/abs/2210.17517) |
| **Commonsense Reasoning** | [CommonsenseQA](https://arxiv.org/abs/1811.00937), [StrategyQA](https://arxiv.org/abs/2101.02235), [ARC](https://arxiv.org/abs/1803.05457), [BoolQ](https://arxiv.org/abs/1905.10044), [HotpotQA](https://arxiv.org/abs/1809.09600), [OpenBookQA](https://arxiv.org/abs/1809.02789), [PIQA](https://arxiv.org/abs/1911.11641) |
|  **Symbolic Reasoning**   | [Coin Flip](https://arxiv.org/abs/2201.11903), [Last Letter Concatenation](https://arxiv.org/abs/2201.11903) |
|  **Logical Reasoning**   | [ReClor](https://arxiv.org/abs/2002.04326), [LogiQA](https://arxiv.org/abs/2007.08124), [ProofWriter](https://arxiv.org/abs/2012.13048) |
| **Multimodal Reasoning**  | [SCIENCEQA](https://arxiv.org/abs/2209.09513) |
|        **Others**         | [BIG-bench](https://doi.org/10.48550/arXiv.2206.04615), [ALERT](https://arxiv.org/abs/2212.08286), [CONDAQA](https://arxiv.org/abs/2211.00295), [SCAN](https://arxiv.org/abs/1711.00350) |

## 🔧 Other Resources

- **[ThoughtSource](https://github.com/OpenBioLink/ThoughtSource)**: Central and open resource for data and tools related to chain-of-thought reasoning in large language models.
- **[Cascades](https://github.com/google-research/cascades)**: Python library which enables complex compositions of language models such as scratchpads, chain of thought, tool use, selection-inference, and more.
- **[LogiTorch](https://github.com/LogiTorch/logitorch)**: PyTorch-based library for logical reasoning on natural language.

## 👥 Contributing

- Add a new paper or update an existing paper, thinking about which category the work should belong to.
- Use the same format as existing entries to describe the work.
- Add the abstract link of the paper (`/abs/` format if it is an arXiv publication).

**Don't worry if you do something wrong, it will be fixed for you!**

### Contributors

<a href="https://github.com/atfortes/LM-Reasoning-Papers/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=atfortes/LM-Reasoning-Papers" />
</a>
