#  Plantify – Plant Disease Detection using Deep Learning

**Plantify** is a machine learning project that detects diseases in plant leaves from images and suggests simple remedies. Built as a collaborative academic/group project by a team of 5 students.

We trained a **MobileNetV2** model (transfer learning) using **PyTorch** on Google Colab. The system classifies leaf images into healthy or diseased categories and maps predictions to disease names and recommends basic remedies.

## Project Highlights
- **Model**: MobileNetV2 (fine-tuned)
- **Framework**: PyTorch
- **Training Environment**: Google Colab
- **Dataset**: [New Plant Diseases Dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset) 
- **Classes**: Multi-class classification (healthy + various plant diseases)
- **Output**: Predicted disease name + confidence + suggested remedy
- **Team**: Collaborative effort by 5 contributors

## Results:
- The training accuracy is 95.40% due to the fine-tuning, and the validation accuracy is 97.05%
- The training loss and validation loss are 0.1368 and 0.0914, respectively.

  ![](https://github.com/Tanishtha-Reddy/Plantify-Disease-Detection-for-Crops/blob/main/resullts/resultspng.png)

- Here are a few outputs:

    ![](https://github.com/Tanishtha-Reddy/Plantify-Disease-Detection-for-Crops/blob/main/resullts/bacterial_leaf.PNG)
    ![](https://github.com/Tanishtha-Reddy/Plantify-Disease-Detection-for-Crops/blob/main/resullts/healthy_leaf.PNG)
    ![](https://github.com/Tanishtha-Reddy/Plantify-Disease-Detection-for-Crops/blob/main/resullts/blight_leaf.PNG)


  
  

