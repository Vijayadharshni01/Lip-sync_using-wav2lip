# Wav2Lip Lip Syncing

This repository contains code to use the Wav2Lip model and also Wav2Lip-Gan model for lip-syncing, which synchronizes an audio file with a video file to create a seamless and natural visual and auditory experience for viewers.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Cloning the Repository](#cloning-the-repository)
  - [Download Pre-Trained Model Weights](#download-pre-trained-model-weights)
  - [Installing Dependencies](#installing-dependencies)
  - [Download Face Detection Model](#download-face-detection-model)
  - [Input Files](#input-files)
  - [Running the Code](#running-the-code)
- [My Code](#my-code)
- [Output of My Code](#output-of-my-code)
  - [Wav2Lip Model Output](#wav2lip-model-output)
  - [Wav2Lip-GAN Model Output](#wav2lip-gan-model-output)
  - [Wav2Lip for My Own Input Video with Your Given Audio](#wav2lip-for-my-own-input-video-with-your-given-audio)
- [Why Lip Sync Didn't Work for Your Input Video](#why-lip-sync-didnt-work-for-your-input-video)
- [Conclusion](#conclusion)
- [Limitations](#limitations)
- [Contact](#contact)

## Getting Started

To get started with using the Wav2Lip model and Wav2Lip-Gan for lip-syncing, follow the steps below:

### What I used

- Google colab as environment.
- Took input from my google drive.
- Libraries are downloaded from [https://github.com/Rudrabha/Wav2Lip.git] this repository's requirement.txt file

## MY Code Step by Step
### Cloning the Repository
Clone this repository to your local machine using the following command: git clone https://github.com/Rudrabha/Wav2Lip.git

### Download Pre-Trained Model Weights
Download the pre-trained model weights for Wav2Lip from [here](https://github.com/Rudrabha/Wav2Lipc) and place the `wav2lip.pth` file in the `Wav2Lip/checkpoints/` directory of the cloned repository.

### Installing Dependencies
Install the required Python packages by navigating to the `Wav2Lip` directory and running the following command:

### Download Face Detection Model
Download the face detection model weights from [here](https://www.adrianbulat.com/downloads/python-fan/s3fd-619a316812.pth) and place the `s3fd.pth` file in the `Wav2Lip/face_detection/detection/sfd/` directory.

### Input Files
Prepare your input files. In this example, the video file is named `dictator_orig_videotest.mp4`, and the audio file is named `myprojaudioshort.wav`. You can replace these with your own video and audio files.

### Running the Code
Run the lip-syncing script by executing the following command from within the `Wav2Lip` directory:
cd Wav2Lip
pip install -r requirements.txt
This command will synchronize the provided audio with the video, and the output video will be saved in the `Wav2Lip` directory.

### NOTE: I HAVE ADJUSTED THE `inference.py` script to avoid some errors

## My Code - You can access my code and experiment with it by following this [https://colab.research.google.com/drive/1cHIMZBjhsTTtgpbIIc2MdHDZ7ik9T2L1?usp=sharing]

## Output of My Code
I have tried using both the Wav2Lip and Wav2Lip-GAN models to see which gives better results for your given input video. However, both models didn't produce satisfactory outputs for your given video.

### Wav2Lip Model Output
https://github.com/Vijayadharshni01/Lip-sync_using-wav2lip/assets/68681505/b2bca34d-d959-41e8-b6ff-aa7d452192f7

### Wav2Lip-GAN Model Output
https://github.com/Vijayadharshni01/Lip-sync_using-wav2lip/assets/68681505/e8838243-d7fe-4927-a369-823a732dda51

### Wav2Lip for My Own Input Video with Your Given Audio
https://github.com/Vijayadharshni01/Lip-sync_using-wav2lip/assets/68681505/03cea751-0f16-48e1-a6b8-1e6391823b5f

## Why Lip Sync Didn't Work for Your Input Video
The issue could be related to improper lip detection in your video.

### Conclution:
Lip sync worked perfectly with my own video and your audio but did not work well with the video given by you.

## Limitations in this model
- This model works only in low resolution video as it is trained with low resolution videos only.
- Videos longer than a minute may result in errors.

## Contact

Vijayadharshni
Email address: thisisdharshni@gmail.com
Github repository link: https://github.com/Vijayadharshni01/Lip-sync_using-wav2lip




