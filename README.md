# teachble_machine
# Image Classification Project using Teachable Machine and Python

This project is a practical application of training a Machine Learning model to recognize and classify images using Google's **Teachable Machine**, then exporting and running it locally via **Python** within the **Anaconda** environment.
## 🧠 Model Training Process (Teachable Machine)

Before testing the model locally, it was trained using Google's Teachable Machine by following these steps:

1. Opened **Teachable Machine** and created a new **Image Project**.
2. Created the required classes (e.g., 'Appels') and uploaded a dataset of images for each category.
3. Clicked **Train Model** to allow the system to learn the patterns and features from the provided dataset.
4. Exported the trained model by selecting **Export Model** -> **TensorFlow** -> **Keras** format.
5. Downloaded the generated `keras_model.h5` and `labels.txt` files to integrate them locally with the Python script.
<img width="1588" height="913" alt="image" src="C:\Users\cloab\OneDrive\Desktop\test resultes.png" />
---

## 📁 Repository Structure
* `main.py`: The Python script that loads the model, processes the input image, and predicts its class.
* `keras_Model.h5`: The trained model exported in TensorFlow/Keras format.
* `labels.txt`: A text file containing the names of the classes the model was trained on.
* **Screenshot:** An image showing the successful execution of the code and the terminal output.

## 🛠 Prerequisites
To run the code successfully, make sure to install the following libraries inside your Conda environment:

```bash
pip install tensorflow pillow numpy
```

## 🚀 How to Run
1. Download all the files in this repository and place them in a single folder on your local machine.

2. Open the **Anaconda Prompt**.

3. Activate the project's environment using the following command:
```bash
conda activate TeachableMachine
```

4. Navigate to the folder containing the files using the `cd` command (example):
```bash
cd C:\Users\wasee\Downloads\converted_keras
```

5. Run the Python script to test the model:
```bash
python main.py
```

## 📊 Results
When testing the model on the input image, it successfully recognized and classified it with very high confidence:
<img width="1036" height="255" alt="image" src="C:\Users\cloab\OneDrive\Desktop\image(2).jpg"/>


* **Predicted Class:** Lion (Lion)
* **Confidence Score:** 0.998 (equivalent to 99.8%)
