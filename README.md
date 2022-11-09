# LM-Reasoning-Papers

![](https://img.shields.io/github/last-commit/atfortes/LM-Reasoning-Papers?color=green)
![](https://img.shields.io/badge/paper%20number-28-brightgreen)
![](https://visitor-badge.glitch.me/badge?page_id=atfortes/LM-Reasoning-Papers)
![](https://img.shields.io/badge/PRs-Welcome-red)

## Contents

List of papers related to arithmetic, commonsense and symbolic reasoning using language models.

- [LM-Reasoning-Papers](#lm-reasoning-papers)
  - [Introduction](#introduction)
  - [Papers](#papers)
    - [Methods](#methods)
    - [Datasets](#datasets)
    - [Frameworks](#frameworks)
    - [Surveys](#surveys)
  - [Contributing](#contributing)

## Introduction

Language models have recently revolutionized the landscape of Natural Language Processing, and scaling them up in size has been shown to confer several benefits, such as improved performance and sample efficiency. However, increasing model size alone has not proved sufficient for achieving high performance on challenging reasoning tasks, such as solving arithmetic problems or answering commonsense questions. This repository contains a list of papers which explore how the reasoning ability of language models can be unlocked.

## Papers

### Methods

1. **Chain of Thought Prompting Elicits Reasoning in Large Language Models.** NeurIPS 2022.

    *Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou.* [[Paper](https://arxiv.org/abs/2201.11903)], 2022.1

2. **Self-consistency improves chain of thought reasoning in language models.** Preprint.

    *Xuezhi Wang, Jason Wei, Dale Schuurmans, Quoc Le, Ed Chi, Sharan Narang, Aakanksha Chowdhery, Denny Zhou.* [[Paper](https://arxiv.org/abs/2203.11171)], 2022.3

3. **Least-to-most prompting enables complex reasoning in large language models.** Preprint.

    *Denny Zhou, Nathanael Schärli, Le Hou, Jason Wei, Nathan Scales, Xuezhi Wang, Dale Schuurmans, Claire Cui, Olivier Bousquet, Quoc Le, Ed Chi.* [[Paper](https://arxiv.org/abs/2203.11171)], 2022.3

4. **Large Language Models are Zero-Shot Reasoners.** Preprint.
   
    *Takeshi Kojima, Shixiang Shane Gu, Machel Reid, Yutaka Matsuo, Yusuke Iwasawa.* [[Paper](https://arxiv.org/abs/2205.11916)], 2022.5

5. **On the Advance of Making Language Models Better Reasoners.** Preprint.
   
    *Yifei Li, Zeqi Lin, Shizhuo Zhang, Qiang Fu, Bei Chen, Jian-Guang Lou, Weizhu Chen.* [[Paper](https://arxiv.org/abs/2206.02336)], 2022.6

6. **Language models are multilingual chain-of-thought reasoners.** Preprint.
   
    *Freda Shi, Mirac Suzgun, Markus Freitag, Xuezhi Wang, Suraj Srivats, Soroush Vosoughi, Hyung Won Chung, Yi Tay, Sebastian Ruder, Denny Zhou, Dipanjan Das, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.03057)], 2022.10

7. **Automatic Chain of Thought Prompting in Large Language Models.** Preprint.
   
    *Zhuosheng Zhang, Aston Zhang, Mu Li, Alex Smola.* [[Paper](https://arxiv.org/abs/2210.03493)], 2022.10

8. **ReAct: Synergizing Reasoning and Acting in Language Models.** Preprint.
   
    *Shunyu Yao, Jeffrey Zhao, Dian Yu, Nan Du, Izhak Shafran, Karthik Narasimhan, Yuan Cao.* [[Paper](https://arxiv.org/abs/2210.03629)], 2022.10

9. **Mind's Eye: Grounded language model reasoning through simulation.** Preprint.
   
    *Ruibo Liu, Jason Wei, Shixiang Shane Gu, Te-Yen Wu, Soroush Vosoughi, Claire Cui, Denny Zhou, Andrew M. Dai.* [[Paper](https://arxiv.org/abs/2210.05359)], 2022.10

10. **Language Models of Code are Few-Shot Commonsense Learners.** Preprint.
   
    *Aman Madaan, Shuyan Zhou, Uri Alon, Yiming Yang, Graham Neubig.* [[Paper](https://arxiv.org/abs/2210.07128)] [[Code](https://github.com/madaan/cocogen)], 2022.10

11. **Challenging BIG-Bench tasks and whether chain-of-thought can solve them.** Preprint.
   
    *Mirac Suzgun, Nathan Scales, Nathanael Schärli, Sebastian Gehrmann, Yi Tay, Hyung Won Chung, Aakanksha Chowdhery, Quoc V. Le, Ed H. Chi, Denny Zhou, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.09261)], 2022.10

12. **Scaling instruction-finetuned language models.** Preprint.

    *Hyung Won Chung, Le Hou, Shayne Longpre, Barret Zoph, Yi Tay, William Fedus, Eric Li, Xuezhi Wang, Mostafa Dehghani, Siddhartha Brahma, Albert Webson, Shixiang Shane Gu, Zhuyun Dai, Mirac Suzgun, Xinyun Chen, Aakanksha Chowdhery, Sharan Narang, Gaurav Mishra, Adams Yu, Vincent Zhao, Yanping Huang, Andrew Dai, Hongkun Yu, Slav Petrov, Ed H. Chi, Jeff Dean, Jacob Devlin, Adam Roberts, Denny Zhou, Quoc V. Le, Jason Wei.* [[Paper](https://arxiv.org/abs/2210.11416)], 2022.10

13. **Large Language Models Can Self-Improve.** Preprint.
   
    *Jiaxin Huang, Shixiang Shane Gu, Le Hou, Yuexin Wu, Xuezhi Wang, Hongkun Yu, Jiawei Han.* [[Paper](https://arxiv.org/abs/2210.11610)], 2022.10

### Datasets

1. **Learning to Solve Arithmetic Word Problems with Verb Categorization.** EMNLP 2014.
   
    *Mohammad Javad Hosseini, Hannaneh Hajishirzi, Oren Etzioni, Nate Kushman.* [[Paper](https://aclanthology.org/D14-1058/)], 2014.10

2. **Solving General Arithmetic Word Problems.** EMNLP 2015.
   
    *Subhro Roy, Dan Roth.* [[Paper](https://arxiv.org/abs/1608.01413)], 2015.9

3. **MAWPS: A Math Word Problem Repository.** NAACL 2016.
   
    *Rik Koncel-Kedziorski, Subhro Roy, Aida Amini, Nate Kushman, Hannaneh Hajishirzi.* [[Paper](https://aclanthology.org/N16-1136/)] [[Code](https://github.com/sroy9/mawps)], 2016.6

4. **Program Induction by Rationale Generation: Learning to Solve and Explain Algebraic Word Problems.** Preprint.
   
    *Wang Ling, Dani Yogatama, Chris Dyer, Phil Blunsom.* [[Paper](https://arxiv.org/abs/1705.04146)] [[Code](https://github.com/deepmind/AQuA)], 2017.5

5. **Think you have Solved Question Answering? Try ARC, the AI2 Reasoning Challenge.** Preprint.
   
    *Peter Clark, Isaac Cowhey, Oren Etzioni, Tushar Khot, Ashish Sabharwal, Carissa Schoenick, Oyvind Tafjord.* [[Paper](https://arxiv.org/abs/1803.05457)], 2018.3

6. **CommonsenseQA: A Question Answering Challenge Targeting Commonsense Knowledge.** NAACL 2019.
   
    *Alon Talmor, Jonathan Herzig, Nicholas Lourie, Jonathan Berant.* [[Paper](https://arxiv.org/abs/1811.00937)] [[Code](https://github.com/jonathanherzig/commonsenseqa)], 2018.11

7. **A Diverse Corpus for Evaluating and Developing English Math Word Problem Solvers.** ACL 2020.
   
    *Shen-Yun Miao, Chao-Chun Liang, Keh-Yih Su.* [[Paper](https://arxiv.org/abs/2106.15772)] [[Code](https://github.com/chaochun/nlu-asdiv-dataset)], 2020.7

8. **Did Aristotle Use a Laptop? A Question Answering Benchmark with Implicit Reasoning Strategies.** TACL 2021.
   
    *Mor Geva, Daniel Khashabi, Elad Segal, Tushar Khot, Dan Roth, Jonathan Berant.* [[Paper](https://arxiv.org/abs/2101.02235)] [[Code](https://github.com/eladsegal/strategyqa)], 2021.1

9. **Are NLP Models really able to Solve Simple Math Word Problems?** NAACL 2021.
   
    *Arkil Patel, Satwik Bhattamishra, Navin Goyal.* [[Paper](https://arxiv.org/abs/2103.07191)] [[Code](https://github.com/arkilpatel/SVAMP)], 2021.3

10. **Training Verifiers to Solve Math Word Problems.** Preprint.
   
    *Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman.* [[Paper](https://arxiv.org/abs/2110.14168)] [[Code](https://github.com/openai/grade-school-math)], 2021.10

11. **Lila: A Unified Benchmark for Mathematical Reasoning.** EMNLP 2022.

    *Swaroop Mishra, Matthew Finlayson, Pan Lu, Leonard Tang, Sean Welleck, Chitta Baral, Tanmay Rajpurohit, Oyvind Tafjord, Ashish Sabharwal, Peter Clark, Ashwin Kalyan.* [[Paper](https://arxiv.org/abs/2210.17517)] [[Code](https://github.com/allenai/lila)], 2022.10

12. **CONDAQA: A Contrastive Reading Comprehension Dataset for Reasoning about Negation.** EMNLP 2022.
  
    *Abhilasha Ravichander, Matt Gardner, Ana Marasović.* [[Paper](https://arxiv.org/abs/2211.00295)] [[Code](https://github.com/abhilasharavichander/condaqa)], 2022.11

### Frameworks

1. **Large Language Models Still Can't Plan.** Preprint.
   
    *Karthik Valmeekam, Alberto Olmo, Sarath Sreedharan, Subbarao Kambhampati.* [[Paper](https://arxiv.org/abs/2206.10498)], 2022.6

2. **Retrieval Augmentation for Commonsense Reasoning: A Unified Approach.** EMNLP 2022.
   
    *Wenhao Yu, Chenguang Zhu, Zhihan Zhang, Shuohang Wang, Zhuosheng Zhang, Yuwei Fang, Meng Jiang.* [[Paper](https://arxiv.org/abs/2210.12887)] [[Code](https://github.com/wyu97/RACo)], 2022.10

### Surveys

1. **Emergent Abilities of Large Language Models.** TMLR 2022.
   
    *Jason Wei, Yi Tay, Rishi Bommasani, Colin Raffel, Barret Zoph, Sebastian Borgeaud, Dani Yogatama, Maarten Bosma, Denny Zhou, Donald Metzler, Ed H. Chi, Tatsunori Hashimoto, Oriol Vinyals, Percy Liang, Jeff Dean, William Fedus.* [[Paper](https://arxiv.org/abs/2206.07682)], 2022.6

## Contributing

- Think about which category the work should belong to.
- Use the same format as the others to discribe the work. Note that there should be an empty line between the title and the authors list, and take care of the indentation.
- Add the pdf link of the paper (if it is an arXiv publication, we prefer `/abs/` format to `/pdf/` format).

**Don't worry if you do all of these wrong, they will be fixed for you.**
