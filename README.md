# Sri Lankan Paddy Field Detection AI Model

## Introduction
This repository contains an AI model specifically designed to detect paddy fields in Sri Lanka. Sri Lankan paddy fields, while not vast in size compared to some other regions, present unique challenges due to the mixed cultivation of various crops, presence of trees, roads, water bodies, and other elements within the fields. This AI model focuses exclusively on identifying and delineating areas where paddy cultivation is present, facilitating targeted fertilization using drones.

## Purpose
The primary purpose of this AI model is to assist farmers in optimizing fertilization processes by accurately identifying paddy fields within the landscape. By utilizing drones for fertilization in these specific areas, farmers can ensure efficient resource allocation while minimizing environmental impact and maximizing crop yield.

## Features
- **Paddy Field Detection**: The model employs advanced computer vision techniques to accurately identify and delineate paddy fields within the landscape.
- **Exclusion of Non-Paddy Areas**: Non-paddy areas such as other crops, trees, roads, and water bodies are ignored, focusing solely on areas suitable for paddy cultivation.
- **Integration with Drone Technology**: The model is designed to work seamlessly with drone technology, enabling targeted fertilization of detected paddy fields.
- **Two Apps**: The repository includes two applications:
  - **Real-Time Video App**: Allows users to process real-time video footage through the model, detecting paddy fields and other elements.
  - **Image Upload App**: Enables manual upload of images for analysis. Users can submit images, and the model will identify paddy fields within them.
- **Sample Photos**: A folder containing sample photos for testing and demonstration purposes.
- **Requirement.txt**: Lists all dependencies required to run the applications and utilize the model.

## Repository Structure
- **`/apps`**: Contains the source code for the Real-Time Video and Image Upload applications.
- **`/sample_photos`**: Sample photos for testing and demonstration purposes.
- **`requirements.txt`**: Lists all dependencies required to run the applications and utilize the model.

## Dependencies
- Python 3.x
- TensorFlow or PyTorch (depending on the chosen framework)
- OpenCV

## Contributions
Contributions to this project are welcome! Whether it's improving the model's accuracy, enhancing documentation, or optimizing deployment processes, your contributions can help make this tool more effective for farmers in Sri Lanka.

## License
This project is licensed under the [MIT License](LICENSE), allowing for both personal and commercial use with proper attribution.

## Contact
For inquiries or support related to this project, please contact [sahanwijesundara11@gmail.com].

---
*Disclaimer: This AI model is intended to assist farmers in optimizing fertilization processes and should be used as a supplementary tool. It is not a replacement for agricultural expertise or field observation.*
