# ANNt
Artificial Neural Network with 't' Distribution Portfolio 

Follow the steps:
1) Install and enable remotes package:
   install.packages('remotes')
   library(remotes)

2) Install and enable the ANNt package:
   install_github('aleoli05/ANNt')
   library(ANNt)
   
3) Install all required package in ANNt:
   install_required_pakage()

4) Import the assets series:
   Example: Assets_series (Tickers=c('AAPL','GOOG','CCBG','XOM','TSLA'),'^GSPC', '2018-01-03', '2023-09-07')

5) ANNt order generate:
   Exaple: ANNt_order ('2018-01-11', '2022-12-30','2023-01-09')
