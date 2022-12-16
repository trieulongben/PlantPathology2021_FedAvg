# PlantPathology2021_FedAvg[![arXiv](https://img.shields.io/badge/arXiv-1602.05629-f9f107.svg)](https://arxiv.org/abs/1602.05629)
![Python](https://upload.wikimedia.org/wikipedia/commons/1/1b/Blue_Python_3.9_Shield_Badge.svg)
![Flask](https://img.shields.io/badge/flask-v1.1.1-blue)
![VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)

`FedAvg (Federated Algorithm)` : [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/abs/1602.05629)


An thesis project of me submitted to International University - Vietnam National University. \
Implementation of FedAvg federated learning algorithm for Plant Pathology 2021 dataset (multi-label) with MobilenetV2 model and Wandb train logging included. 

## Description

Model : MobilenetV2 \
Loss: torch.nn.BCEWithLogitsLoss() \
Accuracy: sklearn.metrics.accuracy_score \
Dataset transfrom:
+ Normalize:  mean: (124.4455, 159.9584, 104.1832), std: (47.1528, 41.4626, 49.2424)
+ Resized: 512x512


## Environment setup

Environment dependency is also use for meb, mobile application part of this project. Thus there will be many redudant for training model process only.

```bash
conda env create -f environment.yml
```



## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
