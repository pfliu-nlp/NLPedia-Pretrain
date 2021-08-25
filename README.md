# Pre-train, Prompt, Predict



**************************** **Updates** ****************************

* 8/25: Add a new papers. ([\[67\]](https://arxiv.org/pdf/2102.02779.pdf))
* 8/15: Add three new papers. ([\[64\]](https://arxiv.org/pdf/2106.07704.pdf), [\[65\]](https://arxiv.org/pdf/1909.09031.pdf), [\[66\]](https://arxiv.org/pdf/2104.08826.pdf))
* 8/02: Add Several missing references. 
* 8/01: Fix one incorrect reference. (Thank Junyang Lin for pointing it out.)
* 7/28: We released [our paper](https://arxiv.org/pdf/2107.13586.pdf). Check it out!

#

[**Typology**](https://github.com/pfliu-nlp/NLPedia-Pretrain/blob/main/README.md#typology-of-prompting-methods) | 
[**Prompt Paper**](https://github.com/pfliu-nlp/NLPedia-Pretrain/tree/main/prompt_paper) |
[**Interactive Paperlist**](http://explainaboard.nlpedia.ai/leaderboard/prompting/) |
[**Pretrained LM Family**](https://github.com/pfliu-nlp/NLPedia-Pretrain/tree/main/pretrain) |
[**Survey and Website**](http://pretrain.nlpedia.ai/) |
[**Copyright**](https://github.com/pfliu-nlp/NLPedia-Pretrain/blob/main/README.md#copyright-and-acknowledgement)

> Feel free to let us know the missing papers (```issue``` or ```pull request```)

> We highly recommend using the [interactive paperlist]((http://explainaboard.nlpedia.ai/leaderboard/prompting/)) for prompt-based learning.
 
  <img src="./fig/bg.png" width="600" class="center">
 
 


 
## Typology of Prompting Methods





* ### Pre-trained Models ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/plm.pdf))
  * *Left-to-right Language Model*
  * *Masked Language Model* 
  * *Prefix Language Model*
  * *Encoder-Decoder*
* ### Prompt Engineering ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/template.pdf))
  * *Shape*
    * *Cloze prompt*: [\[7\]](https://aclanthology.org/D19-1250.pdf) [\[53\]](https://arxiv.org/pdf/2106.01760.pdf)
    * *Prefix prompt*: [\[17\]](https://arxiv.org/pdf/2005.14165.pdf) [\[26\]](https://arxiv.org/pdf/2012.11926.pdf)
  * *Human Effort*
    * *Hand-crated*
    * *Automated*
        - *Discrete*: [\[24\]](https://aclanthology.org/2020.emnlp-main.346.pdf) [\[27\]](https://arxiv.org/pdf/2012.15723.pdf)
        - *Continuous*: [\[29\]](https://arxiv.org/pdf/2101.00190.pdf) [\[59\]](https://arxiv.org/pdf/2106.13884.pdf)
* ### Answer Engineering ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/answer.pdf))
  * *Shape*
    * *Token*: [\[53\]](https://arxiv.org/pdf/2106.01760.pdf) [\[7\]](https://aclanthology.org/D19-1250.pdf)
    * *Span*: [\[19\]](https://aclanthology.org/2021.naacl-main.185.pdf) [\[22\]](https://aclanthology.org/2020.emnlp-main.479.pdf)
    * *Sentence*: [\[17\]](https://arxiv.org/pdf/2005.14165.pdf) [\[29\]](https://arxiv.org/pdf/2101.00190.pdf)
  * Human Effort
    * *Hand-crated*: [\[2\]](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf) [\[53\]](https://arxiv.org/pdf/2106.01760.pdf)
    * *Automated*
        - *Discrete*: [\[24\]](https://aclanthology.org/2020.emnlp-main.346.pdf) [\[13\]](https://aclanthology.org/2021.eacl-main.20.pdf)
        - *Continuous*: [\[28\]](https://arxiv.org/pdf/2101.00121.pdf) 
    
* ### Multi-Prompt Learning ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/multi-prompt.pdf))
  * *Prompt Ensemble*: [\[11\]](https://aclanthology.org/2020.tacl-1.28.pdf) [\[57\]](https://arxiv.org/pdf/2106.11520.pdf)
  * *Prompt Augmentation*: [\[48\]](https://arxiv.org/pdf/2104.08786.pdf) [\[47\]](https://arxiv.org/pdf/2104.08773.pdf)
  * *Prompt Composition*: [\[52\]](https://arxiv.org/pdf/2105.11259.pdf) 
  * *Prompt Decomposition*: [\[53\]](https://arxiv.org/pdf/2106.01760.pdf) 
    
* ### Prompt-based Training Strategies ([Detailed Description](http://pretrain.nlpedia.ai/data/pdf/learning.pdf))
  * Parameter Updating
    * *Promptless Fine-tuning*
    * *Tuning-free Prompting*: [\[17\]](https://arxiv.org/pdf/2005.14165.pdf) [\[7\]](https://aclanthology.org/D19-1250.pdf)
    * *Fixed-LM Prompt Tuning*: [\[29\]](https://arxiv.org/pdf/2101.00190.pdf) [\[28\]](https://arxiv.org/pdf/2101.00121.pdf)
    * *Fixed-prompt LM Tuning*: [\[26\]](https://arxiv.org/pdf/2012.11926.pdf) [\[13\]](https://aclanthology.org/2021.eacl-main.20.pdf)
    * *Prompt+LM Tuning*: [\[33\]](https://arxiv.org/pdf/2102.12206.pdf) [\[37\]](https://arxiv.org/pdf/2103.10385.pdf)
  * Training Sample Size
    * *Zero-shot*: [\[34\]](https://arxiv.org/pdf/2103.00453.pdf) [\[43\]](https://arxiv.org/pdf/2104.07540.pdf)
    * *Few-shot*: [\[19\]](https://aclanthology.org/2021.naacl-main.185.pdf) [\[27\]](https://arxiv.org/pdf/2012.15723.pdf)
    * *Full-data*: [\[21\]](https://arxiv.org/pdf/2010.03648.pdf) [\[29\]](https://arxiv.org/pdf/2101.00190.pdf)



## Copyright and Acknowledgement
* If you aim to use the picture from our github repo or survey, please state the source of these pictures.
* These pictures are drawn by Weizhe and co-designed by Pengfei.
