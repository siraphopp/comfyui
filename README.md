# comfyui

# First Time

```bash
source ~/anaconda3/bin/activate
conda env create -f environment.yml -p ./env
conda activate ./env
pip3 install torch==2.9.0 torchvision==0.24.0 torchaudio==2.9.0 --index-url https://download.pytorch.org/whl/cu130
pip3 install onnx==1.19.1 onnxruntime==1.23.2
git clone https://github.com/comfyanonymous/ComfyUI.git
cd ComfyUI
pip3 install -r requirements.txt
cd custom_nodes
git clone https://github.com/ltdrdata/ComfyUI-Manager comfyui-manager
cd comfyui-manager
pip3 install -r requirements.txt
cd ..
git clone https://github.com/kijai/ComfyUI-WanVideoWrapper.git
cd ComfyUI-WanVideoWrapper
pip3 install -r requirements.txt
cd ../../..
conda deactivate
conda deactivate
```

# Next Time

```bash
source ~/anaconda3/bin/activate
conda activate ./env
cd ComfyUI
python3 main.py
conda deactivate
conda deactivate
```
