# Live OCR Translation App

This **Live OCR Translation App** allows users to capture text from live video using **EasyOCR** and translates it into a selected target language in real-time. Built with **Streamlit**, **OpenCV**, **TextBlob**, and **Google Translate API**, this app provides a seamless experience for text recognition and translation using a webcam.

## Features

- **Live Text Recognition:** Capture text from the live video stream using OCR (Optical Character Recognition) via **EasyOCR**.
- **Real-time Translation:** Translates the recognized text into the selected target language using **Google Translate API**.
- **Multilingual Support:** Detects the language of the text and automatically translates it to the target language, supporting multiple languages.
- **Camera Control:** Toggle the camera on/off for capturing live text from the webcam feed.
- **Text Positioning:** The translated text is displayed on the live video feed, positioned appropriately over the recognized text.

## Requirements

To run this app, you need to install the following Python libraries:

- `streamlit`
- `opencv-python`
- `easyocr`
- `textblob`
- `googletrans`
- `numpy`

You can install these libraries using `pip`:

```bash
pip install streamlit opencv-python easyocr textblob googletrans numpy
How to Run
Clone this repository or download the necessary files.

Install the required libraries as mentioned above.

Run the following command to start the Streamlit app:

bash
Copy code
streamlit run app.py
Open the app in your web browser (usually at http://localhost:8501).

Usage
Select the Target Language: Use the dropdown menu to select the language in which you want the text to be translated.
Turn On the Camera: Click the "Camera On" button to start capturing the live video feed.
View Translations: The app will display the translated text over the recognized text in the live video feed. It will detect the language of the text and translate it accordingly.
Turn Off the Camera: Click the "Camera Off" button to stop the camera feed.
Supported Languages
The app supports a wide range of languages for translation, thanks to the googletrans API. The languages are listed in the dropdown menu for you to select.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
EasyOCR: An easy-to-use OCR tool that recognizes text from images and video streams.
TextBlob: A Python library for processing textual data, including language detection.
Googletrans: Python wrapper for Google Translate API to perform translations.
Streamlit: A powerful framework to build interactive web applications from Python scripts.
OpenCV: An open-source computer vision library for capturing video and processing images.
vbnet
Copy code

This `README.md` provides an overview of your project, how to set it up, and how users can interact with the application. You can adjust it according to your needs.





