🥔 Potato Disease Detection App using CNN & Streamlit

This project is a deep learning-based web application designed to detect diseases in potato leaves using image classification. The system leverages a Convolutional Neural Network (CNN) model trained on labeled potato leaf images to accurately identify common diseases such as Early Blight and Late Blight, along with healthy leaves.

The application is deployed using Streamlit, providing a simple and interactive interface where users can upload an image of a potato leaf. Once the image is uploaded, it is preprocessed (resized, normalized, and formatted) before being passed to the trained CNN model for prediction.

The model outputs:

Predicted class (disease type or healthy)
Confidence level (%) indicating the certainty of the prediction

This tool can assist farmers, researchers, and agricultural experts in early disease detection, enabling timely intervention and reducing crop loss.

🔧 Key Features:
User-friendly web interface built with Streamlit
Image upload and real-time prediction
CNN-based deep learning model for accurate classification
Displays prediction with confidence score
Lightweight and easy to deploy
🛠️ Technologies Used:
Python
TensorFlow / Keras
Streamlit
NumPy, OpenCV (for image processing)
