# Scene-Text-Recognition (STR) Project 
*Implement a Scene Text Recognition (STR) system designed to detect and recognize textual information from natural images.*  
This system follows a **two-stage approach** where a **text detection model** first localizes text regions in the image, and the cropped regions are then fed into a **CRNN model** to recognize the corresponding text sequences.

## Text Detection Results
**Text Detection Model (ICDAR2003 Training):** https://huggingface.co/huytqvn/text-detection-str-pipeline   
  
  
  <p align="center">
  <img src="images/results-text-detection.png" width="350"/>
  </p>

## Text Recognition Results

**Text Recognition Model (CRNN):** https://huggingface.co/huytqvn/text-recognition-pipeline

  <p align="center">
  <img src="images/results-text-recognition.png" width="350"/>
  </p>
