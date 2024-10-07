<h1 align="center">
🖐️ Sign Language Detection with YOLOv11 🤟
</h1>

<h3 align="center"> 🟣Computer Vision Project with YOLOv11 Model🟣 </h3>

---

| 📽️ **YOLOv11 ASL Detection - Output Video Link**     | 
|------------------------------------------------------|
| [![Watch the video](https://github.com/Duygu-Jones/Deep-Learning-Projects/blob/main/03_Sign_Language_YOLO11/ASL_output_img.png?raw=true)](https://youtu.be/GfvfUCwjrSA?si=Pg0buaqQGxHnqyxC)  

## Project Overview

In this project, **Ultralytics YOLOv11** model has been to detect and classify American Sign Language (ASL) gestures in real-time. This model efficiently recognizes different hand gestures, providing a promising step towards building accessible communication tools for the deaf community.

## About YOLOv11
YOLOv11 builds upon the advancements made in previous versions (YOLOv9, YOLOv10), featuring improved architecture, better feature extraction, and optimized training techniques. The model can handle multiple tasks across different domains and is highly scalable, from mobile CPUs to powerful GPUs.

YOLOv11 is available in 5 different sizes, ranging from **2.6M to 56.9M parameters**, and achieves mAP scores between **39.5 and 54.7** on the **COCO dataset**, which was used for initial pre-training.

💡 For more details, check out the [Ultralytics YOLOv11 GitHub Repository](https://github.com/ultralytics/ultralytics).

For this project, the **small version** of YOLOv11 was used for **object detection** to efficiently detect hand signs in real-time.

## Dataset Information
The **American Sign Language (ASL) dataset** used in this project was sourced from [**Roboflow Universe/duyguj/american-sign-language-letters**](https://app.roboflow.com/duyguj/american-sign-language-letters-vouo0/1). All images were pre-labeled, ensuring accurate training data. Additionally, **data augmentation** techniques were applied within Roboflow to improve the model’s generalization by increasing the variability of the dataset.

This dataset contains a total of **1224 images**, which are split into three sets:
- **Train Set**: 1008 images (82%)
- **Validation Set**: 144 images (12%)
- **Test Set**: 72 images (6%)

### Preprocessing:
- **Auto-Orient**: Ensures proper image alignment.
- **Resize**: All images resized to **640x640 pixels**.

### Data Augmentation:
Each training example was augmented with transformations such as:
- **Rotation**: Between **-15° and +15°** to simulate various hand orientations.
- **Exposure**: Adjustments between **-10% and +10%** to account for different lighting conditions.
- **Blur**: Up to **2px** to simulate motion or camera blur.

This setup ensures that the model generalizes better by learning from varied input data.

## Training Process
The YOLOv11 model was **fine-tuned** on the ASL dataset to specialize in detecting hand signs. This process involved:
- **Dataset Augmentation**: Enhanced the dataset using transformations in Roboflow.
- **Model Training**: Trained the YOLOv11 model on the augmented dataset, with validation performed on a separate validation set.
- **Testing**: The model was evaluated on a **dedicated test set** to verify its ability to predict unseen data.

## Performance and Observations
The **final model** was tested on random **sign language images and videos**, demonstrating effective real-time detection of ASL gestures. The results were promising for detecting various hand signs and demonstrated the potential of the YOLOv11 architecture for handling complex, gesture-based tasks.

## Tools Used
- **YOLOv11 (Object Detection)**: Real-time sign detection.
- **OpenCV**: For image and video processing.
- **Python**: For model implementation and integration.

## Next Steps
- Improve detection accuracy for more complex signs.
- Expand the model to support additional sign languages and gestures.

## Useful Links
- [Ultralytics YOLOv11 GitHub Repository](https://github.com/ultralytics/ultralytics)  
- [**Roboflow Universe/duyguj/american-sign-language-letters**](https://app.roboflow.com/duyguj/american-sign-language-letters-vouo0/1)

---

### Thank you for checking out this project! 😊  
If you found this project interesting, feel free to check out the repository and the dataset links above.

If you'd like to contribute or discuss improvements, don't hesitate to connect!



## ⬇️Installation

*To view the notebook and training results, visit my **Kaggle** profile.*  
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook: [Sign Language Detection using YOLOv11 🤟](https://www.kaggle.com/code/duygujones/sign-language-detection-using-yolo11)
 
## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me

I'm Duygu Jones, a Data Scientist passionate about deep learning and AI applications.

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
