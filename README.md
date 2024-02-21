# LiDAR Exploration with Open3D

## Overview
This project focuses on analyzing and visualizing 3D point cloud data from LiDAR datasets utilizing Python and Open3D. It showcases advanced computational techniques for data preparation, voxelization, mesh creation, and transforming local coordinates into geographical coordinates.

## Setup

### Prerequisites
Ensure Python is installed on your system. This project requires:
- laspy
- Open3D
- numpy
- matplotlib
- folium
- plotly
- pandas
- pyproj
- scikit-learn
- trimesh

### Installation
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/WibiSanaSini/LiDAR-Exploration-with-Open3D.git
cd LiDAR-Exploration-with-Open3D
```
Install required libraries:
```bash
pip install laspy open3d numpy matplotlib folium plotly pandas pyproj scikit-learn trimesh
```
## Running the Project

### Data Preparation
1. Place your `.las` dataset in respective directory.
2. Update the `input_file` variable in the notebook to the path of your dataset.

### Execution
Open the Jupyter Notebook:
```bash
jupyter notebook LiDAR_Exploration.ipynb
```
Execute the cells sequentially to import libraries, install modules, prepare data, and perform analysis and visualization.

Detailed instruction and reasoning are fully documented inside the notebook.

## Features
- **Data Preparation:** Import and configure LAS dataset.
- **Data Analysis:** Explore statistical information and visualize point clouds in 3D.
- **Voxelization & Mesh Creation:** Transform data into voxel grids and meshes.
- **Coordinate Transformation:** Convert local coordinates into geographical coordinates for accurate mapping.

## Contributing
Contributions are welcome. Please fork the repository and submit a pull request with your enhancements.

## License
This project is under the MIT License. See the [LICENSE](LICENSE) file for more details.
