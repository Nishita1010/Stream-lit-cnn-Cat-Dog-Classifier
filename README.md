# Stream-lit-cnn-Cat-Dog-Classifier

A simple deep learning web app built with **Streamlit** and **Convolutional Neural Networks (CNNs)** to classify images as either a **cat** or a **dog**. Upload an image, and the model will predict whether it's a feline or a canine!



## Features

- Upload an image and get an instant prediction (Cat/Dog)
- Clean and minimal web UI built with Streamlit
- Uses a pre-trained CNN model (custom trained or transfer learning)
- Real-time inference on uploaded images



## Project Structure



Stream-lit-cnn-Cat-Dog-Classifier/
│
├── model/
│   └── cat\_dog\_cnn\_model.h5         # Trained CNN model
│
├── app.py                           # Streamlit app entry point
├── helper.py                        # Helper functions (image preprocessing, prediction)
├── requirements.txt                 # Python dependencies
├── README.md                        # Project documentation

````

---

##  Model Details

- Built using **TensorFlow/Keras**
- CNN architecture with multiple Conv2D, MaxPooling, and Dense layers
- Trained on a labeled dataset of cat and dog images
- Accepts images resized to **(150x150)** or similar format

---

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/Stream-lit-cnn-Cat-Dog-Classifier.git
cd Stream-lit-cnn-Cat-Dog-Classifier
````

2. **Create and activate a virtual environment (optional but recommended)**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install the required packages**

```bash
pip install -r requirements.txt
```

---

## Running the App

```bash
streamlit run app.py
```

Once the server starts, open the provided URL in your browser (usually [http://localhost:8501](http://localhost:8501))

---

## Sample

Upload an image like this:

![Sample Image](https://example.com/sample.jpg)

Get a prediction:

```
🐶 It's a Dog!
```

---

## Dependencies

* streamlit
* tensorflow / keras
* pillow
* numpy

(Full list in `requirements.txt`)

---

## Author

Developed by [Nishita Namdeo](https://github.com/Nishita1010)

---

## ⭐️ Give it a Star!

If you like this project, consider giving it a ⭐ on GitHub!

```

---

Let me know if you want me to tailor this with **exact model architecture**, **dataset used**, or even create a **requirements.txt** file for you.
```
