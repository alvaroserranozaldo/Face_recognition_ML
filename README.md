# Face_recognition_ML

# The repository processes images stored in zip files within a designated directory. It identifies faces in these images, standardizes their sizes, and generates numerical representations for each face. The processed images, along with their identities, filenames within the zip files, and embeddings, are provided for additional analysis or application.


# Project Overview
This project focuses on facial recognition and image processing. It involves the development of a Python repository to analyze images stored in zip files within a designated directory. The main functionalities include:

- Face Detection and Standardization: The code identifies faces in images, standardizes their sizes, and generates numerical representations for each face.

- Data Processing: It extracts essential information such as identities, filenames within the zip files, and embeddings for each processed image.

- Analysis and Application: Processed images along with their associated data are provided for further analysis or application.

# Dependencies
To run the code successfully, ensure the following dependencies are installed:

- CMake: Download and install from CMake website, adding it to the system path.
- Desktop Development Tools for C++: Install from Visual Studio Microsoft.
- Python packages: Install the required Python packages using pip:

    !pip install face_recognition
    !pip install opencv-python==4.6.0.66
    !pip install cmake
    !pip install Image
    !pip install dlib 

# Usage
Loading Images:

Call the load_images_from_zip() function, providing the directory path containing the zip files.
Specify whether to process all images or just one image from each zip file using the allpics variable.
Nearest Neighbors:

The code computes the nearest neighbors based on face embeddings using the NearestNeighbors algorithm.
It determines the best matches for each query face and provides relevant information such as identities and filenames.
Accuracy Calculation (Optional):

If allpics is set to 1, the code calculates the accuracy of the face recognition model.

# Note
Ensure the necessary Python packages are installed.
Adjust the variables (allpics, num_neighbors) as per the desired functionality.
Large datasets may lead to increased computation time for nearest neighbor search.
