# Senior Citizen Identification System

A comprehensive solution to detect individuals in a video or real-time webcam feed, predict their age and gender, identify senior citizens (age > 60), and log visit details.

## 📁 Repository Contents

* **`Senior_Citizen_Working.ipynb`**: The Jupyter notebook containing the research, data exploration, model training, and evaluation workflow.
* **`app.py`**: A Streamlit web application providing a user-friendly interface for video and webcam-based face analysis.
* **`requirements.txt`**: All the required modules to run app.py and load models
* **`packages.txt`**: All the required packages for running app on streamlit-hub

## 🚀 Features

* **Age & Gender Estimation**: Uses custom-trained deep learning models to predict demographics from video frames.
* **Senior Citizen Detection**: Automatically flags individuals over 60 years old.
* **Video/Live Analysis**: Supports both pre-recorded video file uploads and real-time webcam snapshots via Streamlit.
* **Data Logging**: Built to facilitate the storage of age, gender, and visit timestamps.

## 🛠️ Setup & Installation

### 1. Prerequisites

Ensure you have Python 3.9+ installed. Clone this repository:

```bash
git clone https://github.com/KVAlwaysLearning/Senior_citizen_Identification_Sub
cd Senior_citizen_Identification_Sub

```

### 2. Install Dependencies

Install the required libraries:

```bash
pip install -r requirements.txt

```

### 3. Environment Configuration

The application requires pre-trained model weights. These are managed via a Google Drive folder. If running locally, you may need to set your Drive folder ID in your Streamlit secrets or environment variables.

## 💻 Usage

### Exploring the Research

You can open and run the research notebook (`Senior_Citizen_Working.ipynb`) in Jupyter or Google Colab to see the model training process and evaluation metrics.

### Running the App

Launch the web interface locally:

```bash
streamlit run app.py

```

Once the app is running, you can switch between **File Upload** mode to process videos or **Live Webcam** mode to perform real-time analysis using your computer's camera.

## 📂 Project Structure

```text
├── all_models/        # Directory for downloaded model weights (YOLO/TensorFlow/Custom Trained Model (Refer .ipynb file in the repo)
├── app.py             # Streamlit web application
├── Senior_Citizen_Working.ipynb # Research and data analysis notebook
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation

```

## 🔗 Links

* **Live App**: [Senior Citizen Identification App](https://seniorcitizenidentificationsub-app.streamlit.app/)
* **GitHub Repo**: [Senior Citizen Identification Repo](https://github.com/KVAlwaysLearning/Senior_citizen_Identification_Sub)

---


**Visuals:** 

<img width="1366" height="563" alt="App2" src="https://github.com/user-attachments/assets/dacd0ca0-cebb-4d2d-a429-5a80c749f4ab" />
<img width="1284" height="852" alt="App1" src="https://github.com/user-attachments/assets/586d3e19-b337-463d-9f0f-22a931435902" />
<img width="1366" height="499" alt="App3" src="https://github.com/user-attachments/assets/ba22a294-63ce-4329-b71e-c49790c389fb" />



