<h1 align="center">
Flower Recognition Using CNN + Transfer Learning Models🌻
</h1>

<h3 align="center"> CNN | VGG16 - InceptionV3 - NasNetMobile - EfficientNetB3 - EfficientNetV2S - ConvNeXtTiny </h3>


<p align="center">
  <img src="https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-031-12413-6_59/MediaObjects/520480_1_En_59_Fig3_HTML.png"
</p>

## Project Overview  
**Flower Recognition Using CNN and Transfer Learning**
    
This project utilizes **Convolutional Neural Networks (CNN) and Transfer Learning** to classify images of flowers into five distinct categories accurately. The goal is to aid botanical research and educational applications by automating flower identification, leveraging a dataset composed of images collected from various online sources.

## Importance of Automated Flower Recognition

Automated recognition systems are essential in botany for the efficient cataloguing of species, monitoring biodiversity, and aiding in ecological conservation. These systems provide quick and accurate identification of various flower species, facilitating educational outreach and research.
    

## Project Execution Steps

1. **Image Preprocessing**: Adjusting images to a consistent scale and applying data augmentation techniques to improve model robustness.
2. **Normalization**: Standardizing pixel values across all images to facilitate model training.
3. **Model Development**: Employing CNN for feature extraction and Transfer Learning to leverage pre-trained networks, enhancing the ability to distinguish among the flower classes.
4. **Performance Evaluation**: Assessing accuracy and making iterative improvements to optimize the model for real-world application.


## Applications and Impact

- **Educational Tools**: Enhancing botanical education by providing tools that can identify and classify flowers accurately and swiftly.
- **Conservation Efforts**: Assisting in the documentation and monitoring of plant species for conservation projects.
- **Agricultural Planning**: Aiding in the identification of plant species for crop and garden management.

This project demonstrates the significant potential of CNN and Transfer Learning in the field of flower recognition, offering a valuable tool for educational, conservational, and agricultural applications. It highlights the synergy between technology and botany, promoting a deeper understanding and appreciation of plant diversity.

---

## About the Dataset

The **Flower Recognition Dataset** consists of 4242 images derived from online sources like Flickr, Google Images, and Yandex Images. It is designed to enhance the development of plant recognition models using photographs. This dataset is categorized into five classes: **Daisy**, **Tulip**, **Rose**, **Sunflower**, and **Dandelion**, with each class containing approximately 800 photos. The images maintain their original proportions, varying in size but typically around 320x240 pixels. They are not standardized to a single scale, adding to the complexity and realism of the task.

- **Source:** Images scraped from Flickr, Google Images, and Yandex Images
- **Classes:** Daisy, Tulip, Rose, Sunflower, Dandelion
- **Resolution:** Approx. 320x240 pixels
- **Total Images:** 4242
- **Variability:** Different proportions, not resized to a single scale
    
- > *This dataset is ideal for training and testing machine learning models aimed at recognizing diverse plant species, supporting both academic research and practical applications in botany.*
- > *Original dataset available on Kaggle:* [Flower Recognition](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition)
---

## Conclusion

In this project;

- A detailed exploratory analysis was conducted to identify the images in each class, determine their dimensions, decide whether scaling was needed, and examine the data distribution across classes.
- Preprocessing was performed using **ImageDataGenerator** before each model, ensuring it was tailored to the specific model’s requirements.
- Augmentation and rescaling were applied where needed, except for models that handled preprocessing internally. 
    (If preprocessing were applied within the model, the train-test split would need to be adjusted to work with TensorFlow.)
- For transfer learning models, base models were created by freezing the pre-trained layers. After training these base models, fine-tuning was done by unfreezing the pre-trained layers and using the best weights from the initial training phase. Each model’s performance was evaluated by making predictions on the test data.

*Since the dataset is small to medium-sized, the smallest versions of the transfer learning models were chosen to avoid overfitting. However, it was observed that even these smaller models were slightly large for the dataset.*


