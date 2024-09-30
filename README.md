# AoANet_Notebook
An implementation of AoANet using a Jupyter Notebook. The original AoANet paper can be found at https://arxiv.org/pdf/1908.06954.pdf and the code can be found at https://github.com/husthuaan/AoANet. This was implemented as part of a university project for the course CSC413 at UofT.

# Special Thanks To
 - https://arxiv.org/pdf/1908.06954.pdf by Lun Huang, Wenmin Wang, Jie Chen, Xiao-Yong Wei for the original model.
 - https://github.com/husthuaan/AoANet for providing an implementation of the model that was used to bugfix.
 - https://github.com/ruotianluo/ImageCaptioning.pytorch for a very useful hub for Image Captioning ML models.
 - My group members https://github.com/raylfli and https://github.com/CarolusSolis.
 
 # Details
 The notebook implements AoANet in a Jupyter Notebook. Due to constraints in regards to copmutational resources, the model isn't fully tested. The model runs on Google Colab, but the full model doesn't run as there isn't enough compute (it takes 20 min/epoch using a smaller dataset and model).
 
 # Options
 - A dataset can be chosen (not fully tested) under the 'Loading Data'/'Choose Dataset' section.
 - The Feature Detection Resnet attention window can be changed under the 'Setup' section.
 - The model options can all be changed under 'Training the Model'/'Model Parameters/Options'.

**It is recommended to open the 'model.ipynb' file in Google Colab to improve the readability and formatting of the file.**
