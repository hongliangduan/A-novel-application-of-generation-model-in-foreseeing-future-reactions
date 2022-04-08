## Build_vocaby
`python build_vocab.py --mols=my_data.txt --save_dir=my_dir --vocab_name=my_name --weights_name=my_name`


## Train

`python train.py --model transvae --data_source custom --train_mols_path my_train_data.txt --test_mols_path my_test_data.txt --vocab_path my_vocab.pkl --char_weights_path my_char_weights.npy --d_model 256 --d_feedforward 1024 --save_name my_model`
 
 
## Sampling

`python scripts/sample.py --model transvae --model_ckpt checkpoints/my_ckpt --mols data/my_train_data.txt --sample_mode high_entropy`

 
