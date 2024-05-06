# Furniture Visualization Tool

This project is a furniture visualization tool that allows users to seamlessly integrate objects into new environments for enhanced customer visualization. 
It enables users to upload a photo of their room and virtually place selected furniture items within it, as well as experiment with different textures on these items.

## Team Members
- Prasad Gole - gole2@illinois.edu
- Akash Kumar - akuma9@illinois.edu
- Eilbera (Ellie) Mansour - eilbera2@illinois.edu
- Arul Viswanathan - arulv2@illinois.edu

## Getting Started

To run the notebook `Furniture_Tool_Combined.ipynb`, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Prasad-py/CS445_Group_Project.git
   ```

2. Install the required dependencies:
   ```
   pip install simple-lama-inpainting segment-anything scipy matplotlib numpy pillow opencv-python
   ```

3. Download the pre-trained SAM model checkpoint (`sam_vit_h_4b8939.pth`) and place it in the project directory.

4. Open the `Furniture_Tool_Combined.ipynb` notebook in Jupyter Notebook or JupyterLab.

5. Update the file paths in the notebook to match your local directory structure:
   - Set `datadir` to the path of your project data directory.
   - Update the paths for input images (`image_path`, `couch_path`, `couch10_path`, etc.) to point to the correct image files in the `Project_Files` directory.
   - Modify the output paths (`output_filename`, `save_path`, etc.) to specify where you want to save the generated images. Currently stores in `images/output`.

6. Run the notebook cells in sequential order to execute the code and generate the results. Some results take upwards of 10 mins to get processed.

7. The input images used in the notebook are located in the `Project_Files` directory, and the output images will be saved in the `images/output` directory.

## Results

The project demonstrates the effectiveness of the approach in seamlessly inserting objects into new contexts and enhancing their visual appearance through texture transfer and blending techniques. 
The results showcase the potential of the tool in creating visually compelling and realistic object insertions.
