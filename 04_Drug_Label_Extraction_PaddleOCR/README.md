<h1 align="center">
Drug Label Text Extraction💊 <br>  Optical Character Recognition (OCR)🔎
</h1>

<h3 align="center">Automated Text Extraction and Visualization with PaddleOCR 🤖</h3>


<p align="center">
  <img src="https://github.com/Duygu-Jones/Deep-Learning-Projects/blob/main/04_Drug_Label_Extraction_PaddleOCR/drug4_output.png?raw=true"
</p>

## Project Insight 
Imagine you're at home, feeling tired after a long day, and you need to check the instructions on a medication bottle or food package. The text might be too small, the lighting could be poor, or you’re just too exhausted to focus properly. In such moments, trying to read these labels becomes frustrating and prone to mistakes.

This project aims to automate the extraction and clear visualization of text from drug labels using Optical Character Recognition (OCR) technology. Whether the writing is faint, the environment isn’t ideal, or you’re simply too tired, this tool provides quick access to important information, making daily tasks smoother and more stress-free. Automating this process helps healthcare professionals, patients, and individuals avoid errors and ensures crucial information is easy to read.


## What is OCR?
Optical Character Recognition (OCR) is a technology that converts printed or handwritten text in images into machine-readable text. This allows easy digitization, making information searchable and accessible in digital formats.

#### About PaddleOCR

PaddleOCR is an open-source OCR tool developed by PaddlePaddle, offering multi-language support, lightweight architecture, and fast processing capabilities. Compared to EasyOCR, PaddleOCR provides more flexibility in handling complex layouts and low-resolution images, making it more robust for tasks like drug label text extraction. While EasyOCR is known for its simplicity and ease of use, PaddleOCR excels in efficiency and accuracy, especially when working with large datasets or requiring real-time performance. Additionally, PaddleOCR's pre-trained models are optimized for multiple languages, giving it a broader scope for multilingual applications.


## Significance and Applications
Automating text extraction from drug labels speeds up the process and eliminates errors caused by difficult-to-read packaging. In healthcare, quick and accurate access to drug information can improve patient safety and care. For individuals, it simplifies reading labels in challenging situations, such as poor lighting or worn-out text. The tool can also assist in medication management, automated pharmacy inventory checks, and help those with visual impairments by making text easily accessible.


## Project Execution Steps
1. **Data Collection**: Drug label images were gathered from random sources on the internet.
2. **Model Setup**: PaddleOCR was configured to detect and extract text from the images.
3. **Automation Process**: The OCR model automatically scanned, detected, and extracted the text from each label, reducing manual effort.
3. **Text Detection and Recognition**: The model extracted text from the labels and stored it.
4. **Visualization**: The detected text was annotated on the images for a clear, visual representation.

<p align="center">
  <img src="https://github.com/Duygu-Jones/Deep-Learning-Projects/blob/main/04_Drug_Label_Extraction_PaddleOCR/drug5_output.png?raw=true"
</p>
   
## Conclusion

The project demonstrates how PaddleOCR can be effectively used to automate drug label text extraction. By simplifying access to essential information, this tool can positively impact healthcare and everyday life, improving safety and efficiency in reading labels.

### References:
- This project utilizes **[PaddleOCR GitHub Repository](https://github.com/PaddlePaddle/PaddleOCR)**, an open-source tool developed by PaddlePaddle for efficient text detection and recognition.
- The inspiration for this project came from a demonstration video by **[Nicholas Renotte](https://www.youtube.com/watch?v=t5xwQguk9XU)**.
- For further technical details, the methodology is based on the paper **[PP-OCR: A Practical Ultra Lightweight OCR System](https://arxiv.org/pdf/2009.09941v3)**.
  
---    

## ⬇️Installation

*To view the notebook online, visit my **Kaggle** profile.*
*If you find this work helpful, don't forget to give it an 👍 UPVOTE! and join the discussion!*

 - Kaggle Notebook: [Drug Label Text Extraction with PaddleOCR 🔎💊](https://www.kaggle.com/code/duygujones/drug-label-text-extraction-with-paddleocr)


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
