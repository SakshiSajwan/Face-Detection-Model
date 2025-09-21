This repository contains a Face Detection Model implemented in Python using OpenCV and Haar Cascade Classifiers. The project demonstrates how to detect faces and eyes in images with bounding boxes, and it can be extended for real-time video streams. It is designed as a beginner-friendly computer vision project.

✨ Features

Detects faces and eyes in static images.

Built with Haar Cascade Classifiers.

Includes step-by-step implementation in a Jupyter Notebook.

Beginner-friendly and easy to extend for real-time detection.

🛠️ Tech Stack

Python 3.x

OpenCV

Matplotlib / Jupyter Notebook

📂 Project Structure
Face-Detection-Model/
│── Face Detection Model.ipynb   # Jupyter Notebook with code and outputs
│── Data Set/                    # Folder with sample images
│── requirements.txt             # Python dependencies
│── README.md                    # Documentation

🚀 Installation

Clone the repository:

git clone https://github.com/SakshiSajwan/Face-Detection-Model.git
cd Face-Detection-Model


Create and activate a virtual environment (optional but recommended):

conda create -n face_detection python=3.9 -y
conda activate face_detection


Install dependencies:

pip install -r requirements.txt

▶️ Usage

Open the notebook in Jupyter:

jupyter notebook "Face Detection Model.ipynb"


Modify the image path in the notebook to test detection on your own images.

To extend it for webcam detection, replace the image input with a video capture loop using OpenCV.

📌 Applications

Face and eye detection in images.

Can be extended for real-time detection with webcams.

Useful for learning computer vision basics.

Foundation for projects like attendance systems, security monitoring, or AI-based apps.
