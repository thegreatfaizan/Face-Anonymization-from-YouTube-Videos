# Face-Anonymization-from-YouTube-Videos
This repository contains code and resources for a project that implements face anonymization in YouTube videos. The project uses libraries such as face_recognition, pafy,
youtube-dl and opencv to detect the face of Imran Khan and blur it in the video.

## Directory Structure
The repository has the following directory structure:
- **dataset/**: This directory contains the image file **imran_khan.jpg** used to detect the face of Imran Khan and a video file **video.mp4** that is used as input.
- **Face_Blurring_from_YouTube_Videos.ipynb**: This is a Jupyter Notebook file containing the code that downloads the video from YouTube, detects the face of Imran Khan and
blurs it in the video. The output video is saved as output.mp4.

## Requirements
The following packages must be installed to run the code:

>face_recognition
>
>pafy
>
>youtube-dl==2020.12.2
>
>opencv

## Usage
1. Clone the repository:

  <code>git clone https://github.com/<username>/Face-Anonymization-from-YouTube-Videos.git</code>
  
  
2. Navigate to the repository directory:

  <code>cd Face-Anonymization-from-YouTube-Videos</code>
  
3. Open the Jupyter Notebook file "_Face Blurring from YouTube.ipynb_" and run the code to generate the output video.

4. The output video will be saved in the root directory of the repository as "_output.mp4_".



