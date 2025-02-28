# Neural Machine Translation

Following along the paper - [Attention Is All You Need](https://arxiv.org/abs/1706.03762) (re-implementing it on original machine translation task )

gpt/gpt.py -  GPT-1 architecture 

## Repository Structure

```
nmt_transformer/
│── config/                     # Configuration files
│   ├── config.py               # Model and training hyperparameters
│
│── gpt/                        # GPT-based model implementation
│   ├── gpt.py                  
│
│── inference/                   # Notebooks for inference and testing
│   ├── Beam_Search.ipynb
│   ├── Colab_Train.ipynb
│   ├── Inference.ipynb
│
│── model/                       # Transformer and related architectures
│   ├── model.py
│
│── dataset.py                    # Dataset loading and preprocessing
│── attention_visual.ipynb         # Attention visualization notebook
│── requirements.txt               # Dependencies list
│── train.py                       # Training script
│── translate.py                   # Translation script
```

## Datasets

The following datasets can be used for training and evaluation:
- [WMT](https://huggingface.co/datasets/wmt14) - English-German, English-French, etc.
- [IWSLT](https://huggingface.co/datasets/iwslt2017) - Smaller dataset for speech translation.
- [OPUS](https://opus.nlpl.eu/) - Multilingual parallel dataset.
