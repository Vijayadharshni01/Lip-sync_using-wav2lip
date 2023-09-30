# Wav2Lip Lip Syncing AI Model

This repository contains code to use the Wav2Lip model and also Wav2Lip-Gan model for lip-syncing, which synchronizes an audio file with a video file to create a seamless and natural visual and auditory experience for viewers.

## Getting Started

To get started with using the Wav2Lip model and Wav2Lip-Gan for lip-syncing, follow the steps below:

### What I used

- Google colab as environment.
- Took input from my google drive.
- Libraries are downloaded from [https://github.com/Rudrabha/Wav2Lip.git] this repository's requirement.txt file

## MY Code Step by Step
### Cloning the Repository

1. Clone this repository to your local machine using the following command:
git clone https://github.com/Rudrabha/Wav2Lip.git

### Download Pre-Trained Model Weights

2. Download the pre-trained model weights for Wav2Lip from [here](https://github.com/Rudrabha/Wav2Lipc) and place the `wav2lip.pth` file in the `Wav2Lip/checkpoints/` directory of the cloned repository.

### Installing Dependencies

3. Install the required Python packages by navigating to the `Wav2Lip` directory and running the following command:

### Download Face Detection Model

4. Download the face detection model weights from [here](https://www.adrianbulat.com/downloads/python-fan/s3fd-619a316812.pth) and place the `s3fd.pth` file in the `Wav2Lip/face_detection/detection/sfd/` directory.

### Input Files

5. Prepare your input files. In this example, the video file is named `dictator_orig_videotest.mp4`, and the audio file is named `myprojaudioshort.wav`. You can replace these with your own video and audio files.

### Running the Code

6. Run the lip-syncing script by executing the following command from within the `Wav2Lip` directory:

This command will synchronize the provided audio with the video, and the output video will be saved in the `Wav2Lip` directory.

## MY CODE LINK -

## OUTPUT OF MY CODE
I have tried using both Wav2Lip and Wav2Lip-Gan model to see which gives better result for your given input video. But both models didn't give a good output

### Wav2Lip model Output


https://github.com/Vijayadharshni01/Lip-sync_using-wav2lip/assets/68681505/b2bca34d-d959-41e8-b6ff-aa7d452192f7


### Wav2Lip-Gan model Output


https://github.com/Vijayadharshni01/Lip-sync_using-wav2lip/assets/68681505/e8838243-d7fe-4927-a369-823a732dda51


### Wav2Lip for my own input video with your given audio


https://github.com/Vijayadharshni01/Lip-sync_using-wav2lip/assets/68681505/03cea751-0f16-48e1-a6b8-1e6391823b5f



## Additional Information

- I adjustED the parameters in the `inference.py` script to fine-tune the lip-syncing process.
- For more details and options, refer to the [Wav2Lip GitHub repository](https://github.com/Rudrabha/Wav2Lip).

## License

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.

## Contact

Vijayadharshni
Email address: thisisdharshni@gmail.com




