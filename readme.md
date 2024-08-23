# Live Depth Prediction with MiDaS TFLite

## 🚀 Real-Time Depth Estimation in Your Browser

Explore the fascinating world of depth perception with this cutting-edge web application! Using the power of TensorFlow.js and the MiDaS (Monocular Depth Estimation) model converted to TensorFlow Lite format, this project brings real-time depth prediction right to your browser.

### ⚠️ Compatibility Warning
**Note:** This application currently does not work on Firefox due to compatibility issues with TensorFlow.js and TFLite. For the best experience, please use Chrome, Edge, or another Chromium-based browser.

### 🌟 Key Features

- **Live Depth Prediction**: Watch as the app instantly analyzes your camera feed and visualizes depth information in real-time.
- **TFLite Integration**: Leveraging the efficiency of TensorFlow Lite for faster, lighter-weight inference.
- **Interactive UI**: A sleek, user-friendly interface that allows for easy interaction and camera switching.
- **Cross-Device Compatibility**: Works seamlessly across desktop and mobile devices (except Firefox).
- **Average Depth Display**: Get instant feedback on the average depth of the scene.

### 🛠️ Technology Stack

- TensorFlow.js
- TensorFlow Lite
- HTML5 / CSS3
- JavaScript (ES6+)

### 🔬 MiDaS Model

This project utilizes the state-of-the-art MiDaS model for monocular depth estimation, converted to TFLite format for efficient in-browser execution. MiDaS excels at predicting relative depth from a single image, making it perfect for real-time applications.

### 🚀 Getting Started

Clone the repository, serve it with your favorite local server, and dive into the world of depth perception! No complex setup required – it's as simple as opening the HTML file in a modern web browser (remember, not Firefox!).

### 🤝 Contribute

We welcome contributions! Whether it's improving the UI, optimizing the model, adding new features, or helping with Firefox compatibility, your ideas and pull requests are appreciated.

Unlock the potential of computer vision in your browser – try out Live Depth Prediction today!

### 📚 Citation

If you use the MiDaS model or find this project helpful, please consider citing the following paper:

```
@article{DBLP:journals/corr/abs-1907-01341,
author    = {Katrin Lasinger and
Ren{'{e}} Ranftl and
Konrad Schindler and
Vladlen Koltun},
title     = {Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-Shot
Cross-Dataset Transfer},
journal   = {CoRR},
volume    = {abs/1907.01341},
year      = {2019},
url       = {http://arxiv.org/abs/1907.01341},
archivePrefix = {arXiv},
eprint    = {1907.01341},
timestamp = {Mon, 08 Jul 2019 14:12:33 +0200},
biburl    = {https://dblp.org/rec/journals/corr/abs-1907-01341.bib},
bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
