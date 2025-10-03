# Crop_Disease_Prediction
The Crop Disease Prediction System allows users to upload plant leaf images for disease identification. It predicts the disease and highlights the affected areas in the image. Built with TensorFlow, OpenCV, and Streamlit, it provides accurate results for 38 plant diseases, helping farmers detect plant health issues quickly.
**How to Access the Crop Disease Prediction System**
Follow these steps to run the project on your machine:
**Prerequisites**
Python 3.8+ installed
Git installed
# 1. Clone the repository
git clone https://github.com/SupriyaDhara/crop-disease-Prediction.git

# 2. Navigate to the project folder
cd crop-disease-Prediction

# 3. (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate     # for Linux/Mac
venv\Scripts\activate        # for Windows

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the Streamlit app
streamlit run app.py

**Usage** **-**
Upload a crop leaf image through the interface.
The model will analyze the image.
You’ll get the predicted disease
