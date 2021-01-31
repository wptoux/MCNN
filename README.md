# MCNN
An unoffical demo for training crowd counting MCNN on Shanghai tech dataset (Part-B) with Pytorch and Pytorch-lightning. 

## Training Details
Use albumentations for image augmentation, and generate density maps on the fly with scipy. Some codes are borrowed from https://github.com/svishwa/crowdcount-mcnn. 

## Result On Test Set
MAE: 24.142405  
MSE: 1835.009493670886  

## Kaggle notebooks And Trained Weights
Training: https://www.kaggle.com/wptouxx/shtech-mcnn  
Eval: https://www.kaggle.com/wptouxx/shtech-mcnn-eval  
