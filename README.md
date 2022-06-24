# GAN NFTs

Generating NFTs with GANs.

```
export PYTHONPATH="${PYTHONPATH}:/home/jerm-razer/github/gan-nft"
```

Training:
```
accelerate launch huggingnft/huggingnft/lightweight_gan/train.py --wandb --num_train_steps 200 --save_every 100 --evaluate_every 50 --dataset_name huggingnft/cryptopunks --load_from 15 --name test_punks_1
```

2022-06-20: 600 steps trained 
2022-06-21: 800 steps trained 
2022-06-22: 1000 steps trained 
