# BERT Attention Visualizations – BertViz TutorialS

This repository contains interactive notebooks using **BertViz** to visualize attention patterns in Transformer models, primarily using **BERT**. It includes different views to understand how attention heads behave across layers and tokens.

## Notebooks

- [`bertvizualization.ipynb`](https://colab.research.google.com/github/harsh-codess/BERT-VIZ/blob/main/bertvizualization.ipynb)  
  **→ This is the main notebook using a MULTI HEAD ATTENTION model. Start here for interactive visualizations.**

- [`snapview.ipynb`](https://colab.research.google.com/github/harsh-codess/BERT-VIZ/blob/main/snapview.ipynb)  
  Shows attention flow layer-by-layer for encoder-decoder setups.

- [`bartlight.ipynb`](https://colab.research.google.com/github/harsh-codess/BERT-VIZ/blob/main/bartlight.ipynb)  
  Focuses on visualizing the full model attention in BART.

- [`focusmap.ipynb`](https://colab.research.google.com/github/harsh-codess/BERT-VIZ/blob/main/focusmap.ipynb)  
  Highlights attention patterns in DistilBERT across heads.

## How to Use

1. Click any link above to open the notebook in Google Colab.  
2. Make sure dependencies like `transformers`, `torch`, and `bertviz` are installed using the provided setup cells.  
3. Interactive visuals require a model and tokenizer to be properly loaded — follow each notebook’s instructions.

**🔁 Best viewed in Colab. Start with `bertvizualization.ipynb` to see attention in BERT models clearly.**

## Research Paper

For a deeper understanding of the tool and its underlying concepts, refer to the research paper:  
[**BertViz: A Tool for Visualizing Multi-Head Self-Attention in the BERT Model**](https://www.researchgate.net/publication/335701441_BertViz_A_Tool_for_Visualizing_Multi-Head_Self-Attention_in_the_BERT_Model)

This paper serves as the main reference for the development and understanding of BertViz.

## Author

[harsh-codess](https://github.com/harsh-codess)




