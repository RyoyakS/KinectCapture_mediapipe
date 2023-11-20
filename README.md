# KinectCapture_mediapipe
## Create virtual environment
### METHOD 1 : by .yaml file
conda env create -f mediapipe10.yaml
### METHOD 2 : Step by step
conda create --name mediapipe10 python=3.10
conda activate mediapipe10

## Installation 
pip install -r requirements.txt
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch



