# Option Pricing
The objective is to evaluate and compute financial options in real-time by streaming real-time stock data via Intrinio’s API 
to later be processed and evaluated using the widely used Black-Scholes Model. 
The gathered raw stock data will include metrics such as closing-/ opening prices, high/low, volume, the exact date etc. 
For the pricing purposes the adjusted closing price – adjusted for both dividends and splits – will be taken for the calculations. 
The processing and analytics part will be done in Python 3 applying Apache Spark, Apache Kafka as well as necessary and compatible libraries.

##Note
Due to the fact that the real-time stock data provider only granted us trial access until Sunday 02/09/2020, 
it wil not be possible to run the real-time producer/consumer with our provided keys at a later time. 
Nevertheless, all notebooks show appropriate output, in order to make it comprehensible for anyone reading the code.
