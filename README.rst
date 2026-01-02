#######################################################
Object Detection for Precision Agriculture (YOLOv5)
#######################################################

This repository contains implementations of the **YOLOv5** architecture for specific agricultural use cases. The primary focus is the identification and localization of **palm trees** to support autonomous farming systems, such as automated fertilizing and pesticide spraying drones or robots.

*******************
Key Features
*******************

- **Palm Tree Detection:** Trained models specifically optimized to identify palm trees from aerial or ground-level imagery.
- **Multi-Export Support:** Inference-ready code for PyTorch, ONNX, TFLite, and CoreML formats.
- **Automation Integration:** Designed to provide coordinate data for automated spraying and fertilizing systems.
- **High Performance:** Real-time detection capabilities suitable for deployment on edge devices (Jetson Nano, Raspberry Pi, etc.).

**************************
Technical Specifications
**************************

- **Architecture:** YOLOv5 (You Only Look Once v5)
- **Framework:** PyTorch
- **Inference Engines:** ONNX, TensorFlow Lite, CoreML
- **Focus:** Agrotech, Computer Vision, Precision Farming
- **Target Objects:** Palm Trees (Kelapa Sawit)

*******************
Installation Guide
*******************

1. **Clone the Project**
   .. code-block:: bash

      git clone https://github.com/afafirmansyah/object-detection-yolov5.git

2. **Environment Setup**
   - It is recommended to use a virtual environment or Conda.
   - Install the required dependencies:
     
     .. code-block:: bash

        pip install -r requirements.txt

3. **Running Detection**
   - To run inference using the pre-trained model on your images or videos:
     
     .. code-block:: bash

        python detect.py --weights best.pt --source path/to/your/images/

4. **Automation Output**
   - The system generates bounding box coordinates that can be sent to a controller (via MQTT or Serial) for automated spraying actions.

*******************
Sample Results
*******************

[Tempatkan gambar hasil deteksi pohon sawit dengan bounding boxes di sini]

*******
License
*******

This project is licensed under the MIT License - see the `license.txt` file for details.

*********
Contact
*********

**Ahmad Fauzi Firmansyah**
- **GitHub:** `afafirmansyah <https://github.com/afafirmansyah>`_
- **LinkedIn:** `ahmad-fauzi-firmansyah <https://linkedin.com/in/ahmad-fauzi-firmansyah/>`_
