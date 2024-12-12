# Computer Vision Final Project: 3D Object Visualization

This project leverages computer vision techniques to generate 3D models from images using depth estimation and visualization. The goal is to process images, generate depth maps, create point clouds, and finally visualize 3D models in the browser. It uses Hugging Face for depth estimation, Open3D for 3D visualization, and Python for implementing the core logic.

## Project Overview

This project aims to demonstrate the process of converting a 2D image into a 3D model using depth estimation and computer vision techniques. The following steps outline the flow of the project:

1. **Depth Estimation**: A pre-trained model from Hugging Face is used to predict depth maps from 2D images.
2. **Point Cloud Generation**: The depth map and RGB image are combined to generate a point cloud using Open3D.
3. **3D Mesh Generation**: From the point cloud, a 3D mesh is created using Poisson surface reconstruction.
4. **3D Model Visualization**: The 3D model is visualized and saved for use in a web environment.

## Technologies Used

- **Python**: The primary programming language for data processing and model execution.
- **Open3D**: Used for creating, processing, and visualizing 3D point clouds and meshes.
- **Hugging Face**: For using pre-trained depth estimation models.
- **Matplotlib & Plotly**: For visualizing the output depth map and point cloud.
- **Flask / FastAPI** (Optional for Web Interface): For serving the 3D model to a web browser.

## Setup and Installation

To get started with this project, follow these steps:

### Prerequisites

- Python 3.7 or later
- Install the required libraries via `pip` or `conda`.

### Clone the Repository

```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository

