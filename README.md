# skull_stripping_project

The aim of the project is to prepare a skull stripping method on T1 magnetic resonance imaging (MRI) images of the head. The method should extract the entire area occupied by the brain proper from the patient's raw scan, excluding bones, other soft tissues, etc. 
<p align="center">
<img src="https://github.com/Skwarson96/skull_stripping_project/blob/main/img/skull_stripping.gif" />
</p>

I divided the project into three parts, each of them is contained in a separate one Google Colab:
- create_dataset -> from downloading data from the source to saving the finished dataset to training the neural network 
- train_model -> train model and save it
- model_predict -> generate predictions for test data (at the moment I do not have access to ground true of test data so I cannot define the percentage of network efficiency)

# Training
<p align="left">
  <img src="https://github.com/Skwarson96/skull_stripping_project/blob/main/img/model_loss.png" width="450" />
  <img src="https://github.com/Skwarson96/skull_stripping_project/blob/main/img/model_score.png" width="450" />
</p>

# Results
Test on data from a different source:
<p align="center">
<img src="https://github.com/Skwarson96/skull_stripping_project/blob/main/img/skull_stripping2.png" />
</p>
(:point_up: It's me :grinning:)

