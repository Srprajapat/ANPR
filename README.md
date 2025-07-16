# Automatic Number Plate Recognition (ANPR) System

## Overview

This ANPR system uses **EasyOCR** for license plate recognition, designed for parking management, security checkpoints, or vehicle tracking applications. The system captures vehicle images, processes them to detect license plates, and matches them against a registered database.

## Key Features

- 📸 **Image-based plate detection** using EasyOCR
- 🔍 **Text extraction** from license plates
- 🗃️ **Database integration** for vehicle/owner lookup
- 📊 **Parking management** capabilities
- 🖥️ **Simple command-line interface**

## Prerequisites

### Hardware Requirements
- Camera or image capture device
- Minimum 4GB RAM (8GB recommended)
- CPU with SSE4.2 instruction set

### Software Requirements
- Python 3.7-3.10 (3.11+ not fully supported by some dependencies)
- pip package manager

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Srprajapat/ANPR.git
   cd anpr-system
   ```
2. **Create and activate virtual env**:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate    # Windows
   ```
3. **Install dependencies**:
  ```bash
  pip install easyocr opencv-python imutils
  ```
## System Architecture 
```
ANPR System
├── Image Capture
├── Preprocessing
├── Plate Detection (EasyOCR)
├── Text Validation
├── Database Lookup
└── Output/Logging
```
## Usage
1. Register users and vehicles
3. Process vehicle images

## Contributing

Feel free to fork this repository and make improvements. Pull requests are welcome! 🚀


## Author
Seetaram Prajapat - [GitHub Profile](https://github.com/Srprajapat)

## Contact

For any questions or suggestions, reach out to me at [**seetaram.22jics083@jietjodhpur.ac.in**](mailto\:seetaram.22jics083@jietjodhpur.ac.in) or connect on [LinkedIn](https://www.linkedin.com/in/seetaram-prajapat).

