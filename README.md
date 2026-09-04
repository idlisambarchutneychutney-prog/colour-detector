# Color Detector 

A simple computer vision web app built for the [Hack Club Lookalike](https://lookalike.hackclub.com/) challenge. This project uses a custom-trained Teachable Machine image model to detect and classify Fruit Loops by color (Yellow vs. Purple) in real-time using a live webcam feed.

##  Features

- **Real-Time Classification:** Detects Yellow and Purple  live via webcam.
- **In-Browser Processing:** Powered by TensorFlow.js and Teachable Machine—everything runs locally in the browser.
- **Live Confidence Output:** Displays real-time detection probabilities next to the predicted class.

##  Built With

- **HTML5 & JavaScript**
- **[Teachable Machine](https://teachablemachine.withgoogle.com/)** by Google
- **[TensorFlow.js](https://www.tensorflow.org/js)**

##  Teachable Machine Model

- **Model URL:** `https://teachablemachine.withgoogle.com/models/d9tlQhSG-/`
- **Classes:** 
  - `Yellow`
  - `Purple`

##  How to Run Locally

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (or use VS Code's Live Server extension).
3. Click **Start Camera**, grant webcam permissions, and hold up a Fruit Loop to test!
