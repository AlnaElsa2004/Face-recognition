# Face Recognition Project

This project showcases face recognition using both traditional and deep learning methods in **Google Colab** and **VS Code**. It covers three approaches:

1. **Face Recognition with LBPH and OpenCV**: Uses the LBPH algorithm for recognizing faces in images or video streams.
2. **Face Recognition with Dlib, CNN, and Distance Calculation**: Utilizes Dlib's CNN-based face recognition model with a distance-based classifier.
3. **Face Recognition using Webcam (VS Code)**: Implements face detection with OpenCV and Haarcascade, and performs real-time recognition using a webcam, displaying the name and confidence score of the recognized faces.

### In Google Colab:
 The notebook will demonstrate:
   - LBPH-based face recognition, using a trained model to predict and compare with expected output.
   - CNN-based face recognition using Dlib’s pre-trained model, along with distance calculation to determine recognition accuracy.
 Run the notebook to test these recognition methods on sample data.

### In VS Code (Webcam Recognition):
1. Open `camera_lbph.py` in VS Code.
2. Ensure the `haarcascade_frontalface_default.xml` file and the `lbph_classifier.yml` file are available in the folder.
3. Run the script to detect and recognize faces via your webcam.
   - The system will display the name of the recognized person and the confidence level (lower confidence values indicate better accuracy).

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
