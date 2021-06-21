# OadTR
Code for our paper: "OadTR: Online Action Detection with Transformers"

## Dependencies

* pytorch==1.6.0 
* json
* numpy
* tensorboard-logger
* torchvision==0.7.0

# Feature is coming soon...

# Prepare
* Unzip the anno file "./data/anno_thumos.zip"
* Download the feature

# Training
```
python main.py --num_layers 3 --decoder_layers 5 --enc_layers 64 --output_dir models/en_3_decoder_5_lr_drop_1
```
# Validation
```
python main.py --num_layers 3 --decoder_layers 5 --enc_layers 64 --output_dir models/en_3_decoder_5_lr_drop_1 --eval --resume models/en_3_decoder_5_lr_drop_1/checkpoint000{}.pth
```
