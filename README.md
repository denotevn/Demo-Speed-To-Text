# Demo-Speed-To-Text 
+ demo.ipynb là demo với gradio đầu vào là giọng nói của mọi người
+ SpeedToText là demo đọc từ file âm thanh tương tự như huggingface đã hướng dẫn
## Create venv
+ python3 -m venv env
+ source env/bin/activate
## Install for Ubuntu 22.04
+ **CUDA 11.7:** pip3 install torch torchvision torchaudio
+ pip install gradio
+ pip3 install transformers==4.9.2
+ pip install soundfile