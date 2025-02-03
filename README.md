# CNN Image Classification on FashionMNIST  

## Overview  
This project demonstrates the use of a **Convolutional Neural Network (CNN)** to classify images from the **FashionMNIST dataset**. The model was trained and evaluated to compare its performance with a ResNet model.

## Key Features  
- Built a **custom CNN architecture** for image classification.
- Compared the performance of CNN with **ResNet-based transfer learning**.
- Used **Batch Normalization, Dropout, and Data Augmentation** to improve model generalization.

## Dataset: FashionMNIST  
- **Source**: [FashionMNIST Dataset](https://github.com/zalandoresearch/fashion-mnist)  
- **Description**: 70,000 grayscale images of clothing items (28x28 pixels).  
- **Classes**: 10 categories, including T-shirts, trousers, pullovers, dresses, coats, sandals, shirts, sneakers, bags, and ankle boots.  

## Results  
- **CNN Model Accuracy**: 91.5%  
- **Comparison with ResNet**: The CNN model performed slightly lower than the ResNet model (94%), highlighting the advantages of transfer learning.

## How to Run  
1. Open `CNN_task_3_final_2.ipynb` in Jupyter Notebook or Google Colab.  
2. Run all the cells to train and evaluate the model.  
3. Compare the results with the ResNet-based model.

## Future Improvements  
- Test deeper CNN architectures like **VGG-16**.  
- Experiment with **hyperparameter tuning** to optimize performance.  
- Implement **ensemble learning** using both CNN and ResNet models.

## References  
- **FashionMNIST Dataset**: [GitHub Repository](https://github.com/zalandoresearch/fashion-mnist)  
- **CNN Paper**: [A Guide to Convolutional Neural Networks](https://arxiv.org/abs/1511.08458)  
