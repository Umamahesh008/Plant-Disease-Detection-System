# 🌱 Plant Disease Detection System 🌿
# 📌 Overview
This project is an AI-powered Plant Disease Detection System for Sustainable Agriculture. Using a deep learning model, the system identifies plant diseases from images and provides predictions to help farmers and agricultural experts take preventive measures.

# 🚀 Features
1. Image Upload: Users can upload plant images for disease detection.
2. Deep Learning Model: A trained TensorFlow/Keras model classifies plant diseases.
3. Streamlit Web App: Provides an intuitive UI for easy interaction.
4. Wide Range of Diseases: Identifies multiple plant diseases across different crops.
5. Instant Results: Provides quick predictions with a user-friendly interface.

# 🏗️ Tech Stack
Frontend: Streamlit
Backend: TensorFlow/Keras, NumPy
Model: Pretrained deep learning model for image classification.
# 🔧 Setup & Installation
# Clone the repository:
git clone https://github.com/Umamahesh008/Plant-Disease-Detection.git
cd Plant-Disease-Detection.
# Install dependencies:
pip install -r requirements.txt
# Run the application:
streamlit run main.py
Upload an image and get predictions!
# 📝 How It Works
1. The user uploads an image of a plant leaf.
2. The image is preprocessed and passed to the trained deep learning model.
3. The model predicts the disease and displays the result.
4. The UI highlights the detected disease with a success message.
# 📜 Labels Supported
The model recognizes various plant diseases, including:

Apple Scab, Black Rot, Cedar Apple Rust
Corn Leaf Spot, Rust, Blight
Grape Black Rot, Esca (Black Measles), Leaf Blight
Potato Early & Late Blight
Tomato Bacterial Spot, Early Blight, Leaf Mold, Mosaic Virus
... and many more!
