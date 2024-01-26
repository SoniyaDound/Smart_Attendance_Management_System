# Smart_Attendance_Management_System

This project is a face recognition-based attendance system that uses OpenCV and Python. The system uses a camera to capture images of individuals and then compares them with the images in the database to mark attendance.

## Installation

1. Clone the repository to your local machine. ``` https://github.com/SoniyaDound/Smart_Attendance_Management_System.git```
2. Install the required packages using ```pip install -r requirements.txt```.
3. create and add data folder in repository data>>data_lib>>'dlib_face_recognition_resnet_model_v1.dat' and 'shape_predictor_68_face_landmarks.dat'

## Usage

1. Collect the Faces Dataset by running ``` python get_faces_from_camera_tkinter.py``` .
2. Convert the dataset into ```python features_extraction_to_csv.py```.
3. To take the attendance run ```python attendance_taker.py``` .
4. Check the Database by ```python app.py```.


## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have any suggestions.
