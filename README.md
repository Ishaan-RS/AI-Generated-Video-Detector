# AI-generated Video Detection

This project is designed to detect AI-generated videos using state-of-the-art deep learning models. It leverages transfer learning and recurrent neural networks (RNNs) to analyze visual and auditory data, providing a reliable solution for identifying AI-generated content. The goal is to ensure content authenticity and mitigate the spread of misinformation.

## Features
- **Video Analysis**: Detects tampered or AI-generated video frames using transfer learning + RNN based models.
- **Audio Analysis**: Identifies synthesized or altered audio patterns for enhanced accuracy.
- **Combined Detection**: Integrates video and audio analysis for comprehensive deepfake detection.
- **Customizable Models**: Easily adapt the architecture for specific datasets or applications.

## Technologies Used
- **Python**: Core programming language for implementation.
- **TensorFlow**: Frameworks for building and training deep learning models.
- **RNNs (LSTM)**: For capturing audio temporal dependencies.
- **FFmpeg**: For video and audio preprocessing.
- **MoviePy**: For video and audio preprocessing.
- **OpenCV**: For processing of video frames.
- **Resnet50**: For transfer learning.
- **Librosa**: For feature extraction of audio data.

## Usage
1. Prepare your dataset:
2. Train the model:
3. Test the model:
4. Analyze results:
   The output will include a report indicating whether the content is a deepfake.

## Project Structure
```
.
├── models              # Pre-trained and custom models
├── scripts             # Preprocessing and training scripts
├── Main.ipynb             # Script for testing the model
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```

## Future Scope
- Improve model performance with larger datasets.
- Add real-time detection capabilities.
- Explore additional features like lip-sync analysis for better accuracy.

