# ST-RiskNet

融合局部和全局时空特征的交通事故风险预测
第37届CCF中国数据库学术会议 (NDBC 2020). 计算机科学与探索,

# Usage

train model on NYC:
```
python train.py --config config/nyc/STRiskNet_NYC_Config.json --gpus 0
```


train model on Chicago:
```
python train.py --config config/chicago/STRiskNet_Chicago_Config.json --gpus 0
```

# Configuration

The configuration file config.json contains three parts: Data, Training and Predict:
