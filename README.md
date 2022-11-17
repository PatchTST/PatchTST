# PatchTST

This is an offical implementation of PatchTST: "A Time Series is Worth 64 Words: Long-term Forecasting with Transformers."

# Getting Started

We seperate our codes for supervised learning and self-supervised learning into 2 folders. Please choose the one that you want to work with.

## Supervised Learning

1. Install requirements. ```pip install -r requirements.txt```

2. Download data. You can download all the datasets from [Autoformer](https://drive.google.com/drive/folders/1ZOYpTUa82_jCcxIdTmyr0LXQfvaM9vIy). Create a seperate folder ```./dataset``` and put all the csv files in the directory.

3. Training. All the scripts are in the directory ```./scripts/EXP-LongForecasting/PatchTST```. The default model is PatchTST/42. For example, if you want to get the multivariate forecasting results for weather dataset, just run the following command, and you can open ```./result.txt``` to see the results once the training is done:
```
sh ./scripts/EXP-LongForecasting/PatchTST/weather
```
