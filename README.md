# ViT_basics
Explores vision transformer basics, including using pretrained models, finetuning, etc.

## notebooks
1. vit_load_n_eval_google_model.ipynb -- loads google's pretrained vision transformer model (from link #2 below) and evaluates performance on microsoft/kaggle's cats and dogs dataset, and also on a set of family & friend cat and dog photos
2. vit_finetuning_on_my_dataset.ipynb -- finetunes google's pretrained vision transformer model (from link #3 below)
3. vit_load_n_eval_finetuned_model.ipynb -- loads finetuned model (from notebook #2) and evaluates performance on microsoft/kaggle's cats and dogs dataset, and also on a set of family & friend cat and dog photos


## misc. links
1. [Original ViT paper](https://arxiv.org/pdf/2010.11929.pdf)
2. [Huggingface's pretrained and finetuned Google ViT Model](https://huggingface.co/google/vit-base-patch16-224)
3. [Huggingface's pretrained Google ViT Model](https://huggingface.co/google/vit-base-patch16-224-in21k)
