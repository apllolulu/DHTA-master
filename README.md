# DHTA
Implement our ECCV 2020 work: Targeted Attack for Deep Hashing based Retrieval


The pretrained hashing model: [VGG11_32_for_IamgeNet](https://drive.google.com/file/d/1V6Nvr0DMhquqWwsl1CQtv0Kug7aXXTzx/view?usp=sharing)
Download and save this model at "models/imagenet_vgg11_32"

run the below command to reproduce our result.
```shell
python3 attack_imagenet.py --root [imagent-data-root] --reproduce --gpu-id [gpu-id]
```

The detail README is coming soon...

