---

##Post-Larva Prawn Seed Detection System

**Project Overview**:  
The **Post-Larva Prawn Seed Detection System** is designed to automate the process of detecting and counting post-larva prawn seeds in images. By leveraging advanced **image processing techniques**, this system helps hatcheries optimize seed counting accuracy, reduce manual labor, and enhance operational efficiency.

---

**Key Features**:
- **Automated Counting**: Automatically detects and counts post-larva prawn seeds in images.
- **Image Processing**: Utilizes **OpenCV** for image pre-processing (grayscale conversion, Gaussian blur, and thresholding) and **contour detection** to identify seeds.
- **Customizable Parameters**: Allows adjustment of thresholding levels and seed size filters to adapt to different lighting and background conditions.
- **Speed and Efficiency**: Processes images in seconds, saving valuable time and improving throughput for hatchery operations.

---

**Technologies Used**:
- **Python**  
- **OpenCV**  
- **NumPy**  
- **Matplotlib**  

---

**How It Works**:
1. **Input**: A photo of post-larva prawn seeds is uploaded.
2. **Preprocessing**: The image is converted to grayscale, blurred to reduce noise, and thresholded to highlight seeds.
3. **Seed Detection**: The system identifies contours, filters out noise, and counts the seeds.
4. **Output**: The detected seeds are displayed on the image, with the total count shown.

---

**Potential Applications**:
- **Hatcheries**: Automate seed counting for quality control and inventory management.
- **Aquaculture Farms**: Accurately determine stocking densities for ponds.
- **Seed Transport**: Ensure consistent seed counts during transportation.

---
