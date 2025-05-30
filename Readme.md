# Readme
Author:Weijie Zhu, Liang Xie,Hanyu FU,Jiangling Zhang(me)

GHOST: A hybrid stock prediction framework with sentiment-guided integration of Mamba selection layer and Stock-wise Tokens Layer, effectively solving computational complexity challenges while leveraging GDELT multimodal sentiment analysis to enhance prediction robustness during market volatility. Empirical evaluations on CSI300 and NASDAQ datasets show that the framework achieves superior performance in directional classification and risk-adjusted returns compared to existing models, providing reliable support for quantitative investment decisions.

![4b5926ae437889c612d4ca8ce0ad95bb_720](https://github.com/user-attachments/assets/8fc6a4ca-bab3-40e4-864d-a73295e3f67b)

## Usage
i.   First, configure the environment according to the requirement.txt file

Ensure that the following libraries have aligned versions:

- causal-conv1d==1.1.0
- mamba-ssm==1.1.1
- torch==2.1.1+cu118
- torchvision==0.16.1+cu118
- torchaudio==0.16.1+cu118

ii. Download stock data to ```.\dataset\stock_data```  

market sentiment data to ```.\dataset```

iii. Finally, ```python run.py``` .

Don't forget to modify the number of input stocks and the number of features


## Dataset


We provide stock data from two markets: ```CSI300``` and ```NASDAQ100```. After data preprocessing, 189 and 64 stocks remain respectively, along with corresponding market sentiment data: ```CHN_NEWS_sentiment.csv``` and ```USA_NEWS_sentiment.csv```.


Download link: [https://pan.baidu.com/s/1shZ0xDFyGsf5a4h8JgMHxQ?pwd=6666]




