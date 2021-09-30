# Multi person KeyPoint_Image_Detection
Goal of this project is to detect the KeyPoints of multiple persons present in an image or a video.

Below are the tech stack used for the project:
1) CNN
2) Caffemodels trained on COCO and MPI
3) OpenCV 
4) Python

Trained models and Source code files are present in the repository. Input files and project recording are also added.

Steps for execution:
1) Caffemodels need to trained and downloaded before the start of the project.
    sh getModels.sh
2) python OpenPoseImage.py is the command to run to see the keypoints for a single person in the image.
3) python multi-person-openpose.py is the command to run to see the keypoints for multiple people in the image.
