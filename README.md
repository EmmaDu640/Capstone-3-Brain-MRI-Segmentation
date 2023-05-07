# Capstone-3-Brain-MRI-Segmentation
Semantic segmentation of brain MRI images is a crucial task in medical imaging, as it can help doctors diagnose various neurological disorders. In this project, different encoders for semantic segmentation of brain MRI images using the U-Net architecture were explored. The performance of different encoders was evaluated and compared to determine the most effective encoder for the task.

Data source: https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation
The follwoing models were experiemnted:
1. Generic Unet(no pretained encoders) 
2. VGG16 (retrain all layer)
3. ResNet50 (retrain all layer)
4. ResNet50 (freeze first two conv blocks)
And the test results are:

![Screen Shot 2023-05-06 at 6 54 26 PM](https://user-images.githubusercontent.com/110712413/236653705-69e65d07-6000-4f8f-9a92-ee5ee64aee10.png)
