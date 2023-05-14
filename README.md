# Revit2Reality_Project
A project to transfer the wireframe style building into realistic style

## All the process is based on Cycle-GAN

### 1) 5.14
- Abstract
  - Collected the wireframe style buildings' data (Screenshot from the .rvt file) and architecture images in real life (part from https://www.kaggle.com/datasets/tompaulat/modern-architecture-100k-small-images) as the training dataset. By Using the sample code provided on Cycle-GAN Github, I get a after 200 times epoch (About 10 hours on RTX3080).

- 
![image]5_14/img/epoch001_real_A.png
- Things to improve
- 5.14
  - The generated images are still have a distance to the real life images, part because:
    - Quality of training dataset is not good enough (the outside appearance that I selected from modern-architecture-100k-small-images are not good)
    - Quantity of the data are not enough.

- Problems to solve
- 5.14
  - Seems that https://www.kaggle.com/datasets/wwymak/architecture-dataset is a greater dataset to select training data from.
  - 
