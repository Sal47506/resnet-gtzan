# resnet-gtzan

**I had to archive the old repo because we ended up not using the Self-Supervised AST model**

This updated repo contains all the notebooks for the ResNet analysis of the GTZAN dataset: (https://drive.google.com/drive/folders/1i0jYEzEmdsl793zIFnP4-kR5LJclgR04?usp=sharing)

To run any of the models, simply run any of the (`.ipynb`) files in the original_notebook folder:

**Notebooks**:
1. baseline.ipynb: Baseline model
2. resnet18_original_no_changes.ipynb: ResNet-18 model with no changes made
3. resnet18_test6frozen.ipynb: ResNet-18 model with 6 layers frozen
4. resnet18_test6frozen8specaug.ipynb: ResNet-18 model with 8 layers frozen and Spec Augmentation preprocessing (best performing model)
5. resnet18_test8frozen.ipynb: ResNet-18 model with 8 frozen layers
6. resnet50_test10frozen.ipynb: ResNet-50 model with 10 frozen layers
7. resnet50_test8frozen.ipynb: ResNet-50 model with 8 frozen layers
8. resnet50_w_squeezeandexcitation (1).ipynb: ResNet-50 model with squeeze and excitation added to the model

**Run Notebooks**:
- Simply import the repo into Google Colab and run any of the files in the original_notebook folder.

**Contributions**
- Salamun Nuhin: Preprocessed and augmented all the data and establishing how the data was split, creating and experimenting the models including building the squeeze and excitation models, model training and most of the hyperparameter searches
- Yutong Xia: Helped with some of the fine tuning of the models, contributed to gathering the dataset and build a pipeline to easily download the dataset from Kaggle, and contributed to some of the research of the models.
   

