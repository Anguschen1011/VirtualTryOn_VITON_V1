# Virtual Try-On Using VITON Dataset

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
SSIM score  :  0.7907
LPIPS score :  0.2130
FID score   : 12.7824
=======================
```  

## 6. Hardware
The model architectures proposed in this study are implemented using the PyTorchDL framework, and training is conducted on hardware featuring an Intel® Core™ i7-12700 CPU and Nvidia RTX 3060 12GB graphics processing unit (GPU).
