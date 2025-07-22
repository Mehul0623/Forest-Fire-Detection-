# Forest-Fire-Detection

A simple Convolutional Neural Network (CNN) model built using TensorFlow/Keras to automatically detect wildfire in images. The model classifies input images into two categories — fire and no fire, helping in early wildfire detection from visual data. It is trained on a publicly available dataset and achieves good accuracy on test images.

## Step 1: Clone the repo
```bash
git clone https://github.com/yourusername/forest-fire-detection.git
cd forest-fire-detection
````

## Step 2: Install dependencies

```bash
pip install tensorflow matplotlib kagglehub
```

## Step 3: Download the dataset

Use this code inside your script or notebook:

```python
import kagglehub
path = kagglehub.dataset_download("elmadafri/the-wildfire-dataset")
```

## Step 4: Train the model

Run the training script or notebook.

## Step 5: Predict on new images

Use the function:

```python
predict_fire('path/to/image.jpg')
```

## Step 6: Save and load the model (optional but recommended)

Save the trained model to reuse later without retraining:

```python
model.save('FFD.keras')
```

Load the saved model anytime to make predictions without retraining:

```python
from tensorflow.keras.models import load_model
model = load_model('FFD.keras')
```

**Note:**
Step 6 is optional if you only want to train and predict in a single session. However, saving and loading the model is recommended for efficiency and reusability.

