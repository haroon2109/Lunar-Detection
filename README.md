# Lunar-Detection
This project aims to detect landslides and boulders in lunar surface .

# 🚀 Lunar Surface Anomaly Detector: AI-Powered Analysis

**Unveiling the Moon's Secrets: A Novel Algorithm for Detecting Landslides, Boulders, and Craters with AI Insights.**

---

## ✨ Project Overview

This project presents a cutting-edge web application demonstrating a novel algorithm designed to autonomously detect and quantify critical surface features on the Moon. Leveraging high-resolution imagery from India's **Chandrayaan-1 and Chandrayaan-2 missions**, our system aims to enhance future lunar mission safety, optimize landing site selection, and deepen our scientific understanding of lunar geological processes.

The application serves as an interactive showcase of our multi-stage detection workflow, augmented with powerful **AI-powered insights** to interpret findings and assess their implications.

---

## 💡 Key Features

Our solution combines advanced image processing with intelligent AI capabilities for comprehensive lunar surface analysis:

### 🛰️ Novel Detection Algorithm Workflow
Explore our robust, step-by-step algorithm:
1.  **Input Data:** Utilizes Chandrayaan-1/2 Terrain Mapping Camera (TMC), derived Digital Terrain Models (DTM), and Optical High Resolution Camera (OHRC) imagery.
2.  **Pre-processing & Normalization:** Radiometric, geometric corrections, and DTM generation.
3.  **Feature Extraction:** Derives topographic (slope, curvature) and textural (GLCM) characteristics.
4.  **Detection Modules (Hybrid Deep Learning Core):**
    * **Landslide Detection:** Employs a Random Forest Classifier for precise delineation.
    * **Boulder Detection:** Uses High-Resolution Image Processing with adaptive thresholding and enhanced edge detection.
5.  **Quantification & Metadata Output:** Provides precise measurements:
    * **Landslides:** Length, width, area, and estimated volume (where possible), along with latitude and longitude.
    * **Boulders:** Diameter, radius, estimated height, approximate volume, and latitude/longitude.
    * **Craters:** Detected and marked for comprehensive hazard mapping.
6.  **Output & Active Region Identification:** Generates graphical maps with marked features, detailed inventories, and identifies active geological regions.

### 🧠 AI-Powered Insights (Gemini API Integration)
Our application integrates Large Language Models (LLMs) via the Google Gemini API to provide intelligent, contextual information:
* **Geological Insight:** Get AI-generated interpretations and implications of simulated detection results.
* **Feature Description Generator:** Automatically generate descriptive text for summarized detection findings.
* **Mission Impact Assessor:** Evaluate potential challenges and opportunities for hypothetical lunar missions based on detected features.
* **Algorithm Step Explainer:** Get concise explanations for complex algorithm concepts on demand.

### 🖼️ Interactive Simulated Detection Visual
Upload your own lunar images and witness a live, simulated detection process directly within the browser! Our Canvas-based visualization will **mark landslides with green rectangles, boulders with green squares, and craters with yellow circles**, providing a dynamic demonstration of our algorithm's capabilities.

---

## 🌐 Live Demo

Experience the application firsthand:

👉 **[YOUR LIVE DEMO URL HERE]** 👈

---

## 🚀 Getting Started

To run this project locally and explore its features:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git)
    cd YOUR_REPOSITORY_NAME
    ```

2.  **Open the Application:**
    Simply open the `index.html` file in your preferred web browser.
    ```bash
    # On Windows
    start index.html
    # On macOS
    open index.html
    # On Linux
    xdg-open index.html
    ```

3.  **Enable AI Features (Optional but Recommended):**
    To utilize the AI-Powered Insights, you'll need a **Gemini API Key**.
    * **Get a Key:** Obtain your free API key from [Google AI Studio](https://aistudio.google.com/app/apikey).
    * **Paste into App:** In the web application, scroll to the "AI-Powered Insights" section and paste your key into the "Enter your Gemini API Key" input field.

---

## 🛠️ Technologies Used

* **HTML5:** Structure of the web application.
* **Tailwind CSS:** For a modern, responsive, and utility-first design.
* **Vanilla JavaScript:** Powers all interactive elements, dynamic content, and canvas rendering.
* **Google Gemini API:** Integrates advanced LLM capabilities for intelligent insights.
* **HTML Canvas API:** Used for the interactive, simulated feature detection visual.

---

## 📸 Visual Showcase

*(Optional: Replace this placeholder with a compelling screenshot or GIF of your application in action!)*
