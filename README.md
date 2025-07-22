# Forest-Fire-Detection-

A simple Convolutional Neural Network (CNN) model built using TensorFlow/Keras to automatically detect wildfire in images. The model classifies input images into two categories — fire and no fire, helping in early wildfire detection from visual data. It is trained on a publicly available dataset and achieves good accuracy on test images.


# Step 1: Clone the repo
git clone https://github.com/yourusername/forest-fire-detection.git
cd forest-fire-detection

# Step 2: Install dependencies
pip install tensorflow matplotlib kagglehub

# Step 3: Download the dataset
# (Use the below code in your script or notebook)
import kagglehub
path = kagglehub.dataset_download("elmadafri/the-wildfire-dataset")

# Step 4: Train the model (run the script or notebook)

# Step 5: Predict using
predict_fire('path/to/image.jpg')

# Step 6: Save & Load model
model.save('FFD.keras')
model = load_model('FFD.keras')