#### Model Selection Summary 🚀
When selecting a model based on the training and validation accuracy scores, the following key factors should be considered:

- **Generalization**: Validation accuracy (Val_Accuracy) is crucial as it indicates how well the model performs on unseen data. 🔍
- **Consistent Performance**: Ideally, the model should exhibit both high training and validation accuracy. A significant gap between these scores may suggest overfitting. ⚠️

#### Analysis of Models:
- **ConvNextTiny (109.42 MB)**: Excellent training accuracy (0.99) and the highest validation accuracy (0.95), demonstrating robust generalization with minimal overfitting. 🌟
- **InceptionV3 (92 MB)**: Strong training accuracy (0.99) and very good validation accuracy (0.93). Reliable and efficient. ⚡️
- **EfficientNetV2-S (88 MB)**: Good training accuracy (0.99) with validation accuracy (0.93), slightly lower compared to ConvNextTiny but still efficient. 🧠
- **EfficientNetB3 (48 MB)**: Very good training accuracy (0.98) and excellent validation accuracy (0.94), indicating strong generalization. 🔥
- **NasNetMobile (23 MB)**: Solid training accuracy (0.96) with good validation accuracy (0.92). A lightweight option for mobile applications. 💡
- **VGG16 (528 MB)**: Lower training accuracy (0.96) and good validation accuracy (0.91). The large model size makes it less favorable compared to others. 🔋
- **CNN**: Significantly lower training (0.85) and validation (0.81) accuracies, suggesting potential underfitting or need for further optimization. ⚠️

#### Recommended Model: ConvNextTiny (109.42 MB) 🎯
**Reason**: ConvNextTiny not only provides the highest validation accuracy (0.95) but also shows the smallest gap between training and validation scores, indicating robust generalization and minimal overfitting. It stands out as the best model for ensuring reliable performance in diverse conditions. 🏅

### Collaboration:

#### Rest of the Transfer Learning Models:
This study, in collaboration with **Fatma Nur Azman**, applies a CNN model along with 10 different transfer learning models to the Flowers Recognition dataset. Additional models explored include:
- EfficientNetB3
- Xception
- ResNet152V2
- DenseNet201
- MobileNetV2

For further details on these models and their implementation, please refer to the Kaggle notebook available at this link: [Flower | CNN + 10 Transfer Learning Models | Part-2](https://www.kaggle.com/code/fnurazman/flowers-cnn-10-transfer-learning-part-2).

Thank you to **Fatma Nur Azman** for your help and support throughout this project. I'm truly grateful.

*Thank you to everyone who took the time to engage with this work through comments, feedback, or simply showing support. Your interest means a lot and encourages us to keep learning and improving.*

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook: [Flowers Rec | CNN | 10 Transfer Learning |Part-1🌻](https://www.kaggle.com/code/duygujones/flowers-rec-cnn-10-transfer-learning-part-1)
 - The dataset is available to download on the Kaggle: [Flower Recognition](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition)

## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me

I'm Duygu Jones, a Data Scientist, passionate about data analysis, and machine learning.

♻️ You can find more about me and my work through the following links:

- **Linkedin**: [Linkedin/duygujones](https://www.linkedin.com/in/duygujones/)
- **Website**: [duygujones.com](https://duygujones.vercel.app/)
- **Kaggle**: [kaggle.com/duygujones](https://www.kaggle.com/duygujones)
- **GitHub**: [github.com/Duygu-Jones](https://github.com/Duygu-Jones)
- **Medium**: [medium.com/@duygujones](https://medium.com/@duygujones)

🌐Feel free to connect with me!

<br>

🎯 Enhance your machine learning skills,<br>
💡 Share your insights with the community,<br>
✨ If you find this repository helpful, don't forget to give it a ⭐ star.<br>

Code with joy! 👩‍💻✨

---

##### 📜 License

##### This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
