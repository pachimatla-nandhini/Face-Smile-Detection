This project demonstrates how to detect faces and smiles in videos using OpenCV Haar Cascade Classifiers inside a Streamlit web application.
It allows users to upload a video, see detection results in real time, and download the processed output.

**🚀 Key Features**

 Video Upload → Supports .mp4, .avi, .mov formats.

Face Detection → Detects human faces frame by frame.

Smile Detection → Identifies smiles within detected faces.

Live Preview → Displays processed video frames inside the Streamlit app.

Download Option → Save the processed video after completion.

⚡ Lightweight & Fast → Works in real-time depending on system performance.

**🛠️ Technologies Used**

Python 3.8+

**OpenCV**
 → For computer vision tasks.

**Streamlit**
 → For building the interactive web interface.

Haar Cascade Classifiers → Pre-trained models for face & smile detection.

**📂 Project Structure**
face-smile-detection/
│── app.py                  # Streamlit application (main code)
│── requirements.txt        # Python dependencies
│── README.md               # Documentation
│── output.mp4              # Processed video (generated after running app)



**Install dependencies:**

pip install -r requirements.txt


**Or manually:**

pip install opencv-python streamlit

**▶️ How to Run**

Run the Streamlit server:

streamlit run app.py


**Steps to use**:

Upload a video (.mp4, .avi, .mov).

The app will process the video and detect faces (blue boxes) and smiles (green boxes).

Watch results live on the browser.

Download the processed video using the Download button.

**📦 requirements.txt**
opencv-python
streamlit

**📸 Example Output**

Faces → Blue rectangle.

Smiles → Green rectangle with "Smiling" label.

(You can add screenshots or GIF here to make the repo attractive.)

**🎯 Learning Outcomes**

By building this project, you will learn:

How to use OpenCV Haar cascades for object detection.

How to process video streams frame by frame in Python.

How to build an interactive web app using Streamlit.

How to export/download processed results.
