# 基於可組裝串聯外觀流之虛擬服裝試穿

## ITAC 2024
Paper : [論文](docs/paper.pdf)  
Certificate : [刊登證明](docs/論文刊登證明.pdf)  

## 1. Setting Data's Root 
Get a .pkl file contain data's path 
```
python 001_make_Dataset.py
```
If you would like to change the data, weights, output path or other settings,   
you can find them in ```config.py```.

## 2. Training
Start training 
```
python 002_train_gmm.py
```

## 3. Testing 
Start testing
```
python 003_test.py
```

## 4. Evaluation

```
=======================
FID score   : 24.4623
=======================
```  

## 6. Hardware
The model architectures proposed in this study are implemented using the PyTorchDL framework, and training is conducted on hardware featuring an Intel® Core™ i7-12700 CPU and Nvidia RTX 3060 12GB graphics processing unit (GPU).
