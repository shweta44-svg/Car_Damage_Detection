# Car Damage Detection

![Car Damage Detection Demo](https://huggingface.co/spaces/shweta44/Car-damage-detection/resolve/main/opengraph-image.jpg) <!-- Optional: Replace with actual demo image if available -->

## Overview

This project implements a **car damage detection system** using object detection techniques. It leverages **PyTorch** and **Detectron2** (a state-of-the-art library from Facebook AI Research) to identify and localize damages on car images.

The application features a user-friendly front-end built with **Streamlit**, allowing users to upload images and visualize detected damages in real-time.

The project is fully deployed as an interactive demo on **Hugging Face Spaces**:  
👉 [**Live Demo**](https://huggingface.co/spaces/shweta44/Car-damage-detection)

## Features

- Detects various types of car damages (e.g., dents, scratches, broken parts) using a trained Detectron2 model.
- Bounding box visualization with confidence scores.
- Simple and intuitive Streamlit web interface for uploading and processing images.
- End-to-end pipeline: from model inference to interactive UI.

## Technologies Used

- **Backend**: Python, PyTorch, Detectron2
- **Frontend**: Streamlit
- **Deployment**: Hugging Face Spaces

## Repository Contents

- `Code.ipynb`: Jupyter Notebook containing the model training, inference, and experimentation code.
- `app.py`: Main Streamlit application script for the web interface.
- `requirements.txt`: List of Python dependencies required to run the project.
- `README.md`: Project documentation (this file).

## Installation & Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/shweta44-svg/Car_Damage_Detection.git
   cd Car_Damage_Detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

   > Note: Detectron2 installation may require specific PyTorch and CUDA versions. Follow official Detectron2 installation guide if needed: https://detectron2.readthedocs.io/en/latest/tutorials/install.html

3. Run the Streamlit app locally:
   ```bash
   streamlit run app.py
   ```

4. Open your browser at `http://localhost:8501` to use the app.

## Usage

- Upload a car image through the Streamlit interface.
- The model will process the image and display bounding boxes around detected damage areas.
- Explore `Code.ipynb` for detailed model training and custom experimentation.

## Contributing

Contributions are welcome! Feel free to:
- Open issues for bugs or feature requests.
- Submit pull requests for improvements (e.g., better models, UI enhancements, additional damage classes).

## Acknowledgments

- Built using [Detectron2](https://github.com/facebookresearch/detectron2)
- Dataset and model specifics can be explored in the notebook.

For any questions, feel free to open an issue! 🚀
