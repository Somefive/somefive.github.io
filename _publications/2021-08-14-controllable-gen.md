---
title: "Controllable Generation from Pre-trained Language Models via Inverse Prompting"
collection: publications
permalink: /publication/2021-08-14-controllable-gen
excerpt: 'This paper is about using heuristic methods to improve the quality of generated texts via large language models.'
date: 2021-08-14
venue: 'The 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining'
paperurl: 'http://keg.cs.tsinghua.edu.cn/jietang/publications/KDD21-Zou-et-al-Controllable-Generation-from-Pre-trained-Language-Models-via-Inverse-Prompting.pdf'
citation: 'Zou, Xu & Yin, Da & Zhong, Qingyang & Yang, Hongxia & Yang, Zhilin & Tang, Jie. (2021). Controllable Generation from Pre-trained Language Models via Inverse Prompting. 2450-2460. 10.1145/3447548.3467418. '
---

Large-scale pre-trained language models have demonstrated strong capabilities of generating realistic text. However, it remains challenging to control the generation results. Previous approaches such as prompting are far from sufficient, which limits the usage of language models. To tackle this challenge, we propose an innovative method, inverse prompting, to better control text generation. The core idea of inverse prompting is to use generated text to inversely predict the prompt during beam search, which enhances the relevance between the prompt and the generated text and provides better controllability. Empirically, we pre-train a large-scale Chinese language model to perform a systematic study using human evaluation on the tasks of open-domain poem generation and open-domain long-form question answering. Our results show that our proposed method substantially outperforms the baselines and that our generation quality is close to human performance on some of the tasks.
Narrators can try our poem generation demo at [this https URL](https://pretrain.aminer.cn/apps/poetry.html), while our QA demo can be found at [this https URL](https://pretrain.aminer.cn/app/qa). For researchers, the code is provided in [this https URL](https://github.com/THUDM/InversePrompting).

[Download paper here](http://keg.cs.tsinghua.edu.cn/jietang/publications/KDD21-Zou-et-al-Controllable-Generation-from-Pre-trained-Language-Models-via-Inverse-Prompting.pdf)

Recommended citation: Zou, Xu & Yin, Da & Zhong, Qingyang & Yang, Hongxia & Yang, Zhilin & Tang, Jie. (2021). Controllable Generation from Pre-trained Language Models via Inverse Prompting. 2450-2460. 10.1145/3447548.3467418. 