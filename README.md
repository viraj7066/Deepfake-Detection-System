Deepfake Detection System

Welcome to the Deepfake Detection System, a cutting-edge project designed to identify video deepfakes using advanced deep learning techniques. By combining ResNext for feature extraction and LSTM for sequence analysis, this project achieves high-accuracy detection of manipulated videos.

🚀 Features

Robust Deepfake Detection: Leverages a pretrained ResNext CNN and LSTM for accurate classification.
User-Friendly Web App: Built with Django, allowing users to upload videos and view results seamlessly.
Dockerized Deployment: Spin up the application effortlessly with Docker, no dependency hassles.
Detailed Documentation: Comprehensive guides to understand and replicate the project.


📂 Project Structure
Deepfake-Detection-System
├── Django Application    # Web interface for video uploads and predictions
├── Model Creation       # Scripts for building and training the model
├── Documentation        # In-depth project guides and resources


🛠️ System Architecture
The system extracts features from video frames using a pretrained ResNext model, which are then processed by an LSTM network to classify videos as real or fake.




⚙️ Installation
1. Clone the Repository
git clone https://github.com/viraj7066/Deepfake-Detection-System.git
cd Deepfake-Detection-System

2. Using Docker

Ensure Docker is installed.
Build and run the container:docker build -t deepfake-detection .
docker run -p 8000:8000 deepfake-detection


Access the app at http://localhost:8000.

3. Manual Setup

Follow the YouTube Installation Playlist for step-by-step setup instructions.


🖥️ Usage

Navigate to the Django Application directory.
Start the Django server:python manage.py runserver


Open your browser and visit http://localhost:8000.
Upload a video to detect if it’s a deepfake.


📚 Documentation

Project Documentation
Medium Article for an in-depth overview



🤝 Contribute
We welcome contributions to improve the project! Suggested enhancements include:

Deploying to free cloud platforms.
Creating an open-source API for detection.
Supporting batch processing of entire videos.
Optimizing code Wfor faster execution.

Completed Improvements:

✅ Dockerized the application.
✅ Enabled compatibility with non-CUDA systems (e.g., AMD GPUs, CPUs).

To contribute:

Fork the repository.
Create a feature branch.
Submit a pull request.


📜 License
This project is licensed under the GPLv3 License.

⭐ Support
If you find this project valuable, please give it a star on GitHub to show your support!
