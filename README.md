# Forest-Fire-Detection

A simple Convolutional Neural Network (CNN) model built using TensorFlow/Keras to automatically detect wildfire in images. The model classifies input images into two categories — fire and no fire, helping in early wildfire detection from visual data. It is trained on a publicly available dataset and achieves good accuracy on test images.

---

## How to Run

### Step 1: Clone the repo
```bash
git clone https://github.com/yourusername/forest-fire-detection.git
cd forest-fire-detection
````

### Step 2: Install dependencies

```bash
pip install tensorflow matplotlib kagglehub
```

### Step 3: Download the dataset

Run this Python code in your script or notebook:

```python
import kagglehub
path = kagglehub.dataset_download("elmadafri/the-wildfire-dataset")
```

### Step 4: Train the model

Run your training script or notebook (e.g., `python train.py`)

### Step 5: Predict wildfire on an image

Run this Python function in your code:

```python
predict_fire('path/to/image.jpg')
```

### Step 6: Save & Load the model

In your Python code:

```python
model.save('FFD.keras')
from tensorflow.keras.models import load_model
model = load_model('FFD.keras')
```

```

