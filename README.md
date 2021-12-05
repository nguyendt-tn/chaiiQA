# chaii - Hindi and Tamil Question Answering
3rd Place Solution on kaggle competition chaii - Hindi and Tamil Question Answering competition

Write-up solution : https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/discussion/287929

## Dataset
- transformers-master: https://www.kaggle.com/abhishek/transformers-master
- train.csv: https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering/data
- mlqa_hindi.csv, xquad.csv: https://www.kaggle.com/rhtsingh/mlqa-hindi-processed

## Training
All our code trained on Kaggle notebook
- finetune-squad-tpus.ipynb: script to finetune Muril on SQuAD 2.0 with kaggle tpus, you can run it on kaggle: https://www.kaggle.com/nguyenduongthanh/fine-tune-muril-squad-v2
- train.ipynb: script to finetune model on Competition data, MLQA hindi, XQuaD hindi on kaggle gpus, you can run it on kaggle: https://www.kaggle.com/nguyenduongthanh/simple-train

## Inference
- 10-folds-inference: script to create inference for competition with model trained, you can run it on kaggle: https://www.kaggle.com/nguyenduongthanh/simple-10-folds-of-muril-large

## Trained model
- Muril Large Squad v2: https://www.kaggle.com/nguyenduongthanh/muril-large-squad-v2
- 10 Fold of Muril: https://www.kaggle.com/nguyenduongthanh/muril-10-fold