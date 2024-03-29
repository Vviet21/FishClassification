# FishClassification
![predict](https://github.com/Vviet21/FishClassification/assets/96041524/c7f0174c-758d-4981-a8aa-c2e799abe7b2)

### Dowload A Large Scale Fish Dataset in Kaggle

The dataset in Kaggle : https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset?resource=download

The dataset contains 9 different seafood types. For each class, there are 1000 augmented images and their pair-wise augmented ground truths.
Each class can be found in the "Fish_Dataset" file with their ground truth labels. All images for each class are ordered from "00000.png" to "01000.png".

![data](https://github.com/Vviet21/FishClassification/assets/96041524/81d10a2d-cb38-4448-8004-8014470ea927)

For example, if you want to access the ground truth images of the shrimp in the dataset, the order should be followed is "Fish->Shrimp->Shrimp GT".
### Loading the pretrained model and evaluation

Using pretraind model Resnet50 

Test Loss: 0.00346

Test Accuracy: 99.89%

![accuracy](https://github.com/Vviet21/FishClassification/assets/96041524/fddb7561-136c-427a-b23f-920892321074)
![loss](https://github.com/Vviet21/FishClassification/assets/96041524/b8ecad59-707d-4469-8f31-1c102f990ced)

<!---
--->

