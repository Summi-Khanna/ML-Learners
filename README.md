# ML-Learners - Prediction of BUY or SELL signals

## Overview of the Analysis
The idea of this project is to come up with the prediction of BUY or SELL signals for two particlar stocks `Amazon` and `Tesla` with the help of machine learning. The reason for choosing these two stocks were to see the model's performance for highly volatile stock like Tesla and for comparatively stable stock like Amazon. 
Based on the Twitter sentimatal score merged with historical prices of each company compared to S&P 500 (Index), we tried to prdict the signal of `Long Buy` or `Short Sell`.

The models we used to conduct our analysis:

- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree

---

## Data Sources:

- Historical prices of both teh stock from yahoo.finance
- Twitter Sentiment score from Kaggle 
- Market Sentiment score from survey of AAII.com

---

## Technologies:

It supports Python 3.7 and has been constructed using google colab and jupyter lab

Additionally, the following packages/libraries are used to run the analysis:

- [pandas](https://pypi.org/project/pandas/) - for analyzing data
- [numpy](https://pypi.org/project/numpy/) - for numerical operations
- [hvplot](https://pypi.org/project/hvplot/) - for visualizing data
- [holoviews](https://pypi.org/project/holoviews/) - for data analysis and visualization seamless and simple
- [sklearn](https://pypi.org/project/sklearn/) - for building machine learning models
- [nltk](https://pypi.org/project/nltk/) - for data preprocessing
- [vaderSentiment](https://pypi.org/project/vaderSentiment/3.1.1/) - for analysis of sentiments expressed in social media

---

## Installation Guide

Before running the application first install the following dependencies:

```
  pip install pandas 
  pip install numpy
  pip install hvplot
  pip install holoviews
  pip install sklearn
  pip install nltk
  pip install matplotlib

```

---

### II. Stages of Machine Learning:



## III. Results


## IV. Summary


## Technologies


---

## Installation Guide



---

## Usage




---

## Future Scope:

- Idea of finding a way to predict the buy or sell signal at present date
- For further model evaluation, we can calculate biased prediction using the lime library
- Alpaca order or experiment with Amazon Lex for building a Trading Bot

---

## Contributors
 
Team Leader:

- Matt Wojichowski 
  Email : mwojichowski@gmail.com <br>
  LinkedIn : https://www.linkedin.com/in/matt-wojichowski-cfa-caia-93a34a42/

Team Members:

- Tasnim Morbiwala
  Email : tasnim.morbiwala@gmail.com <br> 
  LinkedIn : https://www.linkedin.com/in/tasnim-morbiwala-58a4599/
  
- Rupika Ranjan Babu  
  Email : rupika10@gmail.com <br> 
  LinkedIn : [https://www.linkedin.com/in/rupika-r-125616a8/](https://www.linkedin.com/in/rupika-r-125616a8/)
  
- Summi Khanna  
  Email : sam.summo2812@gmail.com <br>
  LinkedIn : [https://www.linkedin.com/in/summi-khanna-004a60187/](https://www.linkedin.com/in/summi-khanna-004a60187/)

---

## License

MIT License

Copyright (c) 2021 Summi Khanna, Matt Wojichowski, Tasnim Morbiwala, Rupika Ranjan Babu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---