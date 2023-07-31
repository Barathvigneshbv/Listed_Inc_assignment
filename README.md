# Listed_Inc_assignment
Assignment - 2 : Real_time-voice-cloning
Setup
1. Install Requirements
Both Windows and Linux are supported. A GPU is recommended for training and for inference speed, but is not mandatory.
Python 3.7 is recommended. Python 3.5 or greater should work, but you'll probably have to tweak the dependencies' versions. I recommend setting up a virtual environment using venv, but this is optional.
Install ffmpeg. This is necessary for reading audio files.
Install PyTorch. Pick the latest stable version, your operating system, your package manager (pip by default) and finally pick any of the proposed CUDA versions if you have a GPU, otherwise pick CPU. Run the given command.
Install the remaining requirements with pip install -r requirements.txt

2. Run the inference part
Before you download any dataset, you can begin by testing your configuration with:
python demo_cli.py

3. Launch the Toolbox
python demo_toolbox.py -d <datasets_root>
or
python demo_toolbox.py

Also Find the Screenshots in the evidences folder.
Pretrained weights used: https://drive.google.com/drive/folders/1C7BztCdXcNUNAWqsueYV8bxTyVlaQxS2?usp=drive_link
Input audio used: https://drive.google.com/file/d/1weZ_RtPI7IjgNz2oEOr0MZbPV0_3DBXf/view?usp=drive_link
Output Synthesised audio: https://drive.google.com/file/d/1I0Sgf9kYFBC7_ntgwR86wfnRqO4guBeI/view?usp=drive_link

Thank you!!
