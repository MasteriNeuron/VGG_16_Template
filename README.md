# Creation of Conda Enviroments
"conda create --prefix ./env python=3.11 -y"
<br>
# Activate Conda env
activate env/
<br>
#Install requirements.txt
pip install -r requirements.txt
<br>
###  Here we are using transfer learning on VGG-16 model which was trained on  imagenet dataset. Here we are doing prediction on Hymenoptera_data(ants/bees)
"https://download.pytorch.org/tutorial/hymenoptera_data.zip"

1. first go with VGG_16.ipynb file to play all.
2. then go with tflite file to quantized the model.
