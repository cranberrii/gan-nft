# GAN NFTs

Generating NFTs with GANs.

Training on local machine:
```
$ export PYTHONPATH="${PYTHONPATH}:/home/jerm-razer/github/gan-nft"
```

```
$ accelerate launch huggingnft/huggingnft/lightweight_gan/train.py --wandb --num_train_steps 200 --save_every 100 --evaluate_every 50 --dataset_name huggingnft/cryptopunks --name test_punks_1 

# --load_from 15
```
