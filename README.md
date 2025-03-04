HandTalk Decoder 

Steps to setup project:


#for creating venv(sign) and installing required packages
conda create --name sign python=3.7.1
conda activate sign
cd D:\Sign-Language #path of file
pip install -r requirements.txt
cd D:\Sign-Language\Code\Predictsigns #path of file 
pip install protobuf==3.20.3
set PROTOCOL_BUFFERS_PYTHON_IMPLEMENTATION=python



#for running server on port 3000
node -v
npm -v
npm install express
node server.js



#for pyaudio
pip install PyAudio-0.2.11-cp37-cp37m-win_amd64.whl
pip install pipwin
pipwin install PyAudio (or) pip install PyAudio
python main.py
