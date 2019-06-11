BERT Fine-tuning on Quora Question Pairs
-

This repo contains google colab notebooks for finetuning BERT model on Quora Question Pairs dataset. We use colab TPU runtime for faster training. Medium post on this repo can be found [here](https://medium.com/@drcjudelhi/bert-fine-tuning-on-quora-question-pairs-b48277787285).

If you are not familiar with BERT, please visit [The Illustrated BERT](http://jalammar.github.io/illustrated-bert/), [BERT Research Paper](https://arxiv.org/abs/1810.04805) and [BERT Github Repo](https://github.com/google-research/bert).

For experimenting with latest notebook and more details visit colab notebook.
 <td>
    <a target="_blank" href="https://colab.research.google.com/drive/1dCbs4Th3hzJfWEe6KT-stIVDMqHZSA5V"><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>
  </td>


## Evaluation Results

Evaluation results are on BERT base uncased model. 
We have used train and dev set from [GLUE Quora Question Pairs Task](https://gluebenchmark.com/tasks).

|**Metrics** | **Train Set** | **Dev Set** |
|---|---|---|
|**Loss**|0.150|0.497|
|**Accuracy**|0.969|0.907|
|**F1**|0.959|0.875|
|**AUC**|0.969|0.902|
|**Precision**|0.949|0.864|
|**Recall**|0.969|0.886|

Due to limited resources, It was not possible to finetune on BERT Large model and do hyperparamter tuning.
