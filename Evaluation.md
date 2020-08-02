Question - Which model has a lower loss?

Answer -   LSTM Stock Predictor using closing price has lower loss

Question - Which model tracks the actual values better over time?

Answer - Comparing the model plot between real vs predicted we can say that model using only fng valuse tracks the actuals values better than model using both fng and closing price  

Question - Which window size works best for the model?

Answer - For both LSTM Stock Predictor Using Fear and Greed Index model and  LSTM Stock Predictor Using Closing Prices performed well didn't perform well on increasing the window size.
         On running the LSTM Stock Predictor Using Fear and Greed Index model values decrease when window increased and vice versa for LSTM Stock Predictor Using Closing Prices, but the graph plotted between predicted            vs actual  shows that it is not going on sync when increasing the window size.
        