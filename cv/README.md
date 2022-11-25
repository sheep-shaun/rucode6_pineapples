# RuCode 6.0 CV
Task: Classification of car colour
## Download items from links and extract them to folder with notebooks:
* [Dataset](https://drive.google.com/file/d/1kWHWzBpxK_5z4H6w30fYponeBHRViu-k/view?usp=share_link)
* [Trained Models](https://drive.google.com/file/d/1U9cUMMZiPDvuUKrHXj_Q35IjrCyvrsDa/view?usp=share_link)


## To start a notebook with a solution, it is enough to write:
```bash
jupyter notebook
```
### TO CORRECTLY BE ABLE TO TRAIN AND PREDICT YOU SHOULD INSTALL NVIDIA'S CUDA AND PYTORCH WITH CUDA ENABLED!!!
Then start the Predict.ipynb notebook

## If some libraries are not installed, run
```bash
pip install -r requirements.txt
```

## Info about other notebooks
* Class Balance and Model Tuning 
  * Is made for balancing classes by adding augmentations and then tune the chosen model with Optuna
* Single Model Train and Other Ideas
  * Is made for training single models and testing ideas such as TTA, Augmentations, testing different Optimizers and Schedulers
* CrossValidation
  * Is made for training n models via Cross Validation proccess and then saving them to folder to have ability to use them later 
