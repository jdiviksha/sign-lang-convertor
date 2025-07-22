
# Streamlit-Based Real-Time Speech to ISL Translator

This application uses:

- 🎤 **SpeechRecognition** to capture real-time speech
- 🧠 **Streamlit** for web UI
- 📹 **OpenCV** to play gesture videos corresponding to spoken words

## Setup

1. Install dependencies:
```
pip install streamlit opencv-python speechrecognition
```

2. Add your `.mp4` videos to the `gestures/` folder with filenames like `hello.mp4`, `thanks.mp4`.

3. Run the app:
```
streamlit run app.py
```

## Future Additions
- Webcam sign recognition (reverse flow)
- TensorFlow-based sentence animation
- Mobile/desktop packaging
