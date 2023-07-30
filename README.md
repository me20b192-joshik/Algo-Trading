# Algo-Trading
A project is developed, focusing on optimizing stock trading using an ensemble of algorithms, including **KNN, Decision Tree, Random Forest, and SVM.** The algorithmic model is designed to maximize profits by predicting trading signals through a momentum strategy based on various technical indicators.

The dataset comprises 10 years of stock details for five prominent stocks: RELIANCE, HDFC, ITC, INFOSYS, and TCS. By analyzing this data, we can predict the trend of the market index, which then serves as the basis for setting specific trading rules:

    If the next day's trend is Uptrend, the decision is to BUY.
    If a BUY decision already exists, we will HOLD.
    If the next day's trend is Downtrend, the decision is to SELL.
    If a SELL decision already exists, we will HOLD.

With these rules in place, the return of the strategy is calculated. The analysis resulted in an impressive accuracy of **94.2%**, demonstrating that the model is capable of minimizing losses compared to actual returns calculated based on the previous day's closing price. This indicates the potential effectiveness of our approach in stock trading and its ability to yield better results than traditional methods.
