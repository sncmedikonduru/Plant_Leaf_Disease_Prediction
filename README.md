# Plant Leaf Disease Prediction

## PROBLEM STATEMENT
In the hunt of advancing agricultural technologies and ensuring food security, the ability to predict plant diseases through early intervention is a paramount. Our project utilizes a substantial dataset of approximately 80,000 classified plant leaf image data, consisting of both healthy and diseased specimens across various species. The primary goal is to benchmark the effectiveness of ViT against traditional CNN in disease identification. This comparative analysis uncovers a specific scenario where ViT excels (or) may require further optimization to enhance their utility in agricultural applications.

## Introduction
The agricultural sector frequently confronts the challenge of countless plant diseases, which can lead to significant economic losses globally. Early and accurate diagnosis of these afflictions is crucial in mitigating their impact. This necessitates the integration of advanced algorithms in plant pathology. Vision transformers (ViTs) and Convolutional Neural Networks (CNNs) are at the forefront of this technological advancement. These models offer new avenues for identifying disease patterns in plant leaves, promising to revolutionize agricultural practices by enhancing disease detection and management strategies.

## OBJECTIVE
This project is committed to leveraging the potential of Vision Transformers (ViT’s) and Convolutional Neural Networks (CNNs) to transform plant disease detection and classification. The primary objectives are centred around the capability of these models to detect and define unhealthy regions within plant leaves with unprecedented precision. By focusing on extracting and analysing texture features, the models can differentiate between healthy and diseased tissue, recognizing patterns that are often invisible to the naked eye. Ultimately, the goal is to create a scalable and efficient tool that can be deployed across different regions and plant varieties, making it a solution for plant disease management.

## BENEFITS

Adopting advanced technologies like Vision Transformers (ViTs) and Convolutional Neural Networks (CNNs) in plant disease detection brings many valuable advantages like improved accuracy and precision, resource optimization, and others. The reason is because, diagnosis(treatments) can be applied accurately, there’s less waste of water, pesticides, and other resources. This not only cuts the cost but also lessens the economic footprints of farming practices. 
By this, farmers can maintain steady income because they are able to meet market demand consistently. This stability is vital for the livelihoods of farmers and the overall economy of rural areas.
Overall, the use of Vision Transformers and CNNs in detecting plant diseases is about more than just identifying sick plants—it’s about making agriculture more efficient, sustainable, and economically stable.

## Data Source
The project encompasses a comprehensive approach to tackling plant leaf classification using cutting-edge techniques in computer vision. We have amassed an extensive dataset comprising 80,000 images, carefully classified into 10 healthy and 25 diseased categories from the Kaggle. This meticulous curation ensures a robust foundation for subsequent analysis and model development.

## Methodology
The approach includes:

- **Data Collection**: 
For this project, we collected approximately 80,000 Classified Plant Leaf Image data having both healthy and diseased classes which was collected from kaggle. Kaggle is a online platform which is available directly to the public to download various types of data.

- **Data Preprocessing**: 
Data pre-processing plays a pivotal role in refining the raw dataset, ensuring it's primed for effective model training. Techniques such as image normalization, resizing, and augmentation are likely employed to enhance model generalization and mitigate issues like overfitting. By meticulously preparing the data, we lay the groundwork for the subsequent stages of  project, setting the stage for robust model implementation.

- **Model Implementation**:
We implemented CNN architecture and Transformer architecture. In CNN, we implemented models include Resnet50, Desnet169 and Efficientnet B3. In transformer architecture, we implemeted vision transformers. We compared both the architectures and found a robust model. To Overcome the mitigation problem, we implemeted ensemble methods to acheive high performance.

- **Model Evaluation**: 
We evaluated a models on the bases of evaluation metrics like precision, recall, F1-score and Support. We generated a classification report.

## Results
Out of all other models, the efficient B3 in CNN architecture shows high performance and with the help of ensemble method we achieved 99% test accuracy. 

## Contributors
- [Sai Nath Chowdary Medikonduru](https://www.linkedin.com/in/sai-medikonduru)
- [TejaswiSaiKumar]

## Code Repository
The code is avaliable on GitHub: [Plant Leaf Disease Prediction](https://github.com/sncmedikonduru/Plant_Leaf_Disease_Prediction)

---

© 2024 Plant Leaf Disease Prediction Group Project
